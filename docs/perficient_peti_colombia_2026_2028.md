# Plan Estratégico de Tecnologías de la Información (PETI) 2026-2028

Perficient Inc. — Operación en Colombia

Versión 1.0 — 19 de septiembre de 2026

> Documento académico de Gobierno de TI: un equipo de estudiantes asume el rol del equipo de arquitectura y gobernanza de TI de la operación de Perficient en Colombia. No es un documento oficial de Perficient. Los identificadores entre paréntesis (PUB-, PRV-, INT-) remiten al registro de evidencias del proyecto.

## 1. Introducción

Perficient Inc. es una firma global de consultoría en IA y tecnología, con más de 7.000 asesores, ingenieros y diseñadores (PUB-009). Desde el 2 de octubre de 2024 es una compañía privada, tras su adquisición por EQT (PUB-001, PUB-004), y en marzo de 2026 anunció la evolución de su marca hacia servicios y consultoría "AI-native" (PUB-003). Su modelo de entrega nearshore en Latinoamérica presta servicios de ingeniería a clientes de Norteamérica desde países con husos horarios cercanos, y Colombia es uno de esos países.

Este PETI se centra en la operación colombiana. Allí se ejecutan proyectos de ingeniería de software, seguridad de aplicaciones y analítica para clientes internacionales, y allí se aplica directamente la ley colombiana de protección de datos personales. La operación regional y la global se mencionan solo cuando condicionan las decisiones que se toman en Colombia.

El plan se construyó con la metodología de la Guía MGGTI.GE.ES.03, versión 3.0, del Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC), su plantilla de documento PETI y sus herramientas de construcción, adaptadas a una empresa privada. Los beneficios esperados son tres: mantener sin interrupción la certificación de seguridad que exigen los clientes, poder demostrar cómo se gobierna el uso de la IA, y medir con indicadores la entrega de software y su costo.

## 2. Objetivo y alcance

### 2.1 Objetivo

Formular la estrategia de TI de la operación de Perficient en Colombia para el periodo 2026-2028, alineada con los objetivos corporativos. La estrategia busca cerrar las brechas de gobierno de la inteligencia artificial, seguridad de la información, estandarización de la ingeniería de software y apropiación de herramientas, mediante un portafolio de proyectos priorizado y medible.

### 2.2 Alcance

| Dimensión | Alcance |
|---|---|
| Geográfico | Operación de Perficient en Colombia. La operación LATAM y la global se consideran como contexto |
| Temporal | De octubre de 2026 a septiembre de 2028 (meses 1 a 24), en cuatro fases semestrales. La recertificación ISO/IEC 27001 (P1.1) arranca en septiembre de 2026 (mes 0) |
| Funcional | Células de entrega de ingeniería en Colombia y las herramientas de TI que usan |
| Dominios | Estrategia de TI, gobierno de TI, información, sistemas de información, infraestructura de TI, uso y apropiación, y seguridad de la información |
| Fuera de alcance | Sistemas corporativos globales administrados desde EE. UU. y sistemas propios de los clientes. Se exceptúan los ambientes y pipelines que la operación administra por contrato, cuyos cambios requieren aprobación del cliente |

Las prácticas operativas descritas provienen de una cuenta de cliente analizada (PRV-001) y se presentan como observadas en esa cuenta, no como política general. Por confidencialidad, las herramientas de esa cuenta se nombran por su categoría y no por su nombre comercial.

## 3. Marco normativo

La guía del MinTIC obliga a entidades públicas. Para Perficient es referencia metodológica. Las obligaciones reales de la operación colombiana vienen de la ley de protección de datos y de los compromisos con los clientes.

| Norma o marco | Relación con la operación en Colombia | Aplicación en el PETI |
|---|---|---|
| Ley 1581 de 2012 y Decreto 1377 de 2013 | Obligación legal | Autorización, finalidad, seguridad y transferencias internacionales de datos personales de colaboradores y de clientes; autoridad: Superintendencia de Industria y Comercio |
| Guía MGGTI.GE.ES.03 v3.0, plantilla PETI y herramientas (MinTIC, 2023) | Referencia metodológica | Estructura del documento y actividades |
| MRAE v3.0 y Decreto 767 de 2022 (Política de Gobierno Digital) | Referencia; no obligan a una empresa privada | Dominios de gestión de TI |
| ISO/IEC 27001:2022 | Compromiso certificado de Perficient (PUB-002) | SGSI; recertificación en P1.1 |
| SOC 2 (AICPA) | Informe de atestación que piden los clientes regulados | Informe con controles de IA en P4.1 |
| ISO/IEC 42001:2023 y NIST AI RMF 1.0 | Compromiso propuesto y adopción voluntaria | Sistema de gestión de IA en P1.2 |
| COBIT 2019, TOGAF Standard 10.ª ed., ITIL 4 | Referencias de gobierno, arquitectura y servicios | Diseño del gobierno de TI y mapeo (anexo) |
| Sarbanes-Oxley (SOX) | Antecedente: dejó de aplicar al terminar el registro ante la SEC el 15 de octubre de 2024 (PUB-004) | Obligaciones residuales validadas con Legal en P1.9 |

