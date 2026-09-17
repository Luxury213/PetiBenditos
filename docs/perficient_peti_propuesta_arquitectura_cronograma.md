# Plan Estratégico de Tecnologías de Información (PETI) - Perficient
## Propuesta de Arquitectura Estratégica y Cronograma de Ejecución (2026-2028)

---

## 1. Resumen Ejecutivo y Marco Estratégico

El presente documento constituye la **Propuesta de Arquitectura Estratégica y Cronograma de Ejecución del PETI** para **Perficient**, diseñado para guiar la transformación tecnológica y operativa de la organización hacia un modelo **AI-Native**, manteniendo los más altos estándares de gobernanza, calidad de software y ciberseguridad.

### 1.1. Objetivos Estratégicos del PETI
1. **Liderazgo AI-First**: Consolidar la capacidad de ingeniería digital e inteligencia artificial (Amazon Bedrock, Amazon Q, Claude, Kiro) como motor central del ciclo de vida de desarrollo de software y servicios al cliente.
2. **Excelencia en Gobernanza y Ciberseguridad**: Mantener la conformidad continua con **ISO 27001:2022** y **SOC 2 Type II**, incorporando el marco de gestión **ISO 42001** y **NIST AI RMF** para la IA.
3. **Eficiencia Operativa e Interoperabilidad Multiambiente**: Optimizar la gestión de proyectos mediante **Azure DevOps**, observabilidad centralizada en **Grafana** y la segregación estricta de ambientes (DEV, QA, PROD).
4. **Desarrollo de Talento y Escalabilidad Regional**: Fortalecer las capacidades del personal técnico y administrativo a través de certificaciones oficiales (*Cloud Architecture*, *AI Fundamentals*) y el modelo de trabajo *Nearshore*.

---

## 2. Propuesta de Arquitectura Estratégica de TI (Estado Futuro / TO-BE)

La arquitectura estratégica se articula bajo la metodología **TOGAF ADM**, estructurada en cinco dominios clave:

```
+-----------------------------------------------------------------------------------+
|                           ARQUITECTURA DE NEGOCIO                                 |
|   Modelo Nearshore | Agilidad Boutique | Células Especializadas | Oracle ERP      |
+-----------------------------------------------------------------------------------+
                                          |
                                          v
+-----------------------------------------------------------------------------------+
|                           ARQUITECTURA DE INFORMACIÓN Y DATOS                     |
|   Databricks Brickbuilder | Snowflake Horizon Catalog | AI SOC & Observabilidad |
+-----------------------------------------------------------------------------------+
                                          |
                                          v
+-----------------------------------------------------------------------------------+
|                        ARQUITECTURA DE APLICACIONES E IA                          |
|   Bedrock / Amazon Q / Kiro / Claude | Azure DevOps (ALM) | Fluid Security Pentest|
+-----------------------------------------------------------------------------------+
                                          |
                                          v
+-----------------------------------------------------------------------------------+
|                        ARQUITECTURA DE NUBE E INFRAESTRUCTURA                     |
|   AWS EC2/S3/SaaS | Multi-cloud (Azure/GCP) | Grafana Log Monitoring | DEV/QA/PROD |
+-----------------------------------------------------------------------------------+
                                          |
                                          v
+-----------------------------------------------------------------------------------+
|                        ARQUITECTURA DE CIBERSEGURIDAD Y SGSI                      |
|   ISO 27001:2022 | SOC 2 Type II | MFA & Laptop Encryption | ISO 42001 AI GRC      |
+-----------------------------------------------------------------------------------+
```

### 2.1. Arquitectura de Negocio
* **Modelo de Servicio**: Consultoría de ingeniería digital en la modalidad *Nearshore*, combinando escala global con agilidad de entrega local.
* **Gobernanza Operativa**: Estructura piramidal con claridad de roles (*Product Manager*, *Line Manager*, *Technical Lead*, *Mid Developers*, *Junior Associates*).
* **Gestión de Tiempos y Recursos**: Control de horas administrativas en **Oracle ERP** y seguimiento operacional de entregables en **Azure DevOps**.

### 2.2. Arquitectura de Información y Datos
* **Plataformas Enterprise**: Consolidación de lagos de datos y analítica en **Databricks** y **Snowflake Horizon Catalog**.
* **Observabilidad de Datos**: Trazabilidad de logs y telemetría de negocio integrados en tableros de **Grafana**.

### 2.3. Arquitectura de Aplicaciones e Inteligencia Artificial
* **Cadena de Herramientas AI-First**: Aprovisionamiento normativo de licencias para **Amazon Bedrock**, **Amazon Q**, **Kiro** y **Claude** vinculadas al correo corporativo del cliente.
* **Ciclo de Vida de Software (ALM)**: Gestión agilizada bajo **Scrum** en **Azure DevOps** (Wiki, Boards de Sprint, trazabilidad de tickets de *Bugs*, *Fixes* y *Enhancements*).
* **Calidad y Remedación Defensiva**: Integración de hallazgos de seguridad derivados de **Fluid Security** directamente en la cola de trabajo (*Backlog*) del equipo de desarrollo.

### 2.4. Arquitectura de Nube e Infraestructura
* **Proveedor Cloud Primario**: **Amazon Web Services (AWS)** utilizando servicios de cómputo (**EC2**), almacenamiento (**S3**) y componentes SaaS.
* **Segregación Estricta de Entornos**: Ambientes aislados para **Desarrollo (DEV)**, **Pruebas (QA / CA)** y **Producción (PROD)**.
* **Monitoreo Multiambiente**: Centralización de trazabilidad de errores y *logs* de aplicación mediante **Grafana**.

