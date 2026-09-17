# PLAN ESTRATÉGICO DE TECNOLOGÍAS DE LA INFORMACIÓN (PETI)
## Perficient Inc. — Operación Nearshore Latinoamérica
### Período 2026-2028 | Versión 1.0

---

## TABLA DE CONTENIDO

1. [Introducción](#1-introducción)
2. [Objetivo](#2-objetivo)
3. [Alcance](#3-alcance)
4. [Abreviaturas y Definiciones](#4-abreviaturas-y-definiciones)
5. [Marco Normativo y de Referencia](#5-marco-normativo-y-de-referencia)
6. [Motivadores y Rupturas Estratégicas](#6-motivadores-y-rupturas-estratégicas)
7. [Contexto Estratégico Organizacional](#7-contexto-estratégico-organizacional)
8. [Modelo Operativo](#8-modelo-operativo)
9. [Situación Actual (AS-IS)](#9-situación-actual-as-is)
10. [Situación Objetivo (TO-BE)](#10-situación-objetivo-to-be)
11. [Identificación de Brechas](#11-identificación-de-brechas)
12. [Identificación de Oportunidades y Necesidades de TI](#12-identificación-de-oportunidades-y-necesidades-de-ti)
13. [Portafolio de Iniciativas, Proyectos y Mapa de Ruta](#13-portafolio-de-iniciativas-proyectos-y-mapa-de-ruta)
14. [Indicadores de Gestión (KPIs y KGIs)](#14-indicadores-de-gestión-kpis-y-kgis)
15. [Plan de Gestión de Riesgos de TI](#15-plan-de-gestión-de-riesgos-de-ti)
16. [Plan de Comunicaciones del PETI](#16-plan-de-comunicaciones-del-peti)
17. [Gobernanza del PETI](#17-gobernanza-del-peti)
18. [Control de Cambios](#18-control-de-cambios)

---

## 1. Introducción

El Plan Estratégico de Tecnologías de la Información (PETI) de **Perficient Inc.** está formulado para el período **2026-2028** y constituye el instrumento de planeación estratégica mediante el cual la organización define la hoja de ruta para la adquisición, desarrollo, soporte, mantenimiento, uso y apropiación de las tecnologías de la información y las comunicaciones, de tal manera que contribuyan a la modernización de los procesos de consultoría digital, al fortalecimiento de las capacidades de ingeniería de software con Inteligencia Artificial, y a la generación de valor para los clientes corporativos de Perficient a nivel global.

El presente PETI se estructura siguiendo las mejores prácticas del **Marco de Referencia de Arquitectura Empresarial (MRAE)** del MinTIC de Colombia, la **Guía para la Construcción del PETI** (MGGTI.GE.ES.03, Versión 3.0), y se articula con los marcos de gobernanza internacionales adoptados por Perficient: **COBIT 2019**, **TOGAF ADM**, **ISO 42001 / NIST AI RMF** e **ITIL 4**.

Este plan surge de la convergencia de tres factores críticos:
1. La evolución de la marca corporativa de Perficient hacia un modelo **AI-Native**, que exige una gobernanza formal del ciclo de vida de la inteligencia artificial.
2. La necesidad de renovar la certificación **ISO 27001:2022** (vigente hasta noviembre de 2026) y mantener la acreditación **SOC 2 Type II**.
3. El imperativo de estandarizar las prácticas de ingeniería de software, observabilidad y gestión del ciclo de vida de aplicaciones (ALM) en la operación Nearshore de Latinoamérica.

---

## 2. Objetivo

Formular la estrategia de Tecnologías de la Información (TI) mediante la cual **Perficient** realiza la alineación de las TI que soportan sus procesos de consultoría, ingeniería digital y servicios al cliente, con su misión, su visión y sus objetivos estratégicos corporativos, para convertirlas en agentes clave de la transformación hacia un modelo **AI-Native** que maximice la generación de valor en los compromisos con clientes enterprise a escala global.

---

## 3. Alcance

El presente PETI aborda las fases propuestas en la guía para la construcción del PETI (comprender, analizar, construir y presentar), con una estructura del documento alineada con los **dominios del modelo de gestión y gobierno de TI**: Estrategia TI, Gobierno TI, Información, Sistemas de Información, Infraestructura de TI, Uso y Apropiación, y Seguridad de la Información.

**Ámbito geográfico:** Operación Nearshore de Perficient en Latinoamérica (Colombia, Argentina, México, Chile, Uruguay) y su articulación con la operación global (sede corporativa: 555 Maryville University Drive, Suite 600, Saint Louis, MO 63141, EE. UU.).

**Ámbito temporal:** 24 meses distribuidos en cuatro fases semestrales (Octubre 2026 – Septiembre 2028).

**Ámbito funcional:** Cubre la totalidad de las células operativas especializadas (Ciberseguridad, Analítica de Datos, Mantenimiento Correctivo, Mantenimiento Evolutivo) y todas las verticales de industria atendidas (BFSI, Salud, Retail, Automotriz, TMT).

---

## 4. Abreviaturas y Definiciones

### 4.1 Abreviaturas

| Abreviatura | Significado |
|:---|:---|
| **AIMS** | AI Management System (Sistema de Gestión de Inteligencia Artificial) |
| **ALM** | Application Lifecycle Management (Gestión del Ciclo de Vida de Aplicaciones) |
| **BFSI** | Banking, Financial Services & Insurance |
| **CI/CD** | Continuous Integration / Continuous Delivery |
| **DAST** | Dynamic Application Security Testing |
| **DLP** | Data Loss Prevention |
| **ERP** | Enterprise Resource Planning |
| **GenAI** | Generative Artificial Intelligence |
| **IaC** | Infrastructure as Code |
| **LLM** | Large Language Model (Modelo Masivo de Lenguaje) |
| **MFA** | Multi-Factor Authentication |
| **MRAE** | Marco de Referencia de Arquitectura Empresarial |
| **MTTR** | Mean Time to Remediation |
| **PM** | Product Manager |
| **RAG** | Retrieval-Augmented Generation |
| **RAGAS** | Retrieval Augmented Generation Assessment Score |
| **SAST** | Static Application Security Testing |
| **SCA** | Software Composition Analysis |
| **SGSI** | Sistema de Gestión de Seguridad de la Información |
| **SRE** | Site Reliability Engineering |
| **TL** | Technical Lead (Líder Técnico) |
| **TMT** | Technology, Media & Telecommunications |

### 4.2 Definiciones

- **Arquitectura Empresarial**: Práctica estratégica que analiza integralmente la organización desde múltiples perspectivas (negocio, datos, aplicaciones, tecnología, seguridad) para diagnosticar su estado actual y establecer la transformación necesaria, generando valor a través de las TI (definición alineada con el MRAE del MinTIC).
- **Célula de Trabajo**: Unidad organizativa multidisciplinaria de Perficient, especializada en un dominio funcional (ciberseguridad, datos, correctivo, evolutivo), que opera bajo metodología Scrum dentro de los compromisos con clientes.
- **Modelo Nearshore**: Modalidad de prestación de servicios de consultoría desde centros de desarrollo en Latinoamérica, con husos horarios afines a Norteamérica, que combina agilidad boutique con escala global.
- **Policy-as-Code**: Implementación de políticas de seguridad y permisos para agentes de IA como código ejecutable, versionable y auditable, en lugar de documentos estáticos.

---

## 5. Marco Normativo y de Referencia

| Marco / Norma | Aplicación al PETI de Perficient |
|:---|:---|
| **ISO 27001:2022** | Certificación del SGSI de Perficient (Certificado ISMS-PE-101123, auditor A-Lign, vigente hasta 10/Nov/2026). Base del esquema de ciberseguridad por capas (Defense-in-Depth). |
| **SOC 2 Type II** (AICPA Trust Services Criteria) | Informe de attestation para verificación del entorno de control por clientes regulados (banca, seguros, salud). Complementa la ISO 27001. |
| **ISO/IEC 42001:2023** | Estándar internacional para el establecimiento de un AI Management System (AIMS). Gobernanza responsable de modelos de IA (Bedrock, Amazon Q, Claude, Kiro). |
| **NIST AI RMF 1.0** | Marco de gestión de riesgos de IA del National Institute of Standards and Technology: funciones Gobernar, Mapear, Medir, Gestionar. |
| **COBIT 2019** | Marco de gobernanza y gestión de TI empresarial. Alineación estratégica TI ↔ negocio, evaluación de riesgos, gestión de valor. |
| **TOGAF ADM** | Metodología de Arquitectura Empresarial. Estructura el PETI en dominios de Negocio, Datos, Aplicaciones, Tecnología y Seguridad. |
| **ITIL 4** | Marco de gestión de servicios de TI. Gestión de incidentes, observabilidad, mejora continua y operaciones DevSecOps. |
| **Sarbanes-Oxley Act (SOX)** §302/§906 | Cumplimiento regulatorio SEC. Certificaciones firmadas por CEO/CFO en los filings anuales Form 10-K (CIK: 0001085869). |
| **Guía MGGTI.GE.ES.03 v3.0** (MinTIC Colombia) | Guía de referencia para la estructura y contenido del PETI, con fases: comprender, analizar, construir y presentar. |
| **MRAE v3.0** (MinTIC Colombia) | Marco de Referencia de Arquitectura Empresarial. Dominios: Estrategia TI, Gobierno TI, Información, Sistemas de Información, Gestión de Servicios TI, Uso y Apropiación. |

---

## 6. Motivadores y Rupturas Estratégicas

### 6.1 Motivadores Estratégicos

| Motivador | Fuente | Aplicación al PETI |
|:---|:---|:---|
| **Evolución AI-Native de la marca** | Comunicado corporativo Perficient 2025 | Transición de experimentación aislada de IA hacia ejecución a escala de producción en la arquitectura empresarial. Pilares: Agentic Front Office, GenAI & RAG, Modernización de Desarrollo. |
| **Microsoft AI Inner Circle 2025-2026** | Reconocimiento Microsoft | Posicionamiento en el 1% superior de socios globales de Microsoft. Obliga a mantener estándares de excelencia en IA y nube. |
| **Databricks Brickbuilder (4 especializaciones)** | Alianza estratégica | Capacidad validada para arquitecturas de datos e IA a escala de producción. Requiere integración formal en el PETI. |
| **IDC MarketScape – Major Player** | 3 evaluaciones IDC | Reconocimiento como actor principal en estrategia, diseño y construcción de experiencias digitales. Demanda sostenimiento de capacidades. |
| **Vencimiento ISO 27001:2022** | Certificado ISMS-PE-101123 (A-Lign) | Vigente hasta 10/Nov/2026. Requiere preparación inmediata de auditoría de renovación. |
| **Brecha de inversión IA vs. madurez** | Thought Leadership Perficient | Investigación que revela desalineación entre presupuestos de IA y la madurez operativa real de las empresas. |

### 6.2 Rupturas Estratégicas

| Ruptura | Descripción | Impacto en el PETI |
|:---|:---|:---|
| **Adopción de agentes autónomos (Agentic AI)** | Los modelos de IA pasan de ser asistentes pasivos a agentes con capacidad de ejecutar acciones sobre sistemas reales. | Requiere gobernanza de permisos (Policy-as-Code), inventario trazable de sistemas IA, y controles de la ISO 42001. |
| **Model Context Protocol (MCP)** | Nuevo estándar de interoperabilidad entre modelos de IA y herramientas/contextos empresariales. | Oportunidad de diferenciación en vertical BFSI. Debe incorporarse al mapa de ruta. |
| **Partnership con Lovable** | Primer socio enterprise para construir aplicaciones AI-Native en días. | Cambia el paradigma de ciclos de desarrollo. Impacta la arquitectura de aplicaciones del TO-BE. |
| **Regulación creciente de IA** | ISO 42001 publicada en 2023; adopción en mercados regulados (salud, banca). | Ventaja competitiva para clientes que requieren cumplimiento demostrable. |

---

## 7. Contexto Estratégico Organizacional

### 7.1 Datos Corporativos

| Atributo | Valor |
|:---|:---|
| **Razón Social** | Perficient, Inc. |
| **Identificador SEC (CIK)** | 0001085869 |
| **EIN** | 74-2853258 |
| **Estado de Incorporación** | Delaware, EE. UU. |
| **Sede Principal** | 555 Maryville University Drive, Suite 600, Saint Louis, MO 63141 |
| **Ticker** | PRFT (NASDAQ) |
| **Clasificación SIC** | 7371 (Services-Computer Programming Services) |

### 7.2 Misión Organizacional

Perficient es una consultora digital global que transforma las marcas, operaciones e infraestructuras tecnológicas de las empresas más grandes del mundo, combinando **agilidad boutique con escala global** para entregar soluciones **AI-First** de ingeniería digital, analítica de datos, transformación cloud y experiencia de cliente.

### 7.3 Visión de TI

Ser reconocida como la firma de consultoría digital líder en la ejecución de **Inteligencia Artificial a escala de producción**, manteniendo los más altos estándares de gobernanza, ciberseguridad y excelencia en ingeniería de software en todas las regiones donde opera.

### 7.4 Objetivos Estratégicos de TI

1. **Liderazgo AI-First**: Consolidar la capacidad de ingeniería digital e inteligencia artificial (Amazon Bedrock, Amazon Q, Claude, Kiro) como motor central del ciclo de vida de desarrollo de software y servicios al cliente.
2. **Excelencia en Gobernanza y Ciberseguridad**: Mantener la conformidad continua con ISO 27001:2022 y SOC 2 Type II, incorporando ISO 42001 y NIST AI RMF.
3. **Eficiencia Operativa e Interoperabilidad Multiambiente**: Optimizar la gestión de proyectos mediante Azure DevOps, observabilidad centralizada en Grafana y segregación estricta de ambientes (DEV, QA, PROD).
4. **Desarrollo de Talento y Escalabilidad Regional**: Fortalecer las capacidades del personal a través de certificaciones oficiales y el modelo Nearshore.

### 7.5 Líneas de Negocio Estratégicas

| Línea | Descripción |
|:---|:---|
| **AI & Data Analytics** | Implementación de soluciones cognitivas, ML, LLMs y gobierno de datos |
| **Digital Engineering** | Desarrollo de software a medida, modernización de legados y arquitecturas cloud-native |
| **Cloud Services** | Migración, arquitectura multicloud (AWS, Azure, GCP) y gestión de infraestructura |
| **Strategy & Experience** | Plataformas de comercio digital, CX y marketing automatizado (Front Office) |

### 7.6 Verticales de Industria

| Vertical | Capacidades Destacadas |
|:---|:---|
| **BFSI** (Banca, Seguros, Finanzas) | Automatización de cierres financieros con IA; MCP en entorno bancario regulado; plataformas de pagos instantáneos |
| **Salud y Ciencias de la Vida** | Optimización de revisiones clínicas con IA; gestión de datos EDC, CTMS y seguridad del paciente |
| **Automotriz e Industrial** | Soluciones de ROI en infraestructura de medición avanzada (AMI) |
| **Retail y Consumo** | E-commerce, integración omnicanal y plataformas de contacto masivo |
| **TMT** (Tecnología, Medios, Telecom) | Modernización de plataformas de contenido, analítica y servicios digitales |

### 7.7 Alianzas Estratégicas

| Alianza | Categoría | Relevancia para el PETI |
|:---|:---|:---|
| **Microsoft AI Inner Circle 2025-2026** | Top 1% global de socios Microsoft | Capacidades Azure, Azure DevOps, AI |
| **Databricks Brickbuilder** (4 especializaciones) | Data & AI at Scale | Arquitectura de Data Lake Enterprise |
| **Snowflake Horizon Catalog** | Data Governance | Gobernanza de metadatos empresariales |
| **AWS** (Bedrock, Q, EC2, S3) | Cloud & AI primario | Infraestructura core + IA Generativa |
| **Gradial** | Agentic Marketing | Automatización de marketing con IA |
| **Lovable** | AI-Native App Development | Primer socio enterprise de Lovable |
| **Oracle** | ERP corporativo | Gestión administrativa y control de tiempos |
| **IDC MarketScape** | Major Player (3 evaluaciones) | Digital Experience & AI |

---

## 8. Modelo Operativo

### 8.1 Estructura Organizacional por Proyecto

```
┌─────────────────────────────────────────────────────────────┐
│                   ESTRUCTURA DE PROYECTO                     │
├─────────────────────────────────────────────────────────────┤
│  Product Manager (PM)                                        │
│  └── Vocero ante el cliente, justifica necesidades           │
│      y aprovisionamiento de recursos y licencias.            │
│                                                              │
│  Line Manager                                                │
│  └── Mentor corporativo, desarrollo profesional,             │
│      aprobaciones administrativas, patrocinio de             │
│      certificaciones.                                        │
│                                                              │
│  Technical Lead (TL)                                         │
│  └── Supervisión de calidad de código,                       │
│      decisiones de arquitectura.                             │
│                                                              │
│  Senior Developers / Specialists                             │
│  └── Liderazgo técnico, vulnerabilidades complejas,          │
│      mentoría a juniors.                                     │
│                                                              │
│  Mid Developers                                              │
│  └── Desarrollo de funcionalidades, atención de              │
│      tickets y mejoras.                                      │
│                                                              │
│  Junior Associates                                           │
│  └── Análisis, remediación y soporte.                        │
└─────────────────────────────────────────────────────────────┘
```

### 8.2 Células de Trabajo Especializadas

| Célula | Función Principal | Herramientas Clave |
|:---|:---|:---|
| **Ciberseguridad y Vulnerabilidades** | Evaluación, triaje y remediación de hallazgos de seguridad (Fluid Security) | Fluid Security, Azure DevOps, IPS/IDS |
| **Analítica de Datos** | Soporte directo a operaciones del cliente con insights basados en datos | Databricks, Snowflake, Grafana, Tableau |
| **Mantenimiento Correctivo** | Resolución de bugs, fixes y correcciones técnicas | Azure DevOps (Boards, Sprints), Grafana |
| **Mantenimiento Evolutivo** | Desarrollo de nuevas funcionalidades (Enhancements) | Azure DevOps, AWS, herramientas IA |

### 8.3 Alineación de TI con los Procesos

| Proceso Organizacional | Sistema / Plataforma TI | Cobertura |
|:---|:---|:---|
| Gestión del Ciclo de Vida ALM | Azure DevOps (Wiki, Boards, Sprints) | Total |
| Registro y Control de Tiempos | Oracle ERP | Total |
| Seguridad de Aplicaciones y Pentesting | Fluid Security + Azure DevOps | Total |
| Observabilidad y Monitoreo de Logs | Grafana (DEV, QA, PROD) | Total |
| Infraestructura y Servicios Cloud | AWS (EC2, S3, SaaS) | Total |
| Comunicación y Colaboración | Microsoft Teams | Total |
| Gobernanza de Herramientas IA | AWS Bedrock / Amazon Q / Kiro / Claude | Parcial |
| Analítica Enterprise | Databricks / Snowflake | Parcial |

### 8.4 Rituales Operativos (Scrum)

- **Daily Scrum**: Reuniones diarias vía Microsoft Teams para sincronización de avances, revisión de tickets y resolución de impedimentos.
- **Sprint Planning**: Planificación de iteraciones por célula en Azure DevOps Boards.
- **Sprint Review**: Demostración de entregables al cliente y retrospectiva del Sprint.
- **Rotación Funcional**: Rotación periódica de desarrolladores entre células para eliminar silos de conocimiento.

---

## 9. Situación Actual (AS-IS)

### 9.1 Estrategia de TI

#### 9.1.1 Lienzo Estratégico (Modelo Canvas de TI)

| Componente | Descripción |
|:---|:---|
| **Socios Clave** | AWS, Microsoft, Databricks, Snowflake, Oracle, Salesforce, Gradial, Lovable |
| **Actividades Clave** | Ingeniería digital AI-First, consultoría Nearshore, DevSecOps, analítica enterprise |
| **Propuesta de Valor** | Agilidad boutique con escala global; soluciones AI-Native que transforman el front office |
| **Relaciones con Clientes** | Integración directa en las dinámicas y equipos de los clientes; coexistencia con otras consultoras |
| **Segmentos de Cliente** | BFSI, Salud, Retail, Automotriz, TMT — empresas Fortune 500 y multinacionales |
| **Recursos Clave** | Talento LATAM certificado; plataformas AWS/Azure; herramientas IA (Bedrock/Q/Kiro/Claude) |
| **Canales** | Microsoft Teams, Azure DevOps, correo corporativo, reuniones presenciales/virtuales |
| **Estructura de Costos** | Nómina de talento, licencias cloud, certificaciones, herramientas de seguridad |
| **Fuentes de Ingresos** | Contratos de consultoría (time & materials), proyectos a precio fijo, servicios gestionados |

### 9.2 Gobierno de TI

**Estado actual:**
- ✅ Se utiliza Azure DevOps como plataforma ALM con Wiki, Boards y Sprints.
- ✅ Existe una estructura clara de roles (PM, Line Manager, TL, Sr, Mid, Jr).
- ✅ Oracle ERP en uso para control de tiempos administrativos.
- ⚠️ No existe un Comité Formal de Gobierno de TI con términos de referencia documentados.
- ⚠️ No se ha implementado una matriz RACI por servicio de TI.
- ⚠️ La guía de gestión del presupuesto y costos de TI no está formalizada.

### 9.3 Información

**Estado actual:**
- ✅ Monitoreo de logs centralizado en Grafana para DEV, QA y PROD.
- ✅ Alianzas formalizadas con Databricks y Snowflake.
- ⚠️ No existe un Data Lake Enterprise unificado operativo.
- ⚠️ No se ha implementado un catálogo de metadatos formal (Snowflake Horizon Catalog en adopción).
- ⚠️ No se cuenta con un inventario trazable de modelos y componentes de IA.

### 9.4 Sistemas de Información

**Estado actual:**
- ✅ Azure DevOps como sistema ALM central (Wiki, Boards, Sprints, trazabilidad de tickets).
- ✅ AWS como proveedor cloud primario (EC2, S3, SaaS).
- ✅ Segregación de ambientes DEV / QA / PROD.
- ✅ Herramientas IA en adopción: Amazon Bedrock, Amazon Q, Kiro, Claude.
- ⚠️ No hay estandarización de plantillas de Azure DevOps entre las diferentes células.
- ⚠️ No se ha automatizado el flujo Fluid Security → Azure DevOps (conversión manual de hallazgos a tickets).
- ⚠️ No existe IaC formal (Terraform/CloudFormation) para provisión de ambientes.

### 9.5 Gestión de Servicios de TI (Infraestructura)

**Estado actual:**
- ✅ Infraestructura administrada bajo modelo de responsabilidad compartida (cliente/proveedor + Perficient).
- ✅ Grafana operativo para monitoreo multiambiente.
- ✅ Firewalls, IPS, MFA, cifrado de disco, VPN, antimalware con parcheo automático.
- ✅ Mesa de servicios interna para soporte técnico.
- ⚠️ No se cuenta con dashboard FinOps para monitoreo de costos cloud.
- ⚠️ Las capacidades de auto-escalamiento no están plenamente implementadas.

### 9.6 Uso y Apropiación de TI

**Estado actual:**
- ✅ Acceso a LinkedIn Learning y cursos internos para todo el personal.
- ✅ Política formal de patrocinio de certificaciones (autorizadas por Line Manager).
- ✅ Capacitaciones obligatorias anuales en ciberseguridad y uso ético de IA.
- ⚠️ La adopción de herramientas IA (Bedrock/Q/Kiro) no es uniforme en todas las células.
- ⚠️ No todas las células cuentan con licencias aprovisionadas de herramientas IA.
- ⚠️ El protocolo de solicitud de licencias IA no está estandarizado como SOP formal.

### 9.7 Seguridad de la Información

**Estado actual:**
- ✅ Certificación ISO 27001:2022 vigente (ISMS-PE-101123, A-Lign, hasta 10/Nov/2026).
- ✅ Acreditación SOC 2 Type II vigente.
- ✅ Cumplimiento SOX (Secciones 302/906) en filings SEC anuales.
- ✅ Estrategia Defense-in-Depth implementada (firewalls, MFA, FDE, VPN, antimalware, IPS).
- ✅ Auditoría continua con Fluid Security (pentesting + SCA).
- ✅ Clasificación de vulnerabilidades: inyectadas vs. heredadas.
- ✅ Entrenamientos obligatorios anuales: ciberseguridad, GDPR/CCPA, uso ético de IA.
- ⚠️ ISO 42001 (AIMS) no implementado — planificado pero sin formalización.
- ⚠️ Policy-as-Code para agentes IA no implementado.
- ⚠️ Inventario trazable de sistemas IA inexistente.

---

## 10. Situación Objetivo (TO-BE)

### 10.1 Arquitectura Enterprise Objetivo (TOGAF ADM)

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                        CAPA 1: ARQUITECTURA DE NEGOCIO                      │
│  ┌──────────────┐ ┌──────────────────┐ ┌──────────────┐ ┌──────────────┐   │
│  │   Nearshore   │ │ Células Ágiles   │ │  Oracle ERP  │ │ Verticales   │   │
│  │   Delivery    │ │ Scrum (4 tipos)  │ │  (Tiempos)   │ │ BFSI/Salud/  │   │
│  │   Model       │ │ PM→TL→Sr→Mid→Jr  │ │  + FinOps    │ │ Retail/TMT   │   │
│  └──────────────┘ └──────────────────┘ └──────────────┘ └──────────────┘   │
├─────────────────────────────────────────────────────────────────────────────┤
│                   CAPA 2: ARQUITECTURA DE INFORMACIÓN Y DATOS               │
│  ┌──────────────┐ ┌──────────────────┐ ┌──────────────┐ ┌──────────────┐   │
│  │  Databricks   │ │  Snowflake       │ │  Grafana     │ │  AI Feature  │   │
│  │  Brickbuilder │ │  Horizon Catalog │ │  Log & Biz   │ │  Store       │   │
│  │  (Data Lake)  │ │  (Governance)    │ │  Telemetry   │ │  (Trazable)  │   │
│  └──────────────┘ └──────────────────┘ └──────────────┘ └──────────────┘   │
├─────────────────────────────────────────────────────────────────────────────┤
│                   CAPA 3: ARQUITECTURA DE APLICACIONES E IA                 │
│  ┌──────────────┐ ┌──────────────────┐ ┌──────────────┐ ┌──────────────┐   │
│  │  Amazon       │ │  Azure DevOps    │ │  CI/CD +     │ │  RAG         │   │
│  │  Bedrock/Q/   │ │  ALM Unificado   │ │  DevSecOps   │ │  Enterprise  │   │
│  │  Kiro/Claude  │ │  (Estandarizado) │ │  + RAGAS     │ │  + MCP       │   │
│  └──────────────┘ └──────────────────┘ └──────────────┘ └──────────────┘   │
├─────────────────────────────────────────────────────────────────────────────┤
│               CAPA 4: ARQUITECTURA DE NUBE E INFRAESTRUCTURA                │
│  ┌──────────────┐ ┌──────────────────┐ ┌──────────────┐ ┌──────────────┐   │
│  │  AWS          │ │  Multi-Cloud     │ │  IaC         │ │  Ambientes   │   │
│  │  EC2/S3/SaaS  │ │  Azure + GCP     │ │  Terraform/  │ │  DEV → QA →  │   │
│  │  (Primario)   │ │  (Secundarios)   │ │  CloudForm.  │ │  PROD (IaC)  │   │
│  └──────────────┘ └──────────────────┘ └──────────────┘ └──────────────┘   │
├─────────────────────────────────────────────────────────────────────────────┤
│              CAPA 5: ARQUITECTURA DE CIBERSEGURIDAD Y SGSI                  │
│  ┌──────────────┐ ┌──────────────────┐ ┌──────────────┐ ┌──────────────┐   │
│  │  ISO 27001    │ │  SOC 2 Type II   │ │  ISO 42001   │ │  Policy-as-  │   │
│  │  :2022        │ │  + SOX           │ │  AIMS + NIST │ │  Code para   │   │
│  │  (Renovado)   │ │  (Ampliado)      │ │  AI RMF      │ │  Agentes IA  │   │
│  └──────────────┘ └──────────────────┘ └──────────────┘ └──────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 10.2 Principios Rectores de la Arquitectura TO-BE

| # | Principio | Descripción |
|:---|:---|:---|
| P1 | **AI-Native by Default** | Toda nueva iniciativa de ingeniería debe considerar la integración de capacidades de IA desde el diseño |
| P2 | **Security-First, Compliance-Always** | Ningún componente se despliega sin validación de seguridad y conformidad normativa |
| P3 | **Observable Everything** | Todo sistema, servicio y modelo de IA debe emitir telemetría trazable y auditable |
| P4 | **Automate the Toil** | Eliminar tareas manuales repetitivas mediante IaC, CI/CD y automatización de flujos de seguridad |
| P5 | **Knowledge Democratization** | Documentar en Azure DevOps Wiki + rotar personal para eliminar silos |
| P6 | **Responsible AI Governance** | Todo uso de modelos de IA debe cumplir ISO 42001 y NIST AI RMF con inventario trazable |

### 10.3 Situación Objetivo por Dominio

#### Estrategia de TI
- Mantener el PETI actualizado trimestralmente con seguimiento a KPIs.
- Establecer un Centro de Excelencia (CoE) de IA con charter formal.
- Estandarizar el protocolo de aprovisionamiento de licencias IA como SOP.

#### Gobierno de TI
- Establecer un Comité Directivo del PETI (trimestral), Comité Táctico de TI (mensual) y Comité Operativo por Célula (semanal).
- Implementar indicadores KGI y KPI formales alineados con COBIT 2019.
- Formalizar la guía de gestión de presupuesto y costos de TI.

#### Información
- Integrar Databricks Brickbuilder como plataforma unificada de Data Lake Enterprise.
- Implementar Snowflake Horizon Catalog para gobernanza de metadatos.
- Crear un AI Feature Store trazable vinculado al Inventario AIMS.

#### Sistemas de Información
- Homologar plantillas de Azure DevOps para todas las células.
- Automatizar el flujo Fluid Security → Azure DevOps (API connector).
- Estandarizar pipelines CI/CD con quality gates de seguridad (SCA + SAST + DAST).
- Implementar IaC (Terraform/CloudFormation) para provisión de ambientes.

#### Gestión de Servicios de TI
- Desplegar Grafana unificado con dashboards estandarizados y alertas automáticas.
- Implementar dashboard FinOps (AWS Cost Explorer + alertas de presupuesto).
- 100% de ambientes provisionados via IaC.

#### Uso y Apropiación
- > 85% de células con IA activa para el Mes 12; > 95% para el Mes 24.
- 100% del personal con ≥ 1 certificación técnica oficial para el Mes 18.
- Rotación funcional del 100% del personal al menos 1 vez en 24 meses.

#### Seguridad de la Información
- ISO 27001:2022 renovado (auditoría de renovación completada).
- AIMS v1.0 implementado bajo ISO 42001 con inventario trazable.
- Policy-as-Code para agentes IA operativo.
- SOC 2 Type II con alcance ampliado (controles de IA incluidos).

---

## 11. Identificación de Brechas

| ID | Nombre | Descripción | Dominio | Acción |
|:---|:---|:---|:---|:---|
| BRE-001 | **Gobernanza de IA no formalizada** | No existe un AIMS (AI Management System) documentado bajo ISO 42001. | Seguridad / Gobierno TI | Crear |
| BRE-002 | **Inventario de sistemas IA inexistente** | No hay registro trazable de modelos, proveedores de IA, orígenes de datos y auditoría. | Información / Gobierno TI | Crear |
| BRE-003 | **Flujo Fluid Security → DevOps manual** | La conversión de hallazgos de seguridad a tickets de Azure DevOps se realiza manualmente. | Sistemas de Información | Crear |
| BRE-004 | **Heterogeneidad en plantillas ALM** | Cada célula opera con configuraciones distintas en Azure DevOps. | Sistemas de Información | Modificar |
| BRE-005 | **Adopción desigual de herramientas IA** | No todos los equipos tienen licencias ni capacitación formal en Bedrock/Q/Kiro. | Uso y Apropiación | Modificar |
| BRE-006 | **ISO 27001 por vencer (Nov 2026)** | Requiere preparación inmediata de auditoría de renovación con A-Lign. | Seguridad de la Información | Mantener |
| BRE-007 | **Ausencia de IaC formal** | No se documenta infraestructura como código para consistencia entre ambientes. | Infraestructura TI | Crear |
| BRE-008 | **Policy-as-Code para agentes IA pendiente** | Controles de permisos de ejecución de herramientas por modelos cognitivos no implementados. | Seguridad / Gobierno TI | Crear |
| BRE-009 | **Capacitación IA no universal** | Currícula de IA adaptada pero no desplegada al 100% del personal. | Uso y Apropiación | Modificar |
| BRE-010 | **Integración Databricks/Snowflake incompleta** | Alianzas firmadas pero sin arquitectura unificada de Data Lake Enterprise. | Información | Crear |
| BRE-011 | **Comité de Gobierno TI no formalizado** | No existe un comité con términos de referencia, agenda ni actas formales. | Gobierno TI | Crear |
| BRE-012 | **Conciliación Oracle ERP ↔ Azure DevOps manual** | No hay dashboard automático de alineación entre horas registradas y tareas completadas. | Gobierno TI / Estrategia TI | Crear |
| BRE-013 | **Monitoreo de costos cloud inexistente (FinOps)** | No se cuenta con dashboard de costos cloud ni alertas de presupuesto. | Infraestructura TI | Crear |

---

## 12. Identificación de Oportunidades y Necesidades de TI

| # | Oportunidad / Necesidad | Descripción | Dominio | Prioridad |
|:---|:---|:---|:---|:---|
| OPT-001 | **Arquitecturas RAG Enterprise** | Desplegar arquitecturas de Generación Aumentada por Recuperación en clientes estratégicos, diferenciando la oferta de Perficient. | Sistemas de Información / IA | Alta |
| OPT-002 | **Framework RAGAS** | Implementar evaluación automatizada de alucinaciones en outputs de LLMs dentro de pipelines CI/CD. | Sistemas de Información | Alta |
| OPT-003 | **Agentic Front Office** | Desplegar agentes conversacionales autónomos en producción con controles ISO 42001. | IA / Estrategia | Alta |
| OPT-004 | **MCP en Banca Regulada** | Implementar Model Context Protocol en proyectos BFSI para reducción medible de retrabajos. | IA / Industria | Media |
| OPT-005 | **Lovable Enterprise** | Aprovechar el partnership para construir aplicaciones AI-Native en ciclos ultrarrápidos. | Sistemas de Información | Media |
| OPT-006 | **Thought Leadership** | Publicar casos de estudio enterprise de implementaciones AI-Native exitosas. | Estrategia | Media |

---

## 13. Portafolio de Iniciativas, Proyectos y Mapa de Ruta

### Fase 1: Gobernanza, SGSI y Habilitación AI-First (Meses 1-6)

| ID | Proyecto | Objetivo | Entregable | Brechas | Responsable |
|:---|:---|:---|:---|:---|:---|
| P1.1 | Renovación ISO 27001:2022 | Preparar y ejecutar auditoría de renovación con A-Lign antes de Nov 2026 | Certificado renovado (3 años) | BRE-006 | CISO |
| P1.2 | Diseño del AIMS (ISO 42001) | Implementar AI Management System formal | Manual de IA Responsable v1.0 | BRE-001 | CISO + CTO |
| P1.3 | Inventario Trazable de Sistemas IA | Crear registro de modelos, proveedores, data lineage | Registro actualizado + proceso de mantenimiento | BRE-002 | Arquitectos |
| P1.4 | Policy-as-Code para Agentes IA | Implementar framework de permisos y barreras de seguridad para LLMs | Framework operativo + documentación | BRE-008 | DevSecOps |
| P1.5 | Entrenamientos Obligatorios IA + Seguridad | Actualizar y desplegar módulos de ciberseguridad y uso ético de IA | 100% del personal certificado (LMS) | BRE-009 | RRHH + CISO |
| P1.6 | Protocolo de Licencias IA | Estandarizar SOP de solicitud y justificación técnica ante clientes | SOP formal publicado | BRE-005 | PM + LM |
| P1.7 | Plan de Certificaciones Técnicas | Definir currícula por rol: AWS, AI, Databricks | Plan aprobado con cronograma | BRE-009 | RRHH + LM |
| P1.8 | Centro de Excelencia (CoE) de IA | Establecer equipo interno de referencia en IA | Charter + primeros POCs | BRE-001, BRE-005 | CTO |

### Fase 2: Estandarización ALM, DevSecOps y Observabilidad (Meses 7-12)

| ID | Proyecto | Objetivo | Entregable | Brechas | Responsable |
|:---|:---|:---|:---|:---|:---|
| P2.1 | Templates Azure DevOps | Homologar plantillas (Wiki, Boards, Sprint) para todas las células | Template Master por tipo de célula | BRE-004 | Tech Leads |
| P2.2 | Conector Fluid Security → DevOps | Automatizar flujo: hallazgo → ticket categorizado (Bug/Fix) | API connector operativo | BRE-003 | DevSecOps |
| P2.3 | Pipeline CI/CD Estandarizado | Crear pipeline template con quality gates obligatorios (SCA+SAST+DAST) | Pipeline template + documentación | BRE-003, BRE-007 | DevSecOps |
| P2.4 | Conciliación Oracle ERP ↔ DevOps | Automatizar dashboard de alineación horas vs. tareas | Dashboard operativo | BRE-012 | BI + Ops |
| P2.5 | Grafana Unificado | Desplegar dashboards estandarizados con alertas y SLOs por ambiente | Dashboards DEV/QA/PROD | — | SRE |
| P2.6 | IaC (Terraform / CloudFormation) | Implementar provisión de ambientes AWS como código | Repositorio IaC versionado | BRE-007 | Cloud Arch. |
| P2.7 | Dashboard FinOps | Configurar monitoreo de costos cloud con alertas de presupuesto | Dashboard operativo | BRE-013 | FinOps |
| P2.8 | Formalización Gobierno TI | Establecer comités con TdR, agendas y actas formales | Comité Directivo + Táctico + Operativo | BRE-011 | CTO |

### Fase 3: Escalamiento AI-Native e Integración Analítica (Meses 13-18)

| ID | Proyecto | Objetivo | Entregable | Brechas | Responsable |
|:---|:---|:---|:---|:---|:---|
| P3.1 | RAG Enterprise (≥ 3 clientes) | Desplegar arquitecturas RAG en producción | Casos de uso GenAI con métricas RAGAS | OPT-001 | CoE IA |
| P3.2 | Framework RAGAS | Implementar evaluación de alucinaciones en CI/CD | Suite de testing automatizado para LLMs | OPT-002 | CoE IA |
| P3.3 | Agentic Front Office | Desplegar agente conversacional en producción con ISO 42001 | Agente operativo + informe de controles | OPT-003 | CoE IA + PM |
| P3.4 | Certificaciones 100% | Completar plan: 100% del personal con ≥ 1 certificación | Registro completo de certificaciones | BRE-009 | RRHH + LM |
| P3.5 | Databricks Data Lake Enterprise | Integrar Databricks Brickbuilder como plataforma unificada | Arquitectura de Data Lake validada | BRE-010 | Data Arch. |
| P3.6 | Snowflake Horizon Catalog | Implementar gobernanza de metadatos con lineage y clasificación | Catálogo operativo con controles de acceso | BRE-010 | Data Gov. |
| P3.7 | AI Feature Store | Crear repositorio de features IA con versionado y auditoría | Feature Store vinculado al AIMS | BRE-002 | CoE IA |

### Fase 4: Madurez Operativa, Auditoría Final y Evolución (Meses 19-24)

| ID | Proyecto | Objetivo | Entregable | Brechas | Responsable |
|:---|:---|:---|:---|:---|:---|
| P4.1 | SOC 2 Type II Ampliado | Auditoría externa con alcance ampliado (incluye IA) | Attestation Report | — | CISO |
| P4.2 | Auditoría Interna ISO 42001 | Medir madurez del AIMS | Informe de madurez con gaps residuales | BRE-001 | CISO + CoE |
| P4.3 | ROI del PETI | Medir retorno de inversión tecnológica del ciclo 2026-2028 | Balance de Gestión del PETI | — | CTO + FinOps |
| P4.4 | Arquitectura TO-BE v2.0 | Actualizar arquitectura objetivo para el ciclo 2028-2030 | Documento aprobado | — | CTO + Arch. |
| P4.5 | MCP en BFSI | Implementar Model Context Protocol en proyecto bancario regulado | Caso de éxito con reducción de retrabajos | OPT-004 | CoE IA |
| P4.6 | Caso de Estudio Enterprise | Publicar thought leadership de implementaciones AI-Native | Publicación en blog/eventos | OPT-006 | Marketing |

### Mapa de Ruta Visual

```
MESES   1  2  3  4  5  6 │ 7  8  9  10 11 12 │ 13 14 15 16 17 18 │ 19 20 21 22 23 24
        ├────────────────┤ ├─────────────────┤ ├──────────────────┤ ├──────────────────┤
FASE 1  ████████████████ │                   │                    │                    │
 P1.1   ██████████████   │                   │                    │                    │
 P1.2   ████████████████ │                   │                    │                    │
 P1.3   ██████████       │                   │                    │                    │
 P1.4         ██████████ │                   │                    │                    │
 P1.5   ██████████████   │                   │                    │                    │
 P1.6   ████████         │                   │                    │                    │
 P1.7   ██████████████   │                   │                    │                    │
 P1.8        ███████████ │                   │                    │                    │
FASE 2                   │ ████████████████  │                    │                    │
 P2.1-P2.8               │ ████████████████  │                    │                    │
FASE 3                   │                   │ █████████████████  │                    │
 P3.1-P3.7               │                   │ █████████████████  │                    │
FASE 4                   │                   │                    │ █████████████████  │
 P4.1-P4.6               │                   │                    │ █████████████████  │
```

---

## 14. Indicadores de Gestión (KPIs y KGIs)

### 14.1 Cuadro de Mando Integral (Balanced Scorecard)

| Perspectiva | ID | Indicador | Meta | Frecuencia |
|:---|:---|:---|:---|:---|
| **Financiera** | KPI-01 | ROI de inversiones tecnológicas del PETI | > 150% al cierre del ciclo | Semestral |
| **Financiera** | KPI-02 | Optimización de costos cloud (FinOps) | Reducción > 15% vs. baseline | Trimestral |
| **Cliente** | KPI-03 | Tasa de renovación de contratos enterprise | > 90% | Anual |
| **Procesos** | KPI-04 | AI-First Rate (células con IA activa) | > 85% (M12), > 95% (M24) | Mensual |
| **Procesos** | KPI-05 | MTTR de vulnerabilidades críticas | < 24h (Critical), < 72h (High), < 7d (Medium) | Mensual |
| **Procesos** | KPI-06 | Conciliación Oracle ERP ↔ Azure DevOps | > 95% de alineación | Mensual |
| **Procesos** | KPI-07 | Conformidad ISO 27001 (no conformidades mayores) | 0 hallazgos mayores | Anual |
| **Procesos** | KPI-08 | Cobertura del Inventario de Sistemas IA | ≥ 90% de modelos registrados | Trimestral |
| **Aprendizaje** | KPI-09 | Personal con ≥ 1 certificación técnica oficial | 100% al Mes 18 | Trimestral |
| **Aprendizaje** | KPI-10 | Rotación funcional entre células | 100% en 24 meses | Semestral |

### 14.2 Tablero de Control de TI

El seguimiento al cumplimiento de los hitos y proyectos del PETI se realizará trimestralmente, tomando como base la medición de los indicadores de cumplimiento de cada proyecto. Se generará un informe ejecutivo para el Comité Directivo del PETI con el estado de avance de cada fase.

---

## 15. Plan de Gestión de Riesgos de TI

| ID | Riesgo | Probabilidad | Impacto | Nivel | Control Primario | Control Secundario |
|:---|:---|:---|:---|:---|:---|:---|
| R01 | Fuga de código/datos vía herramientas IA | Media | Crítico | 🔴 | Repositorios IA privados (Bedrock); filtros DLP | Policy-as-Code; auditoría ISO 42001 |
| R02 | Vencimiento ISO 27001 sin renovación | Baja | Crítico | 🔴 | Inicio preparación en Mes 1; auditoría interna Mes 3 | Plan de contingencia con A-Lign |
| R03 | Vulnerabilidades heredadas (dependencias 3rd party) | Alta | Alto | 🔴 | SCA automatizado en CI/CD; Fluid Security | Política de actualización < 30 días |
| R04 | Prompt injection / sesgos en modelos IA | Media | Alto | 🟡 | NIST AI RMF; testing RAGAS | Red teaming; guardrails Bedrock |
| R05 | Desalineación DEV/QA/PROD | Media | Alto | 🟡 | IaC (Terraform/CFN); Grafana multiambiente | Revisión de paridad en Sprint Review |
| R06 | Rotación de personal y silos de conocimiento | Alta | Medio | 🟡 | Rotación periódica entre células; Wiki DevOps | Knowledge transfer bimensual |
| R07 | Incumplimiento SOX / SEC filings | Baja | Crítico | 🟡 | Certificaciones EX-31/EX-32 por CEO/CFO | Auditoría interna trimestral SOX |
| R08 | Sobrecosto en cloud (AWS/Azure/GCP) | Media | Medio | 🟢 | FinOps dashboard + alertas | Right-sizing trimestral |
| R09 | Brecha de capacitación en IA | Media | Medio | 🟢 | Plan de certificaciones por rol | Mentoría Seniors→Juniors; labs CoE |
| R10 | Interoperabilidad con consultoras coexistentes | Baja | Medio | 🟢 | Herramientas compartidas (Teams) | SLAs de interoperabilidad |

---

## 16. Plan de Comunicaciones del PETI

| Mensaje | Grupo de Interés | Canal | Frecuencia |
|:---|:---|:---|:---|
| Divulgación de hoja de ruta y avances del PETI | Todos los colaboradores Perficient LATAM | Correo corporativo + Microsoft Teams | Trimestral |
| Informe ejecutivo de KPIs y estado de proyectos | Comité Directivo (CTO, CISO, VP Operations) | Presentación en sesión de comité | Trimestral |
| Avances y retos de los proyectos de TI | Tech Leads, Product Managers, Line Managers | Azure DevOps Wiki + Teams | Mensual |
| Lecciones aprendidas y casos de éxito | Todos los colaboradores | Newsletter interno + LinkedIn Learning | Semestral |
| Resultados de auditorías y certificaciones | Clientes enterprise, equipo de procurement | Informe formal + reunión ejecutiva | Anual |
| Actualizaciones del Manual de IA Responsable | Todos los colaboradores | Correo corporativo + sesión de capacitación | Cuando se actualice |
| Onboarding al PETI para nuevos colaboradores | Nuevos ingresos | Módulo de inducción corporativa | En cada ingreso |

---

## 17. Gobernanza del PETI

### 17.1 Estructura de Comités

```
┌─────────────────────────────────────────────────────────────────┐
│                    COMITÉ DIRECTIVO DEL PETI                     │
│         (CTO + CISO + VP Operations + VP Delivery)               │
│    Frecuencia: Trimestral                                        │
│    Función: Decisiones estratégicas, aprobación de presupuesto,  │
│    revisión de KGIs, ajustes al mapa de ruta.                    │
├─────────────────────────────────────────────────────────────────┤
│                    COMITÉ TÁCTICO DE TI                           │
│      (Arquitectos + Tech Leads + CoE IA + DevSecOps Lead)        │
│    Frecuencia: Mensual                                           │
│    Función: Seguimiento de KPIs, gestión de riesgos,             │
│    coordinación entre proyectos, resolución de bloqueos.         │
├─────────────────────────────────────────────────────────────────┤
│                    COMITÉ OPERATIVO POR CÉLULA                   │
│     (PM + Line Manager + Tech Lead de cada célula)               │
│    Frecuencia: Semanal (Sprint Review)                           │
│    Función: Ejecución táctica, seguimiento de sprint,            │
│    imputación de tareas y resolución de impedimentos.            │
└─────────────────────────────────────────────────────────────────┘
```

### 17.2 Marcos de Gobernanza Integrados

| Marco | Aplicación en el PETI | Dominio MRAE |
|:---|:---|:---|
| **COBIT 2019** | Alineación estratégica TI ↔ negocio; evaluación de riesgos; gestión de valor | Gobierno TI |
| **TOGAF ADM** | Arquitectura enterprise en 5 capas (Negocio, Datos, Apps, Infra, Seguridad) | Estrategia TI |
| **ISO 42001 / NIST AI RMF** | Gobernanza del ciclo de vida de IA: Gobernar, Mapear, Medir, Gestionar | Seguridad / Gobierno TI |
| **ITIL 4** | Gestión de servicios, incidentes, observabilidad y mejora continua | Servicios TI |
| **ISO 27001:2022** | SGSI: confidencialidad, integridad y disponibilidad de la información | Seguridad de la Información |
| **SOC 2 / SOX** | Attestation de confianza para clientes regulados + cumplimiento SEC | Seguridad / Gobierno TI |

### 17.3 Mapeo Operativo vs. Estándar Normativo

| Dominio Operativo | Herramienta / Plataforma | Marco Relacionado | Proceso COBIT |
|:---|:---|:---|:---|
| Registro y Control de Tiempos | Oracle ERP / Azure DevOps | COBIT 2019 | APO06 / DSS01 |
| Gestión del Ciclo de Vida ALM | Azure DevOps (Wiki, Boards, Sprints) | ITIL 4 / TOGAF | — |
| Seguridad de Aplicaciones | Fluid Security / Azure DevOps | ISO 27001 (A.8.28/A.8.29) / SOC 2 | — |
| Observabilidad y Monitoreo | Grafana (DEV, QA, PROD) | ITIL 4 / ISO 27001 (A.8.15) | — |
| Infraestructura Cloud | AWS (EC2, S3, SaaS) | TOGAF / COBIT | — |
| Gobernanza de IA | Bedrock / Q / Kiro / Claude | ISO 42001 / NIST AI RMF | — |
| Analítica Enterprise | Databricks / Snowflake | TOGAF Data Architecture | — |

---

## 18. Control de Cambios

| Versión | Fecha | Numerales | Descripción de la Modificación |
|:---|:---|:---|:---|
| 1.0 | Septiembre 2026 | Todos | Versión inicial del PETI 2026-2028 de Perficient. |

---

**Elaboró:** Equipo de Arquitectura y Gobernanza de TI — Perficient LATAM

**Revisó:** CTO / CISO / VP Operations

**Aprobó:** Comité Directivo del PETI

---

*Documento preparado como Plan Estratégico de Tecnologías de la Información (PETI) de Perficient Inc. para el período 2026-2028, alineado con la Guía MGGTI.GE.ES.03 v3.0 del MinTIC, el Marco de Referencia de Arquitectura Empresarial (MRAE), y los marcos de gobernanza internacionales COBIT 2019, TOGAF ADM, ISO 42001, ITIL 4 e ISO 27001:2022.*