La operación regional debe cumplir además las leyes de datos de los otros países donde trabaja: Argentina, Ley 25.326 (PUB-012); Chile, Ley 21.719 (PUB-013); México, LFPDPPP de 2025 (PUB-014); y Uruguay, Ley 18.331 (PUB-015). Para este plan importan cuando un proyecto colombiano comparte datos con esos países.

## 4. Metodología

Se siguieron las cuatro fases y las diecisiete actividades de la guía.

| Fase | Actividades | Producto | Ubicación |
|---|---|---|---|
| Planear | 1 a 3 | Equipo, presupuesto de elaboración (equipo académico, sin desembolso) y cronograma | §4, §12 |
| Analizar | 4 a 7 | Contexto, procesos, diagnóstico por dominio, DOFA y tendencias | §5, §6 |
| Construir | 8 a 15 | Estrategia de TI, brechas, portafolio, indicadores y documento | §7 a §10 |
| Socializar | 16 y 17 | Aprobación por el Comité Directivo y plan de comunicaciones | §11, §12 |

Adaptaciones a una empresa privada:

- El Comité Institucional de Gestión y Desempeño se sustituye por un Comité Directivo del PETI, que se constituye con acta antes de la aprobación.
- Trámites, OPA, MIPG y FURAG no aplican.
- La publicación en el sitio web se sustituye por la publicación interna.
- Los costos se expresan en órdenes de magnitud con supuestos explícitos (INT-001).

## 5. Contexto y modelo operativo

### 5.1 Motivadores estratégicos

| Motivador | Fuente | Consecuencia para TI en Colombia |
|---|---|---|
| Evolución de la marca hacia servicios "AI-native" | PUB-003 | Los equipos colombianos usarán IA de forma sistemática; hace falta gobernarla |
| Compañía privada desde octubre de 2024 | PUB-001, PUB-004 | Hay que validar qué obligaciones de control siguen vigentes |
| Recertificación de ISO/IEC 27001:2022 | PUB-002 | La fecha publicada del certificado cae al inicio del plan |
| Alianzas con Microsoft (PUB-005), Databricks (PUB-006, PUB-007), Snowflake (PUB-008), Gradial (PUB-010) y Lovable (PUB-009) | PUB-005 a PUB-010 | Las alianzas exigen personal certificado, también en la operación colombiana |
| Ley 1581 de 2012 | Ley colombiana | Tratamiento de datos personales y transferencias a clientes del exterior |

### 5.2 Objetivos corporativos que el plan apoya

Los formuló el equipo a partir del posicionamiento público (INT-001).

| ID | Objetivo |
|---|---|
| OC01 | Entregar servicios de ingeniería digital e IA a escala de producción |
| OC02 | Mantener la confianza de clientes regulados mediante controles certificados |
| OC03 | Operar con eficiencia y trazabilidad en la entrega nearshore |
| OC04 | Desarrollar y retener talento certificado en Colombia |

### 5.3 Estructura y procesos

En la cuenta analizada cada proyecto tiene un Product Manager (interlocutor con el cliente, justifica licencias), un Line Manager (desarrollo profesional y certificaciones), un Technical Lead (calidad y arquitectura) y desarrolladores senior, intermedios y junior organizados en células especializadas (PRV-001).