### 2.5. Arquitectura de Ciberseguridad y Gobernanza (SGSI)
* **Certificación Base**: Mantenimiento del estándar **ISO 27001:2022** (Certificado ISMS-PE-101123 por A-Lign) y acreditación **SOC 2 Type II**.
* **Seguridad de Endpoint**: Cifrado obligatorio de ordenadores portátiles, autenticación multifactor (MFA), VPNs seguras y filtrado avanzado de correos.
* **Gobernanza de IA**: Implementación de controles de la norma **ISO/IEC 42001** y marco **NIST AI RMF** (Gobernar, Mapas, Medir, Gestionar) para la prevención de riesgos de *prompt injection*, fugas de código o sesgos.

---

## 3. Cronograma de Ejecución e Implementación (Hoja de Ruta 2026-2028)

El cronograma se divide en **cuatro fases estratégicas semestrales** durante un horizonte de 24 meses:

| Fase | Denominación Estratégica | Período | Objetivos Principales | Entregables Clave |
| :--- | :--- | :--- | :--- | :--- |
| **Fase 1** | **Gobernanza, SGSI y Habilitación AI-First** | Meses 1 - 6 | - Formalizar políticas de IA responsable (ISO 42001 / NIST RMF).<br>- Reacreditar ISO 27001:2022.<br>- Centralizar solicitud de licencias Bedrock/Amazon Q. | - Manual de IA Responsable.<br>- Auditoría de Renovación ISO 27001.<br>- Protocolo de Aprovisionamiento de Licencias. |
| **Fase 2** | **Estandarización ALM y Observabilidad Nube** | Meses 7 - 12 | - Homologar plantillas de Azure DevOps por célula.<br>- Implementar monitoreo unificado con Grafana en DEV/QA/PROD.<br>- Automatizar flujo Fluid Security -> Azure DevOps. | - Pipeline CI/CD Estandarizado.<br>- Dashboard de Observabilidad Grafana.<br>- Conector Fluid-DevOps. |
| **Fase 3** | **Escalamiento AI-Native e Integración Analítica** | Meses 13 - 18 | - Desplegar arquitecturas RAG corporativas en clientes estratégicos.<br>- Integrar plataformas Databricks y Snowflake Horizon.<br>- Capacitar al 100% del personal en herramientas AI. | - Casos de Uso GenAI en Producción.<br>- Data Lake Enterprise Conectado.<br>- Plan de Certificaciones Técnicas Completado. |
| **Fase 4** | **Optimización Operativa y Madurez Tecnológica** | Meses 19 - 24 | - Realizar auditoría externa SOC 2 Type II.<br>- Medir KPIs de ROI tecnológico y eficiencia del PETI.<br>- Ajuste y actualización de la arquitectura TO-BE. | - Informe SOC 2 Type II Attestation.<br>- Balance de Gestión del PETI 2026-2028.<br>- Actualización del Plan Tecnológico. |

---

## 4. Matriz de Indicadores de Gestión (KPIs) y Gobernanza del PETI

### 4.1. Indicadores Clave de Desempeño (KPIs)

1. **Adopción de Inteligencia Artificial (AI-First Rate)**:
   * **Métrica**: % de células de desarrollo que utilizan activamente asistentes de código (Amazon Q / Kiro) y modelos cognitivos aprobados.
   * **Meta**: > 85% para el final del Mes 12.
2. **Tiempo Medio de Remedación de Vulnerabilidades (MTTR - Security)**:
   * **Métrica**: Tiempo transcurrido entre la detección en Fluid Security y el cierre del ticket en Azure DevOps.
   * **Meta**: Critical < 24h, High < 72h, Medium < 7 días.
3. **Conformidad de Ciberseguridad e ISO 27001**:
   * **Métrica**: Cobertura de auditorías internas/externas sin hallazgos mayores de no conformidad.
   * **Meta**: 100% de cumplimiento en recertificaciones.
4. **Eficiencia en el Registro de Tiempos y ALM**:
   * **Métrica**: % de conciliación entre las horas registradas en Oracle ERP y las tareas completadas en Azure DevOps.
   * **Meta**: > 95% de alineación mensual.

---

## 5. Plan de Gestión de Riesgos Tecnológicos

| Riesgo Identificado | Nivel de Impacto | Estrategia de Mitigación |
| :--- | :--- | :--- |
| **Fuga de Código o Datos mediante Herramientas IA** | Alto | Implementar repositorios de IA privados en AWS Bedrock sin reentrenamiento de modelos con datos del cliente; aplicar filtros DLP de correo y endpoint. |
| **Desalineación entre Entornos DEV / QA / PROD** | Medio | Automatizar la infraestructura como código (IaC) y monitorear logs en tiempo real mediante Grafana. |
| **Vulnerabilidades Heredadas en Dependencias de Terceros** | Alto | Automatizar análisis de composición de software (SCA) en Azure DevOps e integrar reportes continuos con Fluid Security. |
| **Rotación de Personal y Silos de Conocimiento** | Medio | Mantener la política de rotación periódica entre células (Cyber, Data, Evolutivo, Correctivo) y documentar arquitecturas en Azure DevOps Wiki. |

---

*Documento preparado como insumo formal para el Plan Estratégico de Tecnologías de Información (PETI) de Perficient.*

