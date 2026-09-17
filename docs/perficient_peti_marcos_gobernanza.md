# Perficient: Marcos de Gobernanza de TI (COBIT, TOGAF, ISO 42001, ITIL) para la Estructuración del PETI

## 1. Integración Metodológica de Marcos de Referencia en el PETI
Para que el Plan Estratégico de Tecnologías de Información (PETI) de Perficient posea un estándar internacional de gobernanza, se integran cuatro marcos de referencia clave [2, 6, 22, 25]:

```
+-----------------------------------------------------------------------+
|                         PETI PERFICIENT                               |
+-----------------------------------------------------------------------+
|  1. COBIT 2019       : Alineación Estratégica y Objetivos de Negocio  |
|  2. TOGAF ADM        : Arquitectura Enterprise (Negocio, Datos, App, HW)|
|  3. ISO 42001 / NIST : Gobernanza del Ciclo de Vida de IA (Responsible AI)|
|  4. ITIL 4 / DevSecOps: Operación, Observabilidad (Grafana) y ALM      |
+-----------------------------------------------------------------------+
```

---

## 2. Componentes de Gobernanza Aplicados al PETI

### 2.1. COBIT 2019 (Gobernanza y Gestión de TI)
* **Alineación Estratégica**: Garantizar que las iniciativas tecnológicas de Perficient (ingeniería digital, IA, analítica) agreguen valor directo a las metas comerciales del cliente y del negocio corporativo [6, 25, 86].
* **Evaluación de Riesgos**: Establecer una matriz de riesgos tecnológicos abarcando vulnerabilidades de software, ciberseguridad y continuidad operativa [2, 25].

### 2.2. TOGAF ADM (Arquitectura Empresarial)
* **Arquitectura de Negocio**: Definición del modelo de consultoría multiproveedor, roles (PM, Line Manager, Tech Lead, Seniors, Juniors) y rituales ágiles Scrum [21, 25, 91, 97].
* **Arquitectura de Datos y Aplicaciones**: Integración del ALM en **Azure DevOps** (Wikis, Boards, Tickets), ERP corporativo **Oracle** para control de tiempos, e infraestructura multiproveedor [21, 22, 93, 98].
* **Arquitectura Tecnológica / Nube**: Segregación formal de ambientes de despliegue (**DEV**, **QA/CA**, **PROD**) sobre infraestructura **AWS** (EC2, S3, SaaS) y monitoreo con **Grafana** [22, 94].

### 2.3. ISO 42001 & NIST AI RMF (Gobernanza de Inteligencia Artificial)
* **AI Management System (AIMS)**: Estándar para la gobernanza responsable de modelos y asistentes de IA (Amazon Bedrock, Amazon Q, Kiro, Claude) [2, 6, 18, 20].
* **Controles de Acción y Permisos en Agentes (Policy-as-Code)**: Implementación de barreras de seguridad para limitar los permisos de ejecución de herramientas automatizadas por parte de modelos cognitivos [27, 34, 35].
* **Inventario Traceable de Sistemas IA**: Registro activo de componentes de IA, proveedores de modelos, orígenes de datos y registros de auditoría [30, 31, 39].

### 2.4. ITIL 4 y Operaciones DevSecOps
* **Gestión de Servicios e Incidentes**: Flujo de remediación continua de tickets de bugs, mejoras y vulnerabilidades auditadas por Fluid Security [20, 21, 92, 93].
* **Observabilidad Centralizada**: Trazabilidad multiambiente de logs en **Grafana** para detección rápida de regresiones antes del paso a producción [22, 94].

---

## 3. Matriz de Mapeo Operativo Interno vs. Estándar Normativo PETI

| Dominio Operativo Perficient | Herramienta / Plataforma | Marco de Gobernanza Relacionado |
| :--- | :--- | :--- |
| **Registro y Control de Tiempos** | Oracle ERP / Azure DevOps | COBIT 2019 (APO06 / DSS01) [26, 98] |
| **Gestión del Ciclo de Vida ALM** | Azure DevOps (Wiki, Boards, Sprints) | ITIL 4 / TOGAF Application Architecture [21, 93] |
| **Seguridad de Aplicaciones y Pentesting** | Fluid Security / Azure DevOps | ISO 27001:2022 (A.8.28 / A.8.29) / SOC 2 [20, 84, 92] |
| **Observabilidad y Monitoreo de Logs** | Grafana (DEV, QA, PROD) | ITIL 4 Service Operation / ISO 27001 (A.8.15) [22, 94] |
| **Infraestructura y Servicios Cloud** | AWS (EC2, S3, SaaS) | TOGAF Technology Architecture / COBIT [22, 94] |
| **Gobernanza de Herramientas de IA** | AWS Bedrock / Amazon Q / Kiro | ISO 42001 / NIST AI RMF / OWASP GenAI [2, 18, 20, 90] |