| Categoría | ID | Proceso | Soporte de TI | Cubrimiento |
|---|---|---|---|---|
| Estratégico | PE01 | Planeación estratégica y de TI | Ninguno específico | Sin cobertura |
| Misional | PM01 | Entrega de ingeniería de software | Plataforma de gestión del ciclo de vida de aplicaciones (ALM) | Total |
| Misional | PM02 | Gestión de vulnerabilidades | Servicio externo de pruebas de seguridad y plataforma ALM | Parcial |
| Misional | PM03 | Analítica de datos para clientes | Plataformas de datos del proyecto | Parcial |
| Apoyo | PA01 | Talento y certificaciones | Formación en línea | Parcial |
| Apoyo | PA02 | Registro de tiempos | Sistema corporativo de registro de tiempos | Total |
| Apoyo | PA03 | Licencias y herramientas | Justificación del PM ante el cliente | Parcial |
| Evaluación | PV01 | Auditoría y cumplimiento | Ninguno específico | Sin cobertura |

## 6. Situación actual

### 6.1 Diagnóstico por dominio

| Dominio | Situación en la operación colombiana |
|---|---|
| Estrategia de TI | No hay misión, visión, catálogo de servicios ni tablero de indicadores de TI documentados para la operación |
| Gobierno de TI | Los roles están claros y se trabaja con Scrum (PRV-001), pero no hay comité de TI con actas, matriz RACI, matriz de riesgos ni guía de presupuesto de TI |
| Información | Perficient tiene alianzas con Databricks y Snowflake (PUB-006 a PUB-008), pero no hay plataforma de datos unificada ni inventario de los sistemas de IA en uso |
| Sistemas de información | Se usan una plataforma ALM, un servicio externo de pruebas de seguridad, una plataforma de observabilidad y un sistema de registro de tiempos (PRV-001). Los hallazgos de seguridad y la conciliación de horas se pasan a mano entre herramientas |
| Infraestructura | Los ambientes de desarrollo, pruebas y producción están separados y operan en nube pública, en responsabilidad compartida con el cliente (PRV-001). No hay infraestructura como código ni control de costos de nube |
| Uso y apropiación | Hay formación en línea, patrocinio de certificaciones y capacitaciones obligatorias en la cuenta (PRV-001). El canal para pedir licencias de IA no está estandarizado |
| Seguridad | SGSI certificado en ISO/IEC 27001:2022, certificado ISMS-PE-101123 de A-Lign, con fecha publicada "10/11/2026" (PUB-002). Existen lineamientos de uso de IA (PRV-001), pero no un sistema de gestión de IA ni permisos para agentes. No hay evidencia pública del alcance de un informe SOC 2 |

### 6.2 DOFA

| | Contenido (INT-001) |
|---|---|
| Fortalezas | SGSI certificado; roles claros; pruebas de seguridad continuas; programa de certificaciones; talento colombiano integrado a proyectos internacionales |
| Debilidades | Sin gobierno formal de TI ni de IA; flujos manuales entre herramientas; sin infraestructura como código ni control de costos; sin indicadores de TI |
| Oportunidades | Demanda de clientes por IA gobernada; alianzas con Microsoft, Databricks y Snowflake; ISO/IEC 42001 como diferenciador |
| Amenazas | Vencimiento del certificado ISO sin recertificación; fuga de código o datos por herramientas de IA; rotación de personal; incumplimiento de la Ley 1581 en transferencias internacionales |

### 6.3 Tendencias tecnológicas

| Tendencia | Proceso | Uso previsto |
|---|---|---|
| IA generativa y asistentes de código | PM01, PM02 | Acelerar desarrollo y remediación con controles (P1.2 a P1.4) |
| RAG y agentes de IA | PM01, PM03 | Soluciones para clientes con evaluación de calidad (P3.1 a P3.3) |
| DevSecOps e infraestructura como código | PM01, PM02 | Pipelines con pruebas de seguridad y ambientes reproducibles (P2.3, P2.6) |
| Plataformas de datos en la nube y observabilidad | PM01, PM03 | Datos unificados y tableros con objetivos de servicio (P2.5, P3.5) |

## 7. Situación objetivo y estrategia de TI

Todo este numeral es propuesto y depende de la aprobación del Comité Directivo del PETI.

Misión de TI: proveer y gobernar las plataformas, herramientas y controles con los que la operación colombiana entrega software y soluciones de IA a sus clientes, de forma segura, medible y conforme con la ley.

Visión de TI: en septiembre de 2028, la operación de Perficient en Colombia gestionará el uso de la IA con un sistema certificable, entregará software con pipelines y ambientes estandarizados y medirá su desempeño cada trimestre.

