# Perficient: Ciberseguridad, Certificación ISO 27001:2022 y Evaluaciones SOC 2

## 1. Declaración Oficial de Seguridad e ISMS (ISO 27001:2022)
* **Certificación Internacional**: Perficient mantiene la certificación global **ISO 27001:2022** para su Sistema de Gestión de Seguridad de la Información (ISMS / SGSI) [16, 84, 85].
* **Detalles del Certificado**:
  * **Auditor Independiente**: A-Lign [84, 85].
  * **Número de Certificado**: ISMS-PE-101123 [84, 85].
  * **Vigencia**: Expedido el 10/11/2023, válido hasta el 10/11/2026 [84, 85].
* **Alcance del SGSI**: Valida que los sistemas de información, infraestructura corporativa y datos gestionados u operados por Perficient respetan las mejores prácticas internacionales de confidencialidad, integridad y disponibilidad [16, 84, 85].

---

## 2. Esquema de Ciberseguridad Operativa y Controles Técnicos
Perficient aplica una estrategia de ciberseguridad por capas (*Defense-in-Depth*) que combina controles organizacionales y técnicos [4, 8, 84, 85]:

1. **Seguridad de Red e Infraestructura Hardened**:
   * Implementación de Firewalls de última generación [84, 85].
   * Filtros de Spam y motores de inspección profunda de enlaces en correo electrónico [84, 85].
   * Escaneos continuos de vulnerabilidades y pruebas de penetración (*pentesting*) internas y externas de terceros [48, 84, 85].
2. **Gestión Restringida de Privilegios e Identidades**:
   * Política estricta de contraseñas robustas y autenticación de múltiples factores (**MFA**) [84, 85].
   * Credenciales administrativas restringidas y auditadas bajo el principio de mínimo privilegio [34, 84, 85].
3. **Cifrado y Seguridad de Endpoints**:
   * Cifrado completo de disco (*Full Disk Encryption*) en laptops y dispositivos asignados a los colaboradores [84, 85].
   * Conexiones seguras mediante redes privadas virtuales (**VPN**) para acceso a redes internas [84, 85].
   * Software antimalware con actualización y parcheo automático continuo en el 100% de los endpoints corporativos [84, 85].
4. **Monitoreo Centralizado e Incident Response**:
   * Monitoreo y correlación de registros (*logs*) de firewalls y pasarelas con sistemas de Prevención de Intrusiones (**IPS**) y Detección de Incidentes [11, 28, 84, 85].

---

## 3. Workflow de Ciberseguridad en Proyectos de Desarrollo
En la operación directa de ingeniería y consultoría de Perficient, la ciberseguridad se integra de forma continua dentro del ciclo de vida del software (DevSecOps) [20, 92, 93]:

* **Auditoría Continua con Fluid Security**:
  * Convenio operativo con la plataforma especializada **Fluid Security** para escaneo proactivo de código y pentesting [20, 92].
  * Identificación automática y manual de vulnerabilidades críticas, como inyecciones SQL, fugas de información y fallos de autenticación [20, 92].
* **Clasificación y Triaje de Vulnerabilidades**:
  * Diferenciación estructurada entre **Vulnerabilidades Inyectadas** (errores de desarrollo propio) y **Vulnerabilidades Heredadas** (dependencias o librerías de terceros) [20, 92].
  * Análisis e interpretación por parte de perfiles *Senior* de ciberseguridad dentro del equipo [20, 92].
* **Remediación en Azure DevOps**:
  * Conversión de hallazgos de seguridad en *tickets* de trabajo categorizados en Azure DevOps [20, 93].
  * Asignación directa a desarrolladores Backend/Frontend dentro del Sprint operativo para su remediación y re-verificación [20, 92, 93].

---

## 4. Evaluaciones SOC 2 Type I y Type II
* **Confianza de Terceros (Attestation Report)**: Perficient complementa la norma ISO 27001 con informes **SOC 2** basados en los *Trust Services Criteria* de la AICPA (Seguridad, Disponibilidad, Confidencialidad y Privacidad) [12, 13, 84, 85].
* **Garantía Comercial**: Facilita la verificación del entorno de control por parte de los equipos de compras (*procurement*) y riesgo tecnológico de clientes corporativos e instituciones reguladas (e.g. banca, seguros, salud) [13, 15, 84, 85].

---

## 5. Capacitación Corporativa y Cultura de Seguridad
* **Entrenamiento Anual Obligatorio**: Todo el personal de Perficient realiza módulos obligatorios sobre ciberseguridad personal, protección de privacidad global (GDPR/CCPA) y prevención del acoso/diversidad [25, 96, 97].
* **Uso Seguro y Aceptable de IA**: Lineamientos de gobernanza corporativa para evitar la fuga de código propietario o datos sensibles del cliente al utilizar herramientas de Inteligencia Artificial [25, 97].