| Objetivo de TI | Metas | Año 1 (sep. 2027) | Año 2 (sep. 2028) |
|---|---|---|---|
| OETI01 Gobernar el uso de la IA en la operación colombiana | METI01 Sistemas de IA en el inventario (KPI-08) | 90 % | 100 % |
| | METI02 Células con IA activa y licencia aprobada (KPI-04) | 85 % | 95 % |
| | METI03 Casos de IA en producción con clientes (KPI-03) | 1 | 5 |
| OETI02 Mantener la certificación de seguridad y cumplir la Ley 1581 | METI04 No conformidades mayores ISO/IEC 27001 (KPI-07) | 0 | 0 |
| | METI05 Informe SOC 2 tipo II sin salvedades (KPI-13) | — | Sí |
| | METI06 Remediación de vulnerabilidades críticas (KPI-05) | < 72 h | < 24 h |
| OETI03 Estandarizar la entrega de software, su gobierno y su costo | METI07 Ejecución acumulada del PETI (KPI-01) | 55 % | 95 % |
| | METI08 Sesiones de comité con acta (KPI-14) | 90 % | 90 % |
| | METI09 Conciliación de horas y tareas (KPI-06) | 90 % | 95 % |
| | METI10 Ambientes con infraestructura como código (KPI-11) | 60 % | 100 % |
| | METI11 Variación del costo de nube (KPI-02) | −5 % | −15 % |
| OETI04 Desarrollar las capacidades del talento colombiano en IA, nube y datos | METI12 Personal técnico certificado (KPI-09) | 70 % | 90 % |
| | METI13 Personal rotado entre células (KPI-10) | 50 % | 100 % |

Situación objetivo por dominio:

| Dominio | Estado deseado |
|---|---|
| Estrategia | Misión, visión, catálogo de servicios de TI y tablero de indicadores |
| Gobierno | Comité Directivo (trimestral), Comité Táctico (mensual) y comités por célula (semanal); RACI; matriz de riesgos; guía de presupuesto (COBIT APO06); registro de obligaciones legales |
| Información | Plataforma de datos y catálogo únicos; inventario de sistemas de IA |
| Sistemas de información | Plantillas ALM homologadas; paso automático de hallazgos de seguridad a tickets; pipelines con SAST, DAST y SCA; conciliación automática de horas |
| Infraestructura | Infraestructura como código, observabilidad con objetivos de servicio y control de costos de nube en los ambientes administrados |
| Uso y apropiación | Procedimiento de licencias de IA, plan de certificaciones por rol y currículo de IA para todo el personal |
| Seguridad | ISO/IEC 27001 recertificado; sistema de gestión de IA según ISO/IEC 42001; permisos para agentes; informe SOC 2 con controles de IA; cumplimiento de la Ley 1581 |

## 8. Brechas

Costo estimado (INT-001): bajo, menos de USD 50.000; medio, entre USD 50.000 y 250.000; alto, más de USD 250.000.

| ID | Elemento | Dominio | Acción | Justificación | Tiempo | Costo |
|---|---|---|---|---|---|---|
| BRE-001 | Sistema de gestión de IA | Seguridad | Crear | Hay lineamientos, pero no un sistema de gestión | 6 meses | Medio |
| BRE-002 | Inventario de sistemas de IA | Información | Crear | No hay registro de modelos, proveedores ni datos | 4 meses | Bajo |
| BRE-003 | Integración de hallazgos de seguridad con la ALM | Sistemas de información | Crear | Los hallazgos pasan a mano | 3 meses | Bajo |
| BRE-004 | Plantillas ALM | Sistemas de información | Modificar | Configuraciones distintas entre células | 4 meses | Bajo |
| BRE-005 | Procedimiento de licencias de IA | Uso y apropiación | Modificar | Canal de solicitud no estandarizado | 2 meses | Bajo |
| BRE-006 | Recertificación ISO/IEC 27001 | Seguridad | Modificar | La fecha publicada cae al inicio del plan | 1 a 6 meses | Medio |
| BRE-007 | Infraestructura como código | Infraestructura | Crear | Ambientes sin aprovisionamiento automatizado | 6 meses | Medio |
| BRE-008 | Permisos de agentes de IA | Seguridad | Crear | Sin controles sobre las acciones de los agentes | 3 meses | Medio |
| BRE-009 | Formación en IA | Uso y apropiación | Modificar | Currículo no desplegado a todo el personal | 18 meses | Medio |
| BRE-010 | Plataforma de datos | Información | Crear | Alianzas sin plataforma unificada | 6 meses | Alto |
| BRE-011 | Comités y gobierno de TI | Gobierno | Crear | Sin comités, RACI, matriz de riesgos ni presupuesto de TI | 3 meses | Bajo |
| BRE-012 | Conciliación de tiempos | Sistemas de información | Crear | Conciliación manual | 4 meses | Bajo |
| BRE-013 | Observabilidad y control de costos de nube | Infraestructura | Crear | Sin tableros estándar de monitoreo ni alertas de costo | 3 meses | Bajo |
| BRE-014 | Informe SOC 2 con controles de IA | Seguridad | Modificar | Alcance actual no documentado; no cubre IA | 12 meses | Alto |
| BRE-015 | Estrategia de TI documentada | Estrategia de TI | Crear | Sin misión, visión, catálogo ni tablero de TI | 3 meses | Bajo |
| BRE-016 | Cumplimiento de la Ley 1581 en proyectos | Seguridad | Modificar | Transferencias internacionales de datos sin registro por proyecto | 4 meses | Bajo |

## 9. Hoja de ruta y portafolio de proyectos

Ningún proyecto pasa a ejecución sin patrocinador, caso de negocio, estimación de costo y criterio de aceptación. Los responsables son roles propuestos. La prioridad sigue este orden: primero el riesgo crítico y los plazos externos, después lo que otros proyectos necesitan, luego la estandarización y al final el escalamiento de IA y datos.

| ID | Proyecto | Objetivo | Brecha | Indicador | Responsable | Meses | Costo |
|---|---|---|---|---|---|---|---|
| P1.1 | Recertificación de ISO/IEC 27001:2022 | OETI02 | BRE-006 | KPI-07 | CISO | 0-5 | Medio |
| P1.2 | Sistema de gestión de IA | OETI01 | BRE-001 | KPI-08 | CISO, con CTO | 1-6 | Medio |
| P1.3 | Inventario de sistemas de IA | OETI01 | BRE-002 | KPI-08 | Arquitectura | 1-4 | Bajo |
| P1.4 | Permisos como código para agentes de IA | OETI01 | BRE-008 | KPI-08 | DevSecOps | 4-6 | Medio |
| P1.5 | Capacitación en seguridad, IA y protección de datos | OETI04 | BRE-009 | KPI-09 | Talento humano, con CISO | 1-8 | Bajo |
| P1.6 | Procedimiento de licencias de IA | OETI01 | BRE-005 | KPI-04 | PM y Line Manager, con CTO | 1-3 | Bajo |
| P1.7 | Plan de certificaciones por rol | OETI04 | BRE-009 | KPI-09 | Talento humano, con CTO | 1-5 | Bajo |
| P1.8 | Centro de excelencia de IA en Colombia | OETI01 | BRE-001, BRE-005 | KPI-04 | CTO | 3-6 | Medio |
| P1.9 | Concepto legal y registro de obligaciones (Ley 1581, SOX residual) | OETI02 | BRE-016 | KPI-14 | CTO, con Legal | 1-3 | Bajo |
| P2.1 | Plantillas ALM homologadas | OETI03 | BRE-004 | KPI-01 | Technical Leads | 7-10 | Bajo |
| P2.2 | Integración de pruebas de seguridad con la ALM | OETI02 | BRE-003 | KPI-05 | DevSecOps | 9-11 | Bajo |
| P2.3 | Pipeline de CI/CD estandarizado | OETI02 | BRE-003, BRE-007 | KPI-05 | DevSecOps | 8-12 | Medio |
| P2.4 | Conciliación de tiempos con la ALM | OETI03 | BRE-012 | KPI-06 | Operaciones | 9-12 | Bajo |
| P2.5 | Observabilidad estandarizada | OETI03 | BRE-013 | KPI-01 | SRE | 7-10 | Bajo |
| P2.6 | Infraestructura como código | OETI03 | BRE-007 | KPI-11 | Arquitectura de nube | 7-12 | Medio |
| P2.7 | Tablero de costos de nube | OETI03 | BRE-013 | KPI-02 | FinOps | 7-9 | Bajo |
| P2.8 | Formalización del gobierno y la estrategia de TI | OETI03 | BRE-011, BRE-015 | KPI-14 | CTO | 7-9 | Bajo |
| P3.1 | RAG en producción para clientes | OETI01 | BRE-001 | KPI-03 | CoE de IA | 13-18 | Alto |
| P3.2 | Evaluación automática de modelos de lenguaje | OETI01 | BRE-002 | KPI-08 | CoE de IA | 13-16 | Medio |
| P3.3 | Agente conversacional en producción | OETI01 | BRE-008 | KPI-03 | CoE de IA y PM | 13-18 | Alto |
| P3.4 | Cierre del plan de certificaciones | OETI04 | BRE-009 | KPI-09 | Talento humano | 13-18 | Medio |
| P3.5 | Plataforma y catálogo de datos | OETI03 | BRE-010 | KPI-01 | Arquitectura de datos | 13-18 | Alto |
| P4.1 | Informe SOC 2 tipo II con controles de IA | OETI02 | BRE-014 | KPI-13 | CISO | 13-24 | Alto |
| P4.2 | Auditoría interna del sistema de gestión de IA | OETI01 | BRE-001 | KPI-08 | CISO y CoE de IA | 19-21 | Bajo |
| P4.3 | Balance del PETI y arquitectura 2028-2030 | OETI03 | BRE-015 | KPI-01 | CTO | 21-24 | Bajo |

Fichas de la fase 1:

| Proyecto | ¿Para qué? | ¿Cómo? | Meta |
|---|---|---|---|
| P1.1 | Evitar que caduque la certificación que exigen los clientes | Confirmar con A-Lign la fecha y completar la recertificación antes del 11 de octubre de 2026, la lectura más temprana de la fecha publicada; confirmar el informe SOC 2 vigente; calificar controles con el MSPI | Certificado recertificado, 0 no conformidades mayores |
| P1.2 | Dar reglas formales al uso de IA | Política, roles, evaluación de riesgos y controles según ISO/IEC 42001 y NIST AI RMF | Manual de IA responsable aprobado en el mes 6 |
| P1.3 | Saber qué IA se usa y con qué datos | Levantamiento por célula; registro de modelo, proveedor, datos y responsable | 90 % registrado en el año 1 |
| P1.4 | Limitar lo que un agente de IA puede ejecutar | Piloto sobre el inventario: acciones permitidas y registro de acciones | Aplicado a todos los agentes inventariados |
| P1.5 | Reducir fugas de datos y cumplir la Ley 1581 | Módulos de seguridad y protección de datos (meses 1-5) y de IA (meses 6-8) | 100 % del personal capacitado en el mes 8 |
| P1.6 | Dar acceso ordenado a herramientas de IA | Procedimiento de solicitud, justificación ante el cliente y aprobación | Publicado en el mes 3 |
| P1.7 | Planear la certificación del personal | Currículo por rol (nube, IA, datos), articulado con las alianzas | Plan aprobado en el mes 5 |
| P1.8 | Tener un equipo de referencia en IA en Colombia | Carta de constitución, pruebas de concepto y evaluación de herramientas nuevas | Carta aprobada en el mes 4 |
| P1.9 | Saber qué obligaciones aplican antes de fijar controles | Concepto de Legal sobre Ley 1581 y SOX residual; registro de transferencias internacionales por proyecto | Concepto emitido en el mes 3 |

| Fase | Periodo | Proyectos | Hito | Rango estimado (USD) |
|---|---|---|---|---|
| 1. Gobierno, seguridad y habilitación de IA | Sep. 2026 a mar. 2027 | P1.1 a P1.9 | Recertificación y manual de IA | 200.000 a 1.250.000 |
| 2. Estandarización de la entrega y gobierno | Abr. a sep. 2027 | P2.1 a P2.8 | Pipeline estándar y comités | 100.000 a 800.000 |
| 3. Escalamiento de IA y datos | Oct. 2027 a mar. 2028 | P3.1 a P3.5 | Casos de IA en producción | 850.000 a 3.500.000 |
| 4. Madurez y evaluación | Abr. a sep. 2028 | P4.1 a P4.3 | Informe SOC 2 y balance | 250.000 a 1.100.000 |

Dependencias principales: P1.9 precede a los controles de P1.2; P1.2 y P1.3 preceden a P1.4 y P3.3; P2.1 precede a P2.2 y P2.4; P4.2 precede al informe de P4.1.

## 10. Indicadores

Rangos comunes: bueno, 95 % o más de la meta; intermedio, entre 71 % y 94 %; bajo, 70 % o menos. Las líneas base marcadas "por medir" se toman en el mes indicado.

| ID | Indicador | Fórmula | Línea base | Meta | Frecuencia | Responsable |
|---|---|---|---|---|---|---|
| KPI-01 | Ejecución acumulada del PETI | Proyectos terminados / 25 × 100 | 0 % | 55 % mes 12; 95 % mes 24 | Trimestral | CTO |
| KPI-02 | Variación del costo de nube administrada | (Costo del periodo − costo base) / costo base × 100 | Por medir (P2.7) | −15 % al mes 24 | Trimestral | FinOps |
| KPI-03 | Casos de IA en producción con clientes | Número de casos con métricas | 0 | 5 al mes 24 | Semestral | CoE de IA |
| KPI-04 | Adopción de IA | Células con IA activa y licencia / total de células × 100 | Por medir (mes 3) | 85 % mes 12; 95 % mes 24 | Mensual | CoE de IA |
| KPI-05 | Remediación de vulnerabilidades críticas | Promedio de horas entre detección y cierre | Por medir (mes 3) | < 72 h mes 12; < 24 h mes 24 | Mensual | DevSecOps |
| KPI-06 | Conciliación de horas y tareas | Horas conciliadas / horas registradas × 100 | Por medir (mes 6) | 95 % | Mensual | Operaciones |
| KPI-07 | No conformidades mayores ISO/IEC 27001 | Número por auditoría | Último informe | 0 | Anual | CISO |
| KPI-08 | Cobertura del inventario de IA | Sistemas registrados / identificados × 100 | 0 % | 90 % año 1; 100 % año 2 | Trimestral | Arquitectura |
| KPI-09 | Personal técnico certificado | Personal con más de 6 meses y al menos una certificación / ese personal × 100 | Por medir (mes 3) | 70 % mes 12; 90 % mes 24 | Trimestral | Talento humano |
| KPI-10 | Rotación entre células | Personas rotadas / total × 100 | Por medir (mes 6) | 100 % al mes 24 | Semestral | Line Managers |
| KPI-11 | Ambientes con infraestructura como código | Ambientes con IaC / ambientes administrados × 100 | 0 % | 100 % al mes 24 | Trimestral | Arquitectura de nube |
| KPI-13 | Informe SOC 2 sin salvedades | Informe emitido sin salvedades (sí o no) | Por confirmar (P1.1) | Sí, mes 24 | Anual | CISO |
| KPI-14 | Sesiones de comité con acta | Sesiones con acta / programadas × 100 | 0 % | 90 % | Trimestral | CTO |

KPI-12 no se usa en esta versión; se conserva la numeración para mantener la equivalencia con el PETI regional.

## 11. Riesgos de TI

| ID | Riesgo | Probabilidad | Impacto | Nivel | Tratamiento | Proyecto |
|---|---|---|---|---|---|---|
| R01 | Fuga de código o datos por herramientas de IA | Media | Crítico | Alto | Políticas, permisos como código, capacitación | P1.2, P1.4, P1.5 |
| R02 | Vencimiento del certificado ISO/IEC 27001 sin recertificación | Alta | Crítico | Alto | Recertificación en el mes 0 | P1.1 |
| R03 | Vulnerabilidades heredadas de dependencias | Alta | Alto | Alto | Análisis de composición en el pipeline | P2.2, P2.3 |
| R04 | Sanción por incumplir la Ley 1581 en transferencias de datos | Media | Alto | Medio | Registro de transferencias y capacitación | P1.5, P1.9 |
| R05 | Inyección de instrucciones o sesgos en modelos de IA | Media | Alto | Medio | Evaluación automática y controles NIST AI RMF | P1.2, P3.2 |
| R06 | Rotación de personal y pérdida de conocimiento | Alta | Medio | Medio | Rotación planificada y documentación | P2.1 |
| R07 | Sobrecosto de nube | Media | Medio | Medio | Tablero de costos y ajuste de capacidad | P2.7 |
| R08 | El cliente no autoriza cambios en su infraestructura o herramientas | Media | Alto | Medio | Acuerdo previo; estándares presentados como propuesta | P2.1, P2.6, P2.7 |

## 12. Comunicación y gobierno del PETI

| Actividad | Grupo | Canal | Responsable | Frecuencia |
|---|---|---|---|---|
| Presentación del PETI aprobado | Todo el personal en Colombia | Plataforma de colaboración e intranet | CTO | Una vez (noviembre de 2026) |
| Informe de indicadores y proyectos | Comité Directivo | Sesión del comité | CTO | Trimestral |
| Avance y bloqueos | Líderes de entrega | Comité Táctico y wiki | Líder del Comité Táctico | Mensual |
| Manual de IA y protección de datos | Todo el personal | Correo y capacitación | CISO | En cada versión |
| Resultados de auditorías | Clientes | Reunión con el cliente | CISO | Anual |
| Inducción al PETI | Nuevos ingresos | Módulo de inducción | Talento humano | En cada ingreso |

| Instancia (propuesta) | Integrantes | Frecuencia | Función |
|---|---|---|---|
| Comité Directivo del PETI | CTO, CISO, dirección de operaciones y de entrega | Trimestral | Aprueba el PETI, el presupuesto y el riesgo residual |
| Comité Táctico de TI | Arquitectos, Technical Leads, CoE de IA, DevSecOps | Mensual | Seguimiento de proyectos, indicadores y riesgos |
| Comité por célula | PM, Line Manager y Technical Lead | Semanal | Ejecución |

El Comité Directivo se constituye con acta en octubre de 2026 y aprueba el PETI en esa misma instancia. El plan se revisa cada trimestre y se actualiza al menos una vez al año.

## 13. Glosario

| Término | Definición |
|---|---|
| AIMS | Sistema de gestión de inteligencia artificial, según ISO/IEC 42001 |
| ALM | Gestión del ciclo de vida de aplicaciones |
| Atestación | Informe de un auditor independiente sobre controles, como SOC 2; no es una certificación |
| Brecha | Diferencia entre la situación actual y la objetivo que requiere crear, modificar o eliminar un elemento |
| CI/CD | Integración y entrega continuas |
| DAST, SAST, SCA | Pruebas de seguridad dinámicas, estáticas y de composición de software |
| IaC | Infraestructura como código |
| Nearshore | Prestación de servicios desde países con husos horarios cercanos a los del cliente |
| RAG | Generación aumentada por recuperación |
| SGSI | Sistema de gestión de seguridad de la información |

## 14. Referencias

Congreso de la República de Colombia. (2012). *Ley 1581 de 2012, por la cual se dictan disposiciones generales para la protección de datos personales*.

International Organization for Standardization & International Electrotechnical Commission. (2022). *ISO/IEC 27001:2022 Information security management systems — Requirements*.

International Organization for Standardization & International Electrotechnical Commission. (2023). *ISO/IEC 42001:2023 Artificial intelligence — Management system*.

ISACA. (2018). *COBIT 2019 framework: Governance and management objectives*.

Ministerio de Tecnologías de la Información y las Comunicaciones. (2023). *MGGTI.GE.ES.03 – Guía para la construcción del PETI* (Versión 3.0), plantilla PETI y herramientas para la construcción del PETI.

National Institute of Standards and Technology. (2023). *Artificial intelligence risk management framework (AI RMF 1.0)* (NIST AI 100-1). https://doi.org/10.6028/NIST.AI.100-1

Perficient. (2025, 23 de septiembre). *Perficient recognized as a Microsoft AI Business Solutions Inner Circle partner*. https://blogs.perficient.com/perficient-recognized-as-a-microsoft-ai-business-solutions-inner-circle-partner/

Perficient. (2026, 26 de marzo). *Perficient's evolved brand*. https://www.perficient.com/About/Newsroom/News-Releases/Perficients-Evolved-Brand

Perficient. (2026, 27 de mayo). *Perficient and Lovable partner* [Comunicado, Business Wire]. https://finance.yahoo.com/sectors/technology/articles/frontier-models-business-outcomes-perficient-153000150.html

Perficient. (2026, 9 de septiembre). *Perficient achieves Databricks Brickbuilder specializations*. https://blogs.perficient.com/perficient-achieves-databricks-brickbuilder-specializations/

Perficient. (s. f.). *Customer security statement*. https://www.perficient.com/customer-security

U.S. Securities and Exchange Commission. (s. f.). *Perficient, Inc. (CIK 0001085869): Filings*. https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001085869

## 15. Control de cambios

| Versión | Fecha | Descripción |
|---|---|---|
| 1.0 | 2026-09-19 | Versión enfocada en la operación de Perficient en Colombia, derivada del PETI regional v2.1. Se simplifica a 25 proyectos, 16 brechas y 13 indicadores, y se incorporan la Ley 1581 de 2012 como obligación directa, el riesgo de transferencias internacionales de datos (R04) y el proyecto de registro de obligaciones (P1.9) |

Elaboró: equipo académico del PETI, en el rol de equipo de arquitectura y gobernanza de TI de la operación en Colombia.
Aprobó: Comité Directivo del PETI (pendiente de constitución).
