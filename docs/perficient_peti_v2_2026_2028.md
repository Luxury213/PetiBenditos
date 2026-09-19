# Plan Estratégico de Tecnologías de la Información (PETI) 2026-2028

Perficient Inc. — Operación nearshore de Latinoamérica

Versión 2.1 — 19 de septiembre de 2026 — borrador sujeto a validación

> Clasificación: interno. Documento académico de Gobierno de TI: un equipo de estudiantes asume el rol del equipo de arquitectura y gobernanza de TI de la operación LATAM; no es un documento oficial de Perficient. Antes de cualquier publicación externa se aplica el registro de evidencias (`docs/registro-de-evidencias.md`) y se revisa la reidentificación. Las marcas [EVIDENCIA: …] señalan afirmaciones que aún no tienen fuente registrada.

## 1. Introducción

Perficient Inc. se describe en su comunicación pública de 2026 como una firma global de consultoría en IA y tecnología, con más de 7.000 asesores, ingenieros y diseñadores (PUB-009), y cuenta con centros de entrega nearshore en Latinoamérica [EVIDENCIA: página oficial de entrega nearshore]. Desde el 2 de octubre de 2024 es una compañía privada tras su adquisición por EQT (PUB-001, PUB-004), y en marzo de 2026 anunció la evolución de su marca hacia servicios y consultoría "AI-native" (PUB-003). Ese cambio de posicionamiento trae una consecuencia directa para TI: los equipos que entregan proyectos con herramientas de inteligencia artificial necesitan un sistema de gestión, un inventario y controles que no se encontraron en la evidencia revisada (INT-001).

Este documento formula el Plan Estratégico de Tecnologías de la Información (PETI) de la operación LATAM para el periodo octubre de 2026 a septiembre de 2028. Se construyó con la metodología de la Guía MGGTI.GE.ES.03, versión 3.0, del Ministerio de Tecnologías de la Información y las Comunicaciones de Colombia (MinTIC), su plantilla de documento PETI y sus herramientas de construcción, adaptadas a una empresa privada según lo que la propia guía permite (§2.2).

El plan resume la situación actual de la gestión de TI por dominio, la situación objetivo, las brechas entre ambas, el portafolio de proyectos y su hoja de ruta, los indicadores, los riesgos y la forma en que el plan se comunica y se gobierna. Los beneficios esperados son tres: mantener sin interrupción la certificación de seguridad que exigen los clientes, poder demostrar ante ellos cómo se gobierna el uso de la IA, y medir con indicadores la entrega de software y el costo de la operación.

## 2. Objetivo y alcance

### 2.1 Objetivo

Formular la estrategia de TI de la operación LATAM de Perficient para el periodo 2026-2028, alineada con los objetivos corporativos, que cierre las brechas de gobierno de la inteligencia artificial, seguridad de la información, estandarización de la ingeniería de software y apropiación de herramientas identificadas en el diagnóstico, mediante un portafolio de proyectos priorizado y medible.

### 2.2 Alcance

El PETI recorre las cuatro fases de la guía (planear, analizar, construir y socializar) y organiza el diagnóstico y la situación objetivo según los siete dominios del modelo de gestión y gobierno de TI: estrategia de TI, gobierno de TI, información, sistemas de información, infraestructura de TI, uso y apropiación, y seguridad de la información.

| Dimensión | Alcance |
|---|---|
| Geográfico | Operación nearshore de Perficient en Latinoamérica y su relación con la operación global [EVIDENCIA: países de la operación LATAM según fuente oficial] |
| Temporal | De octubre de 2026 a septiembre de 2028 (meses 1 a 24), en cuatro fases semestrales. P1.1 se ejecuta desde septiembre de 2026 (mes 0) como proyecto en curso, antes de la aprobación del plan |
| Funcional | Células de entrega de ingeniería de la operación LATAM y las herramientas de TI que usan. La tipología de células observada en la cuenta analizada (PRV-001) se usa como referencia, no como estructura corporativa |
| Fuera de alcance | Sistemas corporativos globales administrados desde EE. UU., salvo en su interacción con la operación LATAM; sistemas propios de los clientes, salvo los ambientes, pipelines y cuentas de nube que la operación LATAM administra por contrato, cuyos cambios requieren aprobación del cliente (R11) |

### 2.3 Alcance de la evidencia

La evidencia pública sostiene el contexto corporativo. La evidencia restringida disponible describe una cuenta de cliente y un equipo de entrega anonimizados (PRV-001, PRV-002). Por tanto, las prácticas observadas en esa cuenta se presentan como "observadas en la cuenta analizada" y no como política de Perficient ni como situación comprobada de toda la región. Por confidencialidad, las herramientas de la cuenta analizada se nombran por su categoría (plataforma de gestión del ciclo de vida de aplicaciones, servicio externo de pruebas de seguridad, plataforma de observabilidad, nube pública, servicios de IA generativa) y no por su nombre comercial. Las afirmaciones de ausencia ("no se encontró") se refieren a la evidencia revisada (INT-001).

## 3. Marco normativo

La guía del MinTIC y las normas colombianas de gobierno digital obligan a entidades públicas. Para Perficient son referencia metodológica; las obligaciones reales vienen de las leyes de protección de datos de los países donde opera y de los compromisos que la compañía asume con sus clientes.

| Norma o marco | Relación con Perficient | Aplicación en el PETI |
|---|---|---|
| Guía MGGTI.GE.ES.03 v3.0 (MinTIC, 2023), plantilla PETI y herramientas | Referencia metodológica | Estructura del documento y actividades de construcción |
| Marco de Referencia de Arquitectura Empresarial (MRAE) v3.0 | Referencia metodológica | Dominios de gestión de TI usados en el diagnóstico |
| Decreto 767 de 2022 (Política de Gobierno Digital) | No obliga a Perficient | Contexto de la metodología |
| Colombia: Ley 1581 de 2012 y Decreto 1377 de 2013 | Obligación legal | Tratamiento de datos personales de colaboradores y clientes |
| Argentina: Ley 25.326 de 2000 (PUB-012) | Obligación legal, si la operación incluye Argentina | Ídem |
| Chile: Ley 19.628, reformada por la Ley 21.719 de 2024, con entrada en vigencia prevista para el 1 de diciembre de 2026 [EVIDENCIA: texto en BCN]; el Gobierno propuso aplazarla al 1 de diciembre de 2027 (PUB-013) | Obligación legal, si la operación incluye Chile | El plan asume la fecha más temprana |
| México: nueva Ley Federal de Protección de Datos Personales en Posesión de los Particulares, publicada el 20 de marzo de 2025 (PUB-014) | Obligación legal, si la operación incluye México | Autoridad: Secretaría Anticorrupción y Buen Gobierno |
| Uruguay: Ley 18.331 de 2008 y sus modificaciones (PUB-015) | Obligación legal, si la operación incluye Uruguay | Incluye reglas sobre decisiones automatizadas (Ley 20.075) |
| ISO/IEC 27001:2022 | Compromiso voluntario certificado (PUB-002) | Sistema de gestión de seguridad de la información (SGSI); recertificación en P1.1 |
| SOC 2 (AICPA) | Posible compromiso con clientes; existencia, alcance y vigencia por validar (BRE-015) | Informe de atestación con controles de IA en P4.1 |
| ISO/IEC 42001:2023 | Compromiso propuesto | Sistema de gestión de IA (AIMS) en P1.2 |
| NIST AI RMF 1.0 (2023) | Adopción voluntaria | Funciones gobernar, mapear, medir y gestionar en el AIMS |
| COBIT 2019 | Referencia de gobierno de TI | Diseño del gobierno de TI y mapeo de procesos (anexo B) |
| TOGAF Standard, 10.ª edición | Referencia de arquitectura | Vistas de negocio, datos, aplicaciones y tecnología de §7 |
| ITIL 4 | Referencia de gestión de servicios | Incidentes, cambios, niveles de servicio y monitoreo |
| Sarbanes-Oxley (SOX) §302 y §906 | Antecedente: aplicaba mientras Perficient cotizaba en NASDAQ. Tras la adquisición presentó el Form 15-12G el 15 de octubre de 2024 y no registra presentaciones posteriores ante la SEC (PUB-004) | Obligaciones residuales por validar con Legal y Finanzas (P1.9, R07) |

## 4. Metodología

El PETI se construyó siguiendo las cuatro fases y las diecisiete actividades de la Guía MGGTI.GE.ES.03.

| Fase | Actividad | Producto | Ubicación |
|---|---|---|---|
| Planear | 1. Equipo y partes interesadas | Equipo y partes interesadas por rol | §13.1 |
| | 2. Presupuesto para elaborar el PETI | Elaboración con el equipo académico, sin desembolso ni consultoría externa | Este numeral |
| | 3. Plan y cronograma de trabajo | Cronograma de construcción | Este numeral |
| Analizar | 4. Entorno organizacional | Contexto, procesos, alineación de TI con procesos | §5 |
| | 5. Planes externos y compromisos | Compromisos con plazo | §5.1 |
| | 6. Diagnóstico de la gestión de TI | Situación actual por dominio y DOFA | §6 |
| | 7. Tendencias tecnológicas | Matriz de tendencias frente a procesos | §6.9 |
| Construir | 8. Estrategia de TI | Misión, visión, objetivos, metas y capacidades de TI | §7.1 |
| | 9 y 10. Mejoras y oportunidades por dominio | Situación objetivo y oportunidades | §7, §8.2 |
| | 11. Brechas | Catálogo de brechas | §8.1 |
| | 12. Otros planes | Iniciativas de otros planes | §8.3 |
| | 13. Portafolio y hoja de ruta | Catálogo de proyectos, fichas, presupuesto y mapa de ruta | §9 |
| | 14. Indicadores | Hojas de vida de los indicadores | §10 |
| | 15. Documento PETI | Este documento | — |
| Socializar | 16. Aprobación y publicación | Aprobación por el Comité Directivo del PETI | §13.3 |
| | 17. Socialización | Plan de comunicaciones | §12 |

Adaptaciones a una empresa privada:

- El Comité Institucional de Gestión y Desempeño que prevé la guía se sustituye por el Comité Directivo del PETI, que se propone constituir con acta en octubre de 2026 como condición previa a la aprobación (§13.3).
- Trámites, otros procedimientos administrativos (OPA), SUIT, FURAG y MIPG no aplican. En su lugar se caracterizan las líneas de servicio que Perficient presta a sus clientes.
- La publicación en el sitio web oficial se sustituye por la publicación interna del documento aprobado.
- No hay SECOP ni presupuesto aprobado disponible. Los costos se expresan en órdenes de magnitud con supuestos explícitos (§8.1, INT-001).

Fuentes: documentos públicos registrados con ID `PUB-`; entrevistas y documentación anonimizada de una cuenta de cliente (`PRV-`, de uso restringido); y análisis del equipo (`INT-`).

Cronograma de construcción del PETI (actividad 3):

| Fase | Actividades | Periodo | Responsable | Salida |
|---|---|---|---|---|
| Planear | 1 a 3 | Agosto de 2026 | Líder del equipo PETI | Equipo, cronograma |
| Analizar | 4 a 7 | Agosto y septiembre de 2026 | Analistas de dominio | §5 y §6 |
| Construir | 8 a 15 | Septiembre de 2026 | Líder del equipo PETI y analistas | §7 a §11 |
| Socializar | 16 y 17 | Octubre y noviembre de 2026 | Líder del equipo PETI | Acta de aprobación; plan de comunicaciones |

## 5. Contexto y modelo operativo

### 5.1 Motivadores estratégicos

| Motivador | Fuente | Consecuencia para TI |
|---|---|---|
| Evolución de la marca hacia servicios "AI-native" | PUB-003 | Los equipos de entrega usarán IA de forma sistemática; hace falta gobernarla |
| Condición de compañía privada desde octubre de 2024 | PUB-001, PUB-004 | Cambian las obligaciones de reporte y control; deben validarse antes de fijar controles (P1.9) |
| Recertificación de ISO/IEC 27001:2022 | PUB-002 | La fecha publicada cae al inicio del plan; es la ruta crítica de la fase 1 |
| Alianzas: Microsoft AI Business Solutions Inner Circle 2025-2026 (PUB-005); cuatro especializaciones Brickbuilder de producto y al menos una de industria de Databricks (PUB-006, PUB-007); Snowflake Premier Partner desde junio de 2025 (PUB-008); alianza de co-innovación con Gradial (PUB-010); anuncio de Perficient como primer socio de implementación enterprise de Lovable (PUB-009) | PUB-005 a PUB-010 | Mantener las alianzas exige personal certificado y plataformas de datos e IA en uso real |
| Reconocimiento como Major Player en tres evaluaciones IDC MarketScape de experiencia del cliente de 2025 | PUB-011 | Refuerza la demanda de capacidades de IA en experiencia del cliente |

Compromisos con plazo (actividad 5):

| Compromiso | Obligación de TI | Plazo |
|---|---|---|
| Recertificación ISO/IEC 27001:2022 | Auditoría de recertificación completada | Fecha publicada como "10/11/2026" (PUB-002); el plan asume la lectura más temprana, 2026-10-11 |
| Informe SOC 2 | Confirmar existencia, periodo y alcance | [EVIDENCIA]; confirmación en los meses 1 y 2 (P1.1) |
| Ley 21.719 de Chile, si aplica | Adecuar el tratamiento de datos | 2026-12-01, o 2027-12-01 si se aprueba el aplazamiento (PUB-013) |
| Certificaciones exigidas por los socios | Personal certificado | [EVIDENCIA: requisitos de cada programa de socios] |

Rupturas estratégicas:

| Ruptura | Efecto en el plan |
|---|---|
| Agentes de IA que ejecutan acciones sobre sistemas reales | Permisos como código y registro de acciones (P1.4) |
| Protocolos de integración entre modelos y herramientas, como Model Context Protocol (MCP) | Oportunidad para proyectos regulados, con controles (OPT-004) |
| Herramientas de construcción rápida de aplicaciones con IA | Cambian los tiempos de desarrollo; exigen reglas de calidad y seguridad (OPT-005) |
| Normas de gestión de IA (ISO/IEC 42001, NIST AI RMF) | Los clientes empiezan a pedir evidencia de gestión responsable de la IA |

### 5.2 Contexto institucional

Descripción corporativa: "firma global de consultoría en IA y tecnología" (PUB-009). La misión, la visión y las metas corporativas con medición actual no se localizaron en fuentes abiertas [EVIDENCIA: página oficial "About" y reportes corporativos].

Objetivos corporativos que el PETI apoya (formulados por el equipo; por validar con la dirección):

| ID | Objetivo corporativo | Fuente |
|---|---|---|
| OC01 | Entregar servicios de ingeniería digital e IA a escala de producción | INT-001 (contexto: PUB-003) |
| OC02 | Mantener la confianza de clientes regulados mediante controles certificados | INT-001 (contexto: PUB-002) |
| OC03 | Operar con eficiencia y trazabilidad en la entrega nearshore | INT-001 |
| OC04 | Desarrollar y retener talento certificado en la región | INT-001 |

### 5.3 Estructura organizacional

La compañía no publica un organigrama ni el tamaño de la operación LATAM [EVIDENCIA]. En la cuenta analizada se observó la siguiente estructura por proyecto, con células especializadas (PRV-001):

| Rol | Responsabilidad observada |
|---|---|
| Product Manager (PM) | Interlocutor con el cliente; justifica necesidades de recursos y licencias |
| Line Manager | Desarrollo profesional, aprobaciones administrativas, patrocinio de certificaciones |
| Technical Lead (TL) | Calidad del código y decisiones de arquitectura |
| Desarrolladores senior, intermedios y junior | Remediación de vulnerabilidades complejas y mentoría; desarrollo de funcionalidades; análisis y soporte |

### 5.4 Modelo operativo

#### 5.4.1 Procesos

Mapa de procesos propuesto para la operación LATAM, construido a partir de lo observado en la cuenta analizada (PRV-001) y por validar con la dirección de operaciones (INT-001):

| Categoría | ID | Proceso | Objetivo |
|---|---|---|---|
| Estratégico | PE01 | Planeación estratégica y de TI | Alinear la operación y la TI con los objetivos corporativos |
| Estratégico | PE02 | Gestión de alianzas tecnológicas | Mantener las capacidades exigidas por los socios |
| Misional | PM01 | Entrega de ingeniería de software (evolutivo y correctivo) | Construir y mantener soluciones para clientes |
| Misional | PM02 | Gestión de vulnerabilidades de aplicaciones | Detectar, clasificar y remediar vulnerabilidades |
| Misional | PM03 | Analítica de datos para clientes | Entregar información para la operación del cliente |
| Apoyo | PA01 | Gestión del talento y certificaciones | Formar y certificar al personal |
| Apoyo | PA02 | Registro de tiempos y gestión administrativa | Controlar horas y costos por proyecto |
| Apoyo | PA03 | Gestión de licencias y herramientas | Aprovisionar herramientas, incluidas las de IA |
| Evaluación | PV01 | Auditoría y cumplimiento | Mantener certificaciones y atestaciones |

#### 5.4.2 Alineación de TI con los procesos

Valoración del cubrimiento: INT-001.

| Proceso | Sistema o plataforma | Cubrimiento | Oportunidad de mejora con TI |
|---|---|---|---|
| PE01 Planeación | Sin herramienta específica | Sin cobertura | Tablero de indicadores de TI (BRE-018) |
| PE02 Alianzas | Portales de los socios [EVIDENCIA] | Parcial | Registro de certificaciones por socio (P1.7) |
| PM01 Entrega de ingeniería | Plataforma de gestión del ciclo de vida de aplicaciones (ALM) del proyecto (PRV-001) | Total | Plantillas homogéneas (BRE-004) |
| PM02 Vulnerabilidades | Servicio externo de pruebas de seguridad continuas y plataforma ALM (PRV-001) | Parcial | Paso automático de hallazgos a tickets (BRE-003) |
| PM03 Analítica | [EVIDENCIA: plataformas usadas en proyectos LATAM] | Parcial | Plataforma de datos unificada (BRE-010) |
| PA01 Talento | Plataforma de formación en línea (PRV-001) | Parcial | Registro de certificaciones (P1.7) |
| PA02 Tiempos | Sistema corporativo de registro de tiempos (PRV-001) | Total | Conciliación automática con la plataforma ALM (BRE-012) |
| PA03 Licencias | Justificación del PM ante el cliente (PRV-001); canal no estandarizado | Parcial | Procedimiento estándar (BRE-005) |
| PV01 Auditoría | Sin herramienta específica | Sin cobertura | Evidencias de control centralizadas (P1.1, P4.1) |
| Monitoreo de aplicaciones | Plataforma de observabilidad por ambiente (PRV-001) | Total | Tableros y objetivos de servicio estandarizados (BRE-014) |
| Colaboración | Plataforma de colaboración (PRV-001) | Total | — |
| Uso de IA | Servicios de IA generativa y asistentes de código en uso o en evaluación (PRV-001) | Parcial | Sistema de gestión e inventario (BRE-001, BRE-002) |

#### 5.4.3 Servicios de negocio

Los servicios que Perficient presta a sus clientes se agrupan en líneas de IA y datos, ingeniería digital, nube, y estrategia y experiencia [EVIDENCIA: página oficial de servicios]. Los trámites y OPA de la plantilla no aplican a una empresa privada.

## 6. Situación actual

Criterio de lectura: cada afirmación lleva su evidencia. Lo observado en la cuenta analizada (PRV-001) describe esa cuenta, no toda la operación; las ausencias se refieren a la evidencia revisada (INT-001).

### 6.1 Estrategia de TI

#### 6.1.1 Lienzo estratégico de TI

| Componente | Descripción |
|---|---|
| Segmentos de clientes | Grandes empresas de varias industrias, entre ellas servicios financieros y salud [EVIDENCIA: página de industrias] |
| Propuesta de valor | Entrega nearshore de ingeniería digital y soluciones con IA (PUB-003) |
| Canales | Equipos integrados en el cliente; plataforma ALM, plataforma de colaboración y correo (PRV-001) |
| Relación con clientes | Integración en los equipos del cliente (PRV-001) |
| Fuentes de ingreso | Contratos de consultoría y servicios [EVIDENCIA: modalidades de contratación] |
| Recursos clave | Personal certificado, plataformas de nube y herramientas de IA |
| Actividades clave | Desarrollo, mantenimiento, seguridad de aplicaciones y analítica |
| Socios clave | Microsoft, Databricks, Snowflake, Gradial, Lovable (PUB-005 a PUB-010); AWS [EVIDENCIA] |
| Estructura de costos | Nómina, licencias de nube y de IA, certificaciones, herramientas de seguridad |

#### 6.1.2 Misión, visión y servicios de TI

No se encontró una misión ni una visión de TI documentadas para la operación LATAM, ni un catálogo formal de servicios de TI internos (INT-001; BRE-016). En la cuenta analizada se prestan de hecho servicios de gestión del ciclo de vida de aplicaciones, monitoreo y pruebas de seguridad (PRV-001).

#### 6.1.3 Indicadores de TI

No se encontró un tablero de indicadores de la estrategia de TI (INT-001; BRE-018). Los indicadores del §10 parten sin línea base, que se mide en los primeros meses del plan.

#### 6.1.4 Capacidades de TI

| Capacidad | Estado actual | Evidencia | Estado objetivo (mes 24) |
|---|---|---|---|
| Gestión del ciclo de vida de aplicaciones | Existe | PRV-001 | Estandarizada entre células (P2.1) |
| Seguridad de aplicaciones | Parcial | PRV-001 | Integrada al pipeline (P2.2, P2.3) |
| Observabilidad | Parcial | PRV-001 | Con objetivos de servicio (P2.5) |
| Gestión de la IA | No encontrada | INT-001 | Sistema de gestión auditado (P1.2, P4.2) |
| Gestión de datos | No encontrada | INT-001 | Plataforma y catálogo (P3.5, P3.6) |
| Gestión financiera de TI | No encontrada | INT-001 | Presupuesto y costos de nube controlados (P2.7, P2.8) |
| Gestión del talento de TI | Parcial | PRV-001 | Plan de certificaciones cumplido (P1.7, P3.4) |

### 6.2 Gobierno de TI

- En la cuenta analizada se usa una plataforma ALM para la gestión de proyectos y un sistema corporativo de registro de tiempos, y los roles están definidos (PRV-001).
- En la evidencia revisada no se encontró un comité de gobierno de TI con términos de referencia y actas, ni una matriz RACI, ni una matriz de riesgos de TI, ni una guía de presupuesto y costos de TI para la operación LATAM (INT-001; BRE-011, BRE-017).
- En la cuenta analizada los proyectos se gestionan con Scrum y hay rotación periódica entre células (PRV-001).

### 6.3 Información

- En la cuenta analizada los registros de las aplicaciones se centralizan en una plataforma de observabilidad por ambiente (PRV-001).
- Perficient tiene alianzas con Databricks y Snowflake (PUB-006 a PUB-008), pero no se encontró evidencia de una plataforma de datos unificada ni de un catálogo de metadatos en operación para LATAM (INT-001; BRE-010).
- No se encontró un inventario de modelos, proveedores y datos usados por sistemas de IA (INT-001; BRE-002).

### 6.4 Sistemas de información

| Sistema (categoría) | Uso observado en la cuenta analizada | Estado | Evidencia |
|---|---|---|---|
| Plataforma ALM | Tableros, sprints, wiki, tickets | En uso; homogeneidad de plantillas por verificar | PRV-001; INT-001 |
| Sistema corporativo de registro de tiempos | Registro de horas | En uso; sin conciliación automática con la plataforma ALM | PRV-001 |
| Servicio externo de pruebas de seguridad continuas | Pruebas de penetración y análisis de composición de software | En uso; hallazgos pasados a mano a la plataforma ALM | PRV-001 |
| Plataforma de observabilidad | Monitoreo de registros por ambiente | En uso; estandarización de tableros por verificar | PRV-001; INT-001 |
| Servicios de IA generativa y asistentes de código | Asistencia al desarrollo | En uso o en evaluación | PRV-001 |
| Plataforma de colaboración | Comunicación | En uso | PRV-001 |

Los ambientes de desarrollo, pruebas y producción están separados (PRV-001); no se encontró evidencia de aprovisionamiento con infraestructura como código (INT-001; BRE-007).

Mapa de integraciones:

| Origen | Destino | Mecanismo actual | Mecanismo objetivo |
|---|---|---|---|
| Servicio de pruebas de seguridad | Plataforma ALM | Manual (PRV-001) | Integración por API (P2.2) |
| Sistema de registro de tiempos | Plataforma ALM | Manual (PRV-001) | Conciliación automática (P2.4) |
| Aplicaciones | Plataforma de observabilidad | Automático (PRV-001) | Con alertas y objetivos de servicio (P2.5) |

### 6.5 Infraestructura de TI

- La infraestructura de la cuenta analizada opera en nube pública bajo un modelo de responsabilidad compartida con el cliente (PRV-001).
- No se encontró un tablero de costos de nube ni alertas de presupuesto (INT-001; BRE-013).

### 6.6 Uso y apropiación

- En la cuenta analizada el personal tiene acceso a formación en línea y a un programa de patrocinio de certificaciones aprobado por el Line Manager (PRV-001).
- En la cuenta analizada se observaron capacitaciones obligatorias (PRV-001); su periodicidad y alcance corporativo no están confirmados [EVIDENCIA].
- La uniformidad de la adopción de herramientas de IA entre células no está medida; el canal para solicitar licencias no está estandarizado (PRV-001; INT-001).

### 6.7 Seguridad de la información

Calificación cualitativa (INT-001); la calificación numérica con el instrumento MSPI se hace en P1.1.

| Tema del Anexo A de ISO/IEC 27001:2022 | Situación | Evidencia | Calificación actual | Objetivo al mes 24 |
|---|---|---|---|---|
| Controles organizacionales (5.x) | SGSI certificado, certificado ISMS-PE-101123 emitido por A-Lign; fecha publicada como "10/11/2026", sin indicar formato ni tipo de fecha | PUB-002 | Implementado; recertificación por confirmar | Implementado y recertificado |
| Controles de personas (6.x) | Capacitaciones obligatorias en la cuenta analizada | PRV-001 | Parcial | Implementado |
| Controles físicos (7.x) | Sin información para LATAM | — | Sin evidencia | Evaluado |
| Controles tecnológicos (8.x) | Cortafuegos, autenticación multifactor, cifrado de disco, VPN y antimalware | [EVIDENCIA: reabrir la declaración pública de seguridad] | Sin evidencia confirmada | Implementado |
| Desarrollo seguro (8.25 a 8.29) | Pruebas de seguridad continuas y clasificación de vulnerabilidades propias frente a heredadas | PRV-001 | Parcial | Implementado en el pipeline |

Además: no se encontró evidencia pública de la vigencia y el alcance de un informe SOC 2 tipo II (BRE-015). En la cuenta analizada existen lineamientos sobre el uso de IA (PRV-001), pero no se encontró un sistema de gestión de IA según ISO/IEC 42001 (BRE-001) ni controles de permisos para agentes de IA (BRE-008).

### 6.8 Análisis DOFA por dominio

Elaboración propia a partir de §6.1 a §6.7 (INT-001).

| Dominio | Fortalezas | Debilidades | Oportunidades | Amenazas |
|---|---|---|---|---|
| Estrategia de TI | Posicionamiento público en IA | Sin misión, visión, catálogo de servicios ni tablero de TI | Demanda de clientes por IA gobernada | Competidores con gobierno de IA certificado |
| Gobierno de TI | Roles claros en proyectos | Sin comité, RACI ni matriz de riesgos de TI | Marcos de referencia maduros (COBIT) | Obligaciones no validadas tras la privatización |
| Información | Alianzas registradas con plataformas de datos | Sin plataforma unificada ni inventario de IA | Catálogos de metadatos de los socios | Uso de datos del cliente sin trazabilidad |
| Sistemas de información | Plataforma única de ciclo de vida en la cuenta | Flujos manuales entre herramientas | Integración por API | Retrasos en remediación |
| Infraestructura | Ambientes separados | Sin infraestructura como código ni control de costos | Automatización del aprovisionamiento | Sobrecostos de nube; cambios sujetos al cliente |
| Uso y apropiación | Programa de certificaciones | Adopción de IA no medida | Formación de los socios | Rotación de personal |
| Seguridad | SGSI certificado; pruebas continuas | Recertificación con fecha incierta; sin AIMS | ISO/IEC 42001 como diferenciador | Fuga de código o datos por herramientas de IA |

### 6.9 Tendencias tecnológicas

| Tendencia | Procesos donde aplica | Uso previsto |
|---|---|---|
| IA generativa y asistentes de código | PM01, PM02 | Acelerar desarrollo y remediación con controles (P1.2 a P1.4) |
| Generación aumentada por recuperación (RAG) | PM01, PM03 | Soluciones para clientes con evaluación automática de calidad (P3.1, P3.2) |
| Agentes de IA | PM01 | Agentes en producción con controles (P3.3) |
| DevOps y DevSecOps | PM01, PM02 | Pipelines con pruebas de seguridad obligatorias (P2.3) |
| Infraestructura como código | PM01 | Ambientes reproducibles (P2.6) |
| Plataformas de datos en la nube | PM03 | Plataforma de datos y catálogo (P3.5, P3.6) |
| Observabilidad | PM01 | Tableros y objetivos de servicio (P2.5) |

## 7. Situación objetivo

Todo lo de este numeral es **propuesto** y depende de la aprobación del Comité Directivo del PETI.

### 7.1 Estrategia de TI

Misión de TI: proveer y gobernar las plataformas, herramientas y controles con los que la operación LATAM entrega software y soluciones de IA a sus clientes, de forma segura, medible y conforme con los compromisos de la compañía.

Visión de TI: en septiembre de 2028, la operación LATAM gestionará el uso de la IA con un sistema certificable, entregará software con pipelines y ambientes estandarizados, y medirá su desempeño con un tablero de indicadores revisado cada trimestre.

Objetivos estratégicos de TI y metas (actividad 8). El horizonte es de 24 meses, por lo que la columna "año 3" del Anexo 1 no aplica.

| Objetivo | Objetivo corporativo | Meta | Indicador | Línea base | Año 1 (sep. 2027) | Año 2 (sep. 2028) |
|---|---|---|---|---|---|---|
| OETI01 Gobernar el uso de la IA en la operación LATAM | OC01, OC02 | METI01 Sistemas de IA registrados en el inventario | KPI-08 | Sin inventario | 90 % | 100 % |
| | | METI02 Células con IA activa y licencia aprobada | KPI-04 | Por medir (mes 3) | 85 % | 95 % |
| | | METI03 Casos de IA en producción con clientes | KPI-03 | 0 | 1 | 5 |
| OETI02 Mantener la certificación de seguridad y ampliar las atestaciones a controles de IA | OC02 | METI04 No conformidades mayores en ISO/IEC 27001 | KPI-07 | Por confirmar con el último informe | 0 | 0 |
| | | METI05 Informe SOC 2 tipo II con opinión sin salvedades | KPI-13 | Por confirmar (P1.1) | — | Sí |
| | | METI06 Tiempo de remediación de vulnerabilidades críticas | KPI-05 | Por medir (mes 3) | < 72 h | < 24 h |
| OETI03 Estandarizar la entrega de software, su gobierno, su monitoreo y su costo | OC03 | METI07 Ejecución acumulada del PETI | KPI-01 | 0 % | 55 % | 95 % |
| | | METI08 Sesiones de comité con acta | KPI-14 | 0 % | 90 % | 90 % |
| | | METI09 Conciliación de horas y tareas | KPI-06 | Por medir (mes 6) | 90 % | 95 % |
| | | METI10 Ambientes con infraestructura como código | KPI-11 | 0 % | 60 % | 100 % |
| | | METI11 Servicios con objetivos de nivel de servicio monitoreados | KPI-12 | Por medir | 100 % | 100 % |
| | | METI12 Variación del costo de nube en cuentas administradas | KPI-02 | Por medir (P2.7) | −5 % | −15 % |
| | | METI13 Células con plantilla ALM homologada | KPI-15 | 0 % | 100 % | 100 % |
| | | METI14 Fuentes de datos priorizadas catalogadas | KPI-16 | 0 % | — | 80 % |
| OETI04 Desarrollar las capacidades del personal en IA, nube y datos | OC04 | METI15 Personal técnico certificado | KPI-09 | Por medir (mes 3) | 70 % | 90 % |
| | | METI16 Personal rotado entre células | KPI-10 | Por medir (mes 6) | 50 % | 100 % |

Principios de arquitectura:

| Principio | Enunciado |
|---|---|
| IA considerada desde el diseño | Toda iniciativa nueva evalúa el uso de IA y sus riesgos antes de empezar |
| Seguridad y cumplimiento primero | Ningún componente pasa a producción sin validación de seguridad |
| Todo se observa | Sistemas, servicios y modelos de IA emiten telemetría trazable |
| Automatizar el trabajo repetitivo | Infraestructura como código, pipelines y flujos de seguridad automáticos |
| Conocimiento documentado | La documentación vive en la wiki del proyecto y se rota al personal |

Catálogo de servicios de TI propuesto: gestión del ciclo de vida de aplicaciones; aprovisionamiento de herramientas y licencias de IA; pruebas de seguridad y remediación; monitoreo y observabilidad; aprovisionamiento de ambientes; plataforma de datos; mesa de servicio interna; formación y certificación. Cada servicio tendrá ficha con responsable y acuerdo de nivel de servicio (P2.8). Las capacidades objetivo están en §6.1.4.

### 7.2 Gobierno de TI

Arquitectura de negocio (vista TOGAF): se propone un Comité Directivo del PETI (trimestral), un Comité Táctico de TI (mensual) y comités operativos por célula (semanales), con términos de referencia y actas; una matriz de riesgos de TI mantenida por el Comité Táctico (§11); una guía de presupuesto y costos de TI alineada con COBIT APO06; un registro de obligaciones regulatorias por país; y una matriz RACI en la que el Comité Directivo aprueba (A), el Comité Táctico y los líderes de dominio ejecutan (R), las células son consultadas (C) y todo el personal es informado (I).

### 7.3 Información

Arquitectura de datos (vista TOGAF): se propone una plataforma de datos por seleccionar entre los socios con alianza registrada (PUB-006 a PUB-008), con un solo catálogo de metadatos, y un repositorio de variables de IA versionado y vinculado al inventario de IA.

### 7.4 Sistemas de información

Arquitectura de aplicaciones (vista TOGAF): se propone un estándar de Perficient para proponer a los clientes, que incluye plantillas ALM homologadas por tipo de célula, integración automática entre las pruebas de seguridad y la plataforma ALM, pipelines de CI/CD con análisis estático (SAST), dinámico (DAST) y de composición de software (SCA) obligatorios, y conciliación automática entre el registro de tiempos y la plataforma ALM.

### 7.5 Infraestructura de TI

Arquitectura de tecnología (vista TOGAF): en los ambientes que la operación administra por contrato, se propone aprovisionar todo con infraestructura como código, tableros de observabilidad estandarizados con alertas y objetivos de nivel de servicio, y un tablero de costos de nube con alertas de presupuesto.

### 7.6 Uso y apropiación

Procedimiento estándar para solicitar herramientas de IA; plan de certificaciones por rol; currículo de IA para todo el personal; rotación entre células al menos una vez en el periodo.

### 7.7 Seguridad de la información

Certificado ISO/IEC 27001:2022 recertificado; sistema de gestión de IA según ISO/IEC 42001 implantado y auditado internamente; permisos para agentes de IA definidos como código; informe SOC 2 tipo II con alcance que incluya controles de IA.

## 8. Brechas y oportunidades

### 8.1 Catálogo de brechas

Supuestos de costo (INT-001): costo de inversión total estimado en órdenes de magnitud, por validar con Finanzas. Bajo: menos de USD 50.000. Medio: entre USD 50.000 y 250.000. Alto: más de USD 250.000 (para estimar el presupuesto se toma un tope de USD 1.000.000). Incluye horas del personal, licencias y servicios externos.

| ID | Proceso | Elemento afectado | Dominio | Acción | Descripción y justificación | Tiempo estimado | Costo estimado | Proyecto en curso |
|---|---|---|---|---|---|---|---|---|
| BRE-001 | PM01 | Sistema de gestión de IA | Seguridad | Crear | Existen lineamientos de uso de IA en la cuenta (PRV-001), pero no un sistema de gestión (§6.7) | 6 meses | Medio | No |
| BRE-002 | PM01 | Inventario de sistemas de IA | Información | Crear | No hay registro de modelos, proveedores ni datos (§6.3) | 4 meses | Bajo | No |
| BRE-003 | PM02 | Integración de hallazgos de seguridad con la plataforma ALM | Sistemas de información | Crear | Los hallazgos pasan a mano (§6.4) | 3 meses | Bajo | No |
| BRE-004 | PM01 | Plantillas ALM | Sistemas de información | Modificar | Homogeneidad entre células sin verificar (§6.4) | 4 meses | Bajo | No |
| BRE-005 | PA03 | Procedimiento de licencias de IA | Uso y apropiación | Modificar | Canal de solicitud no estandarizado (§6.6) | 2 meses | Bajo | No |
| BRE-006 | PV01 | Recertificación de ISO/IEC 27001 | Seguridad | Modificar | La fecha publicada cae al inicio del plan (§6.7) | 1 a 6 meses | Medio | Sí, si la auditoría de recertificación ya está programada [EVIDENCIA]; si no, No, y R02 se trata como materializado |
| BRE-007 | PM01 | Infraestructura como código | Infraestructura | Crear | Sin evidencia de aprovisionamiento automatizado (§6.4) | 6 meses | Medio | No |
| BRE-008 | PM01 | Permisos de agentes de IA | Seguridad | Crear | Sin controles sobre las acciones de los agentes (§6.7) | 3 meses | Medio | No |
| BRE-009 | PA01 | Formación en IA | Uso y apropiación | Modificar | Currículo no desplegado a todo el personal (§6.6) | 18 meses | Medio | No |
| BRE-010 | PM03 | Plataforma de datos | Información | Crear | Alianzas sin plataforma unificada (§6.3). Necesidad de datos compartidos en proyectos LATAM [EVIDENCIA]; si no se confirma, pasa a oportunidad | 6 meses | Alto | No |
| BRE-011 | PE01 | Comités táctico y operativos | Gobierno | Crear | Sin comités ni actas (§6.2) | 3 meses | Bajo | No |
| BRE-012 | PA02 | Conciliación de tiempos | Sistemas de información | Crear | Conciliación manual con la plataforma ALM (§6.4) | 4 meses | Bajo | No |
| BRE-013 | PM01 | Control de costos de nube | Infraestructura | Crear | Sin tablero ni alertas de costos (§6.5) | 3 meses | Bajo | No |
| BRE-014 | PM01 | Tableros de observabilidad | Infraestructura | Modificar | Estandarización de tableros y objetivos de servicio sin verificar (§6.4) | 4 meses | Bajo | No |
| BRE-015 | PV01 | Atestación SOC 2 | Seguridad | Modificar | Vigencia y alcance sin evidencia; no cubre controles de IA (§6.7) | 12 meses | Alto | No |
| BRE-016 | PE01 | Misión, visión y catálogo de servicios de TI | Estrategia de TI | Crear | No existen (§6.1.2) | 3 meses | Bajo | No |
| BRE-017 | PE01 | RACI, matriz de riesgos, presupuesto de TI y registro de obligaciones | Gobierno | Crear | No documentados (§6.2) | 3 meses | Bajo | No |
| BRE-018 | PE01 | Tablero de indicadores de TI | Estrategia de TI | Crear | No existe (§6.1.3) | 3 meses | Bajo | No |

### 8.2 Oportunidades y necesidades de TI

| ID | Oportunidad | Descripción | Prioridad | Proyecto |
|---|---|---|---|---|
| OPT-001 | RAG para clientes | Soluciones de generación aumentada por recuperación en producción | Alta | P3.1 |
| OPT-002 | Evaluación automática de modelos de lenguaje | Métricas de calidad y alucinación en los pipelines | Alta | P3.2 |
| OPT-003 | Agentes en producción | Agentes conversacionales con controles de ISO/IEC 42001 | Alta | P3.3 |
| OPT-004 | MCP en proyectos regulados | Integración de modelos y herramientas con control de acceso | Media | P4.5 |
| OPT-005 | Construcción rápida de aplicaciones con IA | Uso de plataformas como Lovable (PUB-009) con reglas de calidad | Media | Evaluación en el CoE de IA (P1.8) |
| OPT-006 | Casos de estudio | Publicación de resultados verificables | Media | P4.6 |
| OPT-007 | Seguimiento y continuidad del PETI | Balance del ciclo y arquitectura del siguiente | Media | P4.3, P4.4 |

### 8.3 Iniciativas de otros planes

La operación LATAM no tiene otros planes corporativos con componente de TI registrados en la evidencia disponible [EVIDENCIA: planes de la casa matriz aplicables a LATAM]. Si existen, se incorporan a la hoja de ruta en la primera revisión trimestral.

## 9. Hoja de ruta y portafolio de proyectos

Puerta de ejecución: ningún proyecto pasa a ejecución sin patrocinador nominal, caso de negocio, estimación de inversión y operación, fuente de financiación, dependencias, riesgos y criterio de aceptación. Los responsables son roles propuestos. Los proyectos que tocan ambientes de clientes requieren su aprobación (R11).

Criterios de priorización (INT-001): primero lo que trata un riesgo crítico o un plazo externo (recertificación, obligaciones legales); después lo que otros proyectos necesitan (gobierno de IA, inventario, comités, plantillas); después la estandarización de la entrega; al final el escalamiento de IA y datos, que depende de los anteriores y tiene el mayor costo.

### 9.1 Catálogo de proyectos

| ID | Proyecto | Dominio | Objetivo de TI | Meta | Brecha u oportunidad | Indicador | Responsable | Meses | Inicio | Costo |
|---|---|---|---|---|---|---|---|---|---|---|
| P1.1 | Recertificación de ISO/IEC 27001:2022 | Seguridad | OETI02 | METI04 | BRE-006 | KPI-07 | CISO | 0-5 | 2026-09 | Medio |
| P1.2 | Sistema de gestión de IA | Seguridad | OETI01 | METI01 | BRE-001 | KPI-08 | CISO, con CTO | 1-6 | 2026-10 | Medio |
| P1.3 | Inventario de sistemas de IA | Información | OETI01 | METI01 | BRE-002 | KPI-08 | Arquitectura | 1-4 | 2026-10 | Bajo |
| P1.4 | Permisos como código para agentes de IA | Seguridad | OETI01 | METI01 | BRE-008 | KPI-08 | DevSecOps | 4-6 | 2027-01 | Medio |
| P1.5 | Capacitación obligatoria en seguridad e IA | Uso y apropiación | OETI04 | METI15 | BRE-009 | KPI-09 | Talento humano, con CISO | 1-8 | 2026-10 | Bajo |
| P1.6 | Procedimiento de licencias de IA | Uso y apropiación | OETI01 | METI02 | BRE-005 | KPI-04 | PM y Line Manager, con CTO | 1-3 | 2026-10 | Bajo |
| P1.7 | Plan de certificaciones por rol | Uso y apropiación | OETI04 | METI15 | BRE-009 | KPI-09 | Talento humano, con CTO | 1-5 | 2026-10 | Bajo |
| P1.8 | Centro de excelencia (CoE) de IA | Estrategia de TI | OETI01 | METI02 | BRE-001, BRE-005, OPT-005 | KPI-04 | CTO | 3-6 | 2026-12 | Medio |
| P1.9 | Concepto legal de obligaciones vigentes | Gobierno | OETI03 | METI08 | BRE-017 | KPI-14 | CTO, con Legal y Finanzas | 1-3 | 2026-10 | Bajo |
| P2.1 | Plantillas ALM homologadas | Sistemas de información | OETI03 | METI13 | BRE-004 | KPI-15 | Technical Leads, con CTO | 7-10 | 2027-04 | Bajo |
| P2.2 | Integración de pruebas de seguridad con la plataforma ALM | Sistemas de información | OETI02 | METI06 | BRE-003 | KPI-05 | DevSecOps | 9-11 | 2027-06 | Bajo |
| P2.3 | Pipeline de CI/CD estandarizado | Sistemas de información | OETI02 | METI06 | BRE-003, BRE-007 | KPI-05 | DevSecOps | 8-12 | 2027-05 | Medio |
| P2.4 | Conciliación entre registro de tiempos y plataforma ALM | Sistemas de información | OETI03 | METI09 | BRE-012 | KPI-06 | BI y operaciones | 9-12 | 2027-06 | Bajo |
| P2.5 | Observabilidad estandarizada | Infraestructura | OETI03 | METI11 | BRE-014 | KPI-12 | SRE | 7-10 | 2027-04 | Bajo |
| P2.6 | Infraestructura como código | Infraestructura | OETI03 | METI10 | BRE-007 | KPI-11 | Arquitectura de nube | 7-12 | 2027-04 | Medio |
| P2.7 | Tablero de costos de nube | Infraestructura | OETI03 | METI12 | BRE-013 | KPI-02 | FinOps | 7-9 | 2027-04 | Bajo |
| P2.8 | Formalización del gobierno de TI | Gobierno | OETI03 | METI08 | BRE-011, BRE-016, BRE-017, BRE-018 | KPI-14 | CTO | 7-9 | 2027-04 | Bajo |
| P3.1 | RAG en producción para clientes | Sistemas de información | OETI01 | METI03 | OPT-001 | KPI-03 | CoE de IA | 13-18 | 2027-10 | Alto |
| P3.2 | Evaluación automática de modelos de lenguaje | Sistemas de información | OETI01 | METI01 | OPT-002 | KPI-08 | CoE de IA | 13-16 | 2027-10 | Medio |
| P3.3 | Agente conversacional en producción | Sistemas de información | OETI01 | METI03 | OPT-003 | KPI-03 | CoE de IA y PM | 13-18 | 2027-10 | Alto |
| P3.4 | Cierre del plan de certificaciones | Uso y apropiación | OETI04 | METI15 | BRE-009 | KPI-09 | Talento humano, con CTO | 13-18 | 2027-10 | Medio |
| P3.5 | Plataforma de datos | Información | OETI03 | METI14 | BRE-010 | KPI-16 | Arquitectura de datos | 13-18 | 2027-10 | Alto |
| P3.6 | Catálogo de metadatos | Información | OETI03 | METI14 | BRE-010 | KPI-16 | Gobierno de datos | 13-18 | 2027-10 | Medio |
| P3.7 | Repositorio de variables de IA | Información | OETI01 | METI01 | BRE-002 | KPI-08 | CoE de IA | 15-18 | 2027-12 | Medio |
| P4.1 | Informe SOC 2 tipo II con controles de IA | Seguridad | OETI02 | METI05 | BRE-015 | KPI-13 | CISO | 13-24 | 2027-10 | Alto |
| P4.2 | Auditoría interna del sistema de gestión de IA | Seguridad | OETI01 | METI01 | BRE-001 | KPI-08 | CISO y CoE de IA | 19-21 | 2028-04 | Bajo |
| P4.3 | Balance y retorno del PETI | Estrategia de TI | OETI03 | METI07 | OPT-007 | KPI-01 | CTO y FinOps | 22-24 | 2028-07 | Bajo |
| P4.4 | Arquitectura objetivo 2028-2030 | Estrategia de TI | OETI03 | METI07 | OPT-007 | KPI-01 | CTO y arquitectura | 21-24 | 2028-06 | Bajo |
| P4.5 | MCP en un proyecto regulado | Sistemas de información | OETI01 | METI03 | OPT-004 | KPI-03 | CoE de IA | 19-24 | 2028-04 | Medio |
| P4.6 | Caso de estudio publicado | Estrategia de TI | OETI01 | METI03 | OPT-006 | KPI-03 | Marketing, con CoE de IA | 21-24 | 2028-06 | Bajo |

### 9.2 Fichas de los proyectos de la fase 1

| Proyecto | ¿Para qué? | ¿Cómo? | Entregable | Meta |
|---|---|---|---|---|
| P1.1 | Evitar que caduque la certificación que exigen los clientes | Mes 0 (antes del 2026-10-11): confirmar con A-Lign el vencimiento y completar la auditoría de recertificación. Si vence sin recertificación, contingencia: auditoría de certificación inicial [VERIFICAR condiciones con A-Lign]. Meses 1 y 2: confirmar existencia, periodo y alcance del informe SOC 2 vigente. Meses 1 a 5: cierre de no conformidades y calificación MSPI | Certificado recertificado | 0 no conformidades mayores |
| P1.2 | Dar reglas formales al uso de IA, partiendo de los lineamientos existentes | Política de IA, roles, evaluación de impacto y riesgos, controles según ISO/IEC 42001 y NIST AI RMF | Manual de IA responsable v1.0 | Manual aprobado en el mes 6 |
| P1.3 | Saber qué IA se usa, con qué datos y dónde | Levantamiento por célula; registro de modelo, proveedor, datos y responsable | Inventario y procedimiento | 90 % de sistemas registrados en el año 1 |
| P1.4 | Limitar lo que un agente de IA puede ejecutar | Piloto sobre el inventario de P1.3: acciones permitidas, políticas versionadas, registro de acciones | Marco de permisos operativo | Aplicado a todos los agentes inventariados |
| P1.5 | Reducir el riesgo de fuga de datos por mal uso de IA | Módulo de seguridad en los meses 1 a 5; módulo de IA, basado en el manual de P1.2, en los meses 6 a 8 | Módulos desplegados | 100 % del personal capacitado en el mes 8 |
| P1.6 | Dar acceso ordenado a herramientas de IA | Procedimiento de solicitud, justificación ante el cliente y aprobación | Procedimiento publicado | Publicado en el mes 3 |
| P1.7 | Planear la certificación del personal | Currículo por rol (nube, IA, datos) con calendario | Plan aprobado | Aprobado en el mes 5 |
| P1.8 | Tener un equipo de referencia en IA | Carta de constitución, miembros, pruebas de concepto, evaluación de herramientas nuevas (OPT-005) | Carta y primeras pruebas de concepto | Carta aprobada en el mes 4 |
| P1.9 | Saber qué obligaciones regulatorias siguen vigentes antes de fijar controles | Concepto de Legal y Finanzas sobre SOX residual y protección de datos por país; registro de obligaciones | Concepto y registro | Concepto emitido en el mes 3 |

### 9.3 Descripción de los proyectos de las fases 2 a 4

| Proyecto | Descripción y alcance |
|---|---|
| P2.1 | Plantilla maestra de wiki, tableros y sprints por tipo de célula, propuesta a los clientes |
| P2.2 | Conector que convierte cada hallazgo de seguridad en ticket categorizado y asignado |
| P2.3 | Plantilla de pipeline con puertas de calidad SAST, DAST y SCA obligatorias |
| P2.4 | Tablero que concilia horas registradas y tareas cerradas por proyecto |
| P2.5 | Tableros estándar, alertas y objetivos de nivel de servicio por ambiente |
| P2.6 | Repositorio de infraestructura como código para los ambientes administrados por contrato |
| P2.7 | Tablero de costos de nube con alertas de presupuesto y ajuste trimestral de capacidad |
| P2.8 | Comité Táctico y comités operativos con actas; RACI; matriz de riesgos; guía de presupuesto; misión, visión y catálogo de servicios de TI; tablero de indicadores |
| P3.1 | Al menos tres casos de RAG en producción con métricas de calidad |
| P3.2 | Suite de evaluación automática de salidas de modelos de lenguaje en CI/CD |
| P3.3 | Agente conversacional en producción con informe de controles |
| P3.4 | Seguimiento y cierre del plan de certificaciones |
| P3.5 | Plataforma de datos seleccionada entre los socios con alianza, con arquitectura validada |
| P3.6 | Catálogo único de metadatos con linaje y clasificación |
| P3.7 | Repositorio de variables de IA versionado y vinculado al inventario |
| P4.1 | Preparación en los meses 13 a 15; periodo de observación en los meses 16 a 21 [VERIFICAR duración mínima con el auditor]; informe en el mes 24 |
| P4.2 | Auditoría interna del sistema de gestión de IA; precede al informe de P4.1 |
| P4.3 | Balance del PETI: cumplimiento de metas, inversión y resultados |
| P4.4 | Arquitectura objetivo para el ciclo 2028-2030 |
| P4.5 | Caso de MCP en un proyecto regulado con controles de acceso |
| P4.6 | Caso de estudio publicado con resultados verificables |

### 9.4 Presupuesto estimado por fase

Rangos calculados con los supuestos de §8.1 (INT-001); no son presupuesto aprobado.

| Fase | Proyectos bajo / medio / alto | Rango estimado (USD) |
|---|---|---|
| 1 | 5 / 4 / 0 | 200.000 a 1.250.000 |
| 2 | 6 / 2 / 0 | 100.000 a 800.000 |
| 3 | 0 / 4 / 3 | 950.000 a 4.000.000 |
| 4 | 4 / 1 / 1 | 300.000 a 1.450.000 |
| Total | 15 / 11 / 4 | 1.550.000 a 7.500.000 |

### 9.5 Mapa de ruta

| Fase | Periodo | Meses | Proyectos | Hito de cierre |
|---|---|---|---|---|
| 1. Gobierno, SGSI y habilitación de IA | Sep. 2026 a mar. 2027 | 0-6 | P1.1 a P1.9 | Decisión de recertificación antes del 2026-10-11; manual de IA aprobado |
| 2. Estandarización de la entrega y gobierno | Abr. 2027 a sep. 2027 | 7-12 | P2.1 a P2.8 | Pipeline estándar y comités formalizados |
| 3. Escalamiento de IA y datos | Oct. 2027 a mar. 2028 | 13-18 | P3.1 a P3.7 | Casos de IA en producción con métricas |
| 4. Madurez y evaluación | Abr. 2028 a sep. 2028 | 19-24 | P4.1 a P4.6 | Informe SOC 2 y balance del PETI |

Dependencias: P1.9 precede a los controles de P1.2; P1.2 y P1.3 preceden a P1.4, P3.3 y P4.2; P1.2 precede al módulo de IA de P1.5; P2.1 precede a P2.2 y P2.4; P2.6 precede a P2.3 en la parte de ambientes; P4.2 precede al informe de P4.1; P2.8 debe estar activo antes de la primera revisión anual.

## 10. Indicadores

Hojas de vida (actividad 14). Rangos por indicador; "cumplimiento" es el valor medido sobre la meta.

| ID | Indicador | Dominio | Objetivo y meta | Tipo | Fórmula | Línea base | Meta | Frecuencia | Fuente de datos | Responsable | Rangos | Mide |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| KPI-01 | Ejecución acumulada del PETI | Estrategia de TI | OETI03, METI07 | Estratégico | Proyectos terminados / 30 × 100 | 0 % | 55 % mes 12; 95 % mes 24 | Trimestral | Tablero de seguimiento del PETI | CTO | Bueno ≥ 95 % de la meta; intermedio 71 a 94 %; bajo ≤ 70 % | P1.9, P4.3, P4.4 |
| KPI-02 | Variación del costo de nube en cuentas administradas por Perficient | Infraestructura | OETI03, METI12 | Táctico | (Costo del periodo − costo base) / costo base × 100 | Por medir (P2.7) | −15 % al mes 24 | Trimestral | Tablero de costos de nube | FinOps | Bueno ≤ −15 %; intermedio entre −14 % y 0 %; bajo > 0 % | P2.7 |
| KPI-03 | Casos de IA en producción con clientes | Sistemas de información | OETI01, METI03 | Estratégico | Número de casos con métricas publicadas | 0 | 3 al mes 18; 5 al mes 24 | Semestral | Registro del CoE de IA | CoE de IA | Bueno ≥ meta; intermedio ≥ 60 % de la meta; bajo < 60 % | P3.1, P3.3, P4.5, P4.6 |
| KPI-04 | Adopción de IA | Uso y apropiación | OETI01, METI02 | Táctico | Células con IA activa y licencia aprobada / total de células × 100 | Por medir (mes 3) | 85 % mes 12; 95 % mes 24 | Mensual | Inventario de licencias | CoE de IA | Comunes | P1.6, P1.8 |
| KPI-05 | Tiempo de remediación de vulnerabilidades | Seguridad | OETI02, METI06 | Operativo | Promedio de horas entre detección y cierre del ticket, por severidad | Por medir (mes 3) | Crítica < 72 h al mes 12 y < 24 h al mes 24; alta < 72 h; media < 7 días | Mensual | Servicio de pruebas de seguridad y plataforma ALM | DevSecOps | Bueno ≤ meta; intermedio hasta 1,5 × meta; bajo > 1,5 × meta | P2.2, P2.3 |
| KPI-06 | Conciliación de horas y tareas | Sistemas de información | OETI03, METI09 | Operativo | Horas conciliadas / horas registradas × 100 | Por medir (mes 6) | 95 % | Mensual | Registro de tiempos y plataforma ALM | Operaciones | Comunes | P2.4 |
| KPI-07 | No conformidades mayores en ISO/IEC 27001 | Seguridad | OETI02, METI04 | Estratégico | Número de no conformidades mayores en auditorías ISO/IEC 27001 | Por confirmar | 0 | Anual | Informes de auditoría | CISO | Bueno 0; bajo ≥ 1 | P1.1 |
| KPI-08 | Cobertura del inventario de IA | Información | OETI01, METI01 | Táctico | Sistemas de IA registrados / sistemas de IA identificados × 100 | 0 % | 90 % año 1; 100 % año 2 | Trimestral | Inventario de IA | Arquitectura | Comunes | P1.2 a P1.4, P3.2, P3.7, P4.2 |
| KPI-09 | Personal técnico certificado | Uso y apropiación | OETI04, METI15 | Táctico | Personal técnico con más de 6 meses en la operación y al menos una certificación vigente / total de ese personal × 100 | Por medir (mes 3) | 70 % mes 12; 90 % mes 24 | Trimestral | Registro de certificaciones | Talento humano | Comunes | P1.5, P1.7, P3.4 |
| KPI-10 | Rotación entre células | Uso y apropiación | OETI04, METI16 | Táctico | Personas rotadas al menos una vez / total × 100 | Por medir (mes 6) | 100 % al mes 24 | Semestral | Registro de asignaciones | Line Managers | Comunes | Rotación planificada (§7.6) |
| KPI-11 | Ambientes con infraestructura como código | Infraestructura | OETI03, METI10 | Táctico | Ambientes administrados aprovisionados con IaC / total de ambientes administrados × 100 | 0 % | 60 % mes 12; 100 % mes 24 | Trimestral | Repositorio de IaC | Arquitectura de nube | Comunes | P2.6 |
| KPI-12 | Servicios con objetivos de nivel de servicio monitoreados | Infraestructura | OETI03, METI11 | Operativo | Servicios con tablero y alertas estándar / servicios en producción × 100 | Por medir | 100 % al mes 12 | Trimestral | Plataforma de observabilidad | SRE | Comunes | P2.5 |
| KPI-13 | Informe SOC 2 tipo II sin salvedades | Seguridad | OETI02, METI05 | Estratégico | Informe emitido con opinión sin salvedades (sí o no) y número de excepciones | Por confirmar (P1.1) | Sí, al mes 24 | Anual | Informe del auditor | CISO | Bueno: sí y sin excepciones materiales; bajo: no | P4.1 |
| KPI-14 | Sesiones de comité con acta | Gobierno | OETI03, METI08 | Táctico | Sesiones con acta / sesiones programadas × 100 | 0 % | 90 % | Trimestral | Actas de comités | CTO | Comunes | P1.9, P2.8 |
| KPI-15 | Células con plantilla ALM homologada | Sistemas de información | OETI03, METI13 | Operativo | Células con plantilla / total de células × 100 | 0 % | 100 % al mes 12 | Trimestral | Plataforma ALM | Technical Leads | Comunes | P2.1 |
| KPI-16 | Fuentes de datos priorizadas catalogadas | Información | OETI03, METI14 | Táctico | Fuentes catalogadas / fuentes priorizadas × 100 | 0 % | 80 % al mes 18 | Trimestral | Catálogo de metadatos | Gobierno de datos | Comunes | P3.5, P3.6 |

Rangos comunes: bueno ≥ 95 % de la meta; intermedio entre 71 % y 94 %; bajo ≤ 70 %. Un indicador solo se usa para evaluar desempeño cuando tiene línea base con fecha y fuente de datos disponible.

## 11. Riesgos de TI

Valoración preliminar. Probabilidad: baja, media o alta. Impacto: medio, alto o crítico. Nivel: alto si el impacto es crítico o si la probabilidad y el impacto son altos; medio si uno de los dos es medio y el otro alto o medio con probabilidad media o alta; bajo en los demás casos. El riesgo residual lo acepta el Comité Directivo del PETI.

| ID | Riesgo | Probabilidad | Impacto | Nivel | Tratamiento | Proyecto o control | Propietario | Residual esperado |
|---|---|---|---|---|---|---|---|---|
| R01 | Fuga de código o datos por herramientas de IA | Media | Crítico | Alto | Repositorios privados, filtros de pérdida de datos, permisos como código | P1.2, P1.4, P1.5 | CISO | Medio |
| R02 | Vencimiento del certificado ISO/IEC 27001 sin recertificación | Alta, mientras no haya evidencia de la auditoría programada | Crítico | Alto | Confirmación de fecha y recertificación en el mes 0; contingencia de certificación inicial | P1.1 | CISO | Bajo |
| R03 | Vulnerabilidades heredadas de dependencias | Alta | Alto | Alto | Análisis de composición en el pipeline; actualización en menos de 30 días | P2.2, P2.3 | DevSecOps | Medio |
| R04 | Inyección de instrucciones o sesgos en modelos | Media | Alto | Medio | Evaluación automática, pruebas adversarias, controles NIST AI RMF | P1.2, P3.2 | CoE de IA | Bajo |
| R05 | Diferencias entre ambientes | Media | Alto | Medio | Infraestructura como código y monitoreo por ambiente | P2.5, P2.6 | Arquitectura de nube | Bajo |
| R06 | Rotación de personal y pérdida de conocimiento | Alta | Medio | Medio | Rotación planificada y documentación en wiki | P2.1; rotación (§7.6) | Line Managers | Medio |
| R07 | Obligaciones regulatorias no validadas tras la privatización | Media | Alto | Medio | Concepto de Legal y Finanzas; registro de obligaciones | P1.9, P2.8 | CTO | Bajo |
| R08 | Sobrecosto de nube | Media | Medio | Medio | Tablero de costos y ajuste trimestral de capacidad | P2.7 | FinOps | Bajo |
| R09 | Brecha de capacitación en IA | Media | Medio | Medio | Plan de certificaciones y mentoría | P1.5, P1.7, P3.4 | Talento humano | Bajo |
| R10 | Problemas de interoperabilidad en entornos multiproveedor | Baja | Medio | Bajo | Herramientas compartidas y acuerdos de nivel de servicio | P2.8 | PM | Bajo |
| R11 | El cliente no autoriza cambios en su infraestructura o herramientas | Media | Alto | Medio | Acuerdo previo con el cliente; estándares presentados como propuesta | P2.1, P2.5, P2.6, P2.7 | PM | Medio |

## 12. Estrategia de comunicación del PETI

Plan propuesto (actividad 17).

### 12.1 Grupos de interés

| Grupo | Descripción | Necesidad de información |
|---|---|---|
| Dirección | CTO, CISO, vicepresidencias de operaciones y entrega (roles propuestos) | Avance, riesgos, decisiones de inversión |
| Líderes de entrega | PM, Line Managers, Technical Leads | Cambios en herramientas, procedimientos y plazos |
| Personal técnico | Desarrolladores y especialistas de todas las células | Qué cambia en su trabajo y qué formación reciben |
| Clientes | Áreas de compras y riesgo tecnológico | Estado de certificaciones y atestaciones |
| Nuevos ingresos | Personal que se incorpora | Contexto del PETI y reglas de uso de IA |

### 12.2 Plan de comunicación

| Actividad | Grupo | Canal | Formato | Responsable | Frecuencia |
|---|---|---|---|---|---|
| Presentación del PETI aprobado | Todo el personal | Plataforma de colaboración e intranet | Documento y sesión | CTO | Una vez (noviembre de 2026) |
| Informe de indicadores y proyectos | Dirección | Sesión del Comité Directivo | Informe ejecutivo | CTO | Trimestral |
| Avance y bloqueos de proyectos | Líderes de entrega | Comité Táctico; wiki | Tablero y acta | Líder del Comité Táctico | Mensual |
| Hoja de ruta y avances | Personal técnico | Correo y plataforma de colaboración | Boletín | Comunicaciones internas | Trimestral |
| Manual de IA responsable y sus cambios | Todo el personal | Correo y sesión de capacitación | Documento y sesión | CISO | En cada versión |
| Resultados de auditorías | Clientes | Reunión con el cliente | Informe formal | CISO | Anual |
| Lecciones aprendidas | Todo el personal | Boletín interno | Artículo | CoE de IA | Semestral |
| Inducción al PETI | Nuevos ingresos | Módulo de inducción | Curso corto | Talento humano | En cada ingreso |

## 13. Gobierno y seguimiento del PETI

### 13.1 Equipo y partes interesadas

Lo elaboró un equipo académico que asume el rol del equipo de arquitectura y gobernanza de TI de la operación LATAM; no es un documento oficial de Perficient.

| Rol en el PETI | Perfil | ¿Existe en Perficient? | Capacidad de decisión |
|---|---|---|---|
| Líder del equipo PETI | Arquitecto empresarial | Rol académico | Consolida y propone |
| Analistas de dominio | Estrategia, gobierno, información, SI, infraestructura, uso y apropiación, seguridad | Rol académico | Diagnóstico y propuestas por dominio |
| Patrocinador | CTO de la operación | [EVIDENCIA] | Aprueba presupuesto y prioridades |
| Responsable de seguridad | CISO | [EVIDENCIA] | Aprueba controles y riesgo residual |
| Partes interesadas | VP de operaciones y de entrega, PM, Line Managers, Technical Leads | [EVIDENCIA] | Consultados |

### 13.2 Instancias de gobierno propuestas

| Instancia | Integrantes | Frecuencia | Función |
|---|---|---|---|
| Comité Directivo del PETI | CTO, CISO, VP de operaciones, VP de entrega | Trimestral | Aprueba el PETI y sus cambios, el presupuesto y el riesgo residual; revisa indicadores |
| Comité Táctico de TI | Arquitectos, Technical Leads, CoE de IA, líder de DevSecOps | Mensual | Seguimiento de proyectos, indicadores y riesgos; resuelve bloqueos |
| Comité operativo por célula | PM, Line Manager y Technical Lead | Semanal (revisión de sprint) | Ejecución y registro de tareas |

### 13.3 Aprobación y actualización

Como condición previa a la actividad 16, se propone constituir con acta el Comité Directivo del PETI en octubre de 2026. El PETI se presenta a ese comité, que deja constancia de su aprobación en acta. P2.8 formaliza después el Comité Táctico, los comités operativos, la RACI y el registro de obligaciones. El plan se revisa cada trimestre y se actualiza al menos una vez al año o cuando cambie un objetivo corporativo, una obligación o la prioridad de un proyecto. Cada actualización se registra en el control de cambios.

## 14. Glosario

| Término | Definición |
|---|---|
| AIMS | Sistema de gestión de inteligencia artificial (AI Management System), según ISO/IEC 42001 |
| ALM | Gestión del ciclo de vida de aplicaciones (Application Lifecycle Management) |
| Arquitectura empresarial | Práctica que analiza la organización desde negocio, datos, aplicaciones, tecnología y seguridad para diagnosticarla y definir su transformación |
| Atestación | Informe de un auditor independiente sobre los controles de una organización, como SOC 2; no es una certificación |
| Brecha | Diferencia entre la situación actual y la objetivo que requiere crear, modificar o eliminar un elemento |
| CI/CD | Integración y entrega continuas |
| CoE | Centro de excelencia |
| DAST, SAST, SCA | Pruebas de seguridad dinámicas, estáticas y de composición de software |
| IaC | Infraestructura como código |
| LLM | Modelo de lenguaje de gran tamaño |
| MCP | Model Context Protocol, protocolo de integración entre modelos de IA y herramientas |
| MRAE | Marco de Referencia de Arquitectura Empresarial del MinTIC |
| Nearshore | Prestación de servicios desde países con husos horarios cercanos a los del cliente |
| Parte interesada | Persona o grupo que influye en el plan o se ve afectado por él |
| Permisos como código | Políticas de acceso escritas como código versionado y auditable |
| RAG | Generación aumentada por recuperación |
| SGSI | Sistema de gestión de seguridad de la información |
| SRE | Ingeniería de confiabilidad del sitio |

## 15. Referencias bibliográficas

American Institute of Certified Public Accountants. (2017). *Trust services criteria for security, availability, processing integrity, confidentiality, and privacy* [VERIFICAR edición revisada de 2022]. AICPA.

Argentina. (2000). *Ley 25.326 de protección de los datos personales*. https://www.argentina.gob.ar/normativa/nacional/ley-25326-64790

Congreso de la República de Colombia. (2012). *Ley 1581 de 2012, por la cual se dictan disposiciones generales para la protección de datos personales* [VERIFICAR Diario Oficial].

EQT. (2024, 2 de octubre). *EQT completes acquisition of Perficient* [Comunicado publicado por Perficient]. https://www.perficient.com/news-room/news-releases/2024/eqt-completes-acquisition-of-perficient

International Organization for Standardization & International Electrotechnical Commission. (2022). *Information security, cybersecurity and privacy protection — Information security management systems — Requirements* (ISO/IEC 27001:2022).

International Organization for Standardization & International Electrotechnical Commission. (2023). *Information technology — Artificial intelligence — Management system* (ISO/IEC 42001:2023).

ISACA. (2018). *COBIT 2019 framework: Governance and management objectives*. ISACA.

México. (2025, 20 de marzo). *Ley Federal de Protección de Datos Personales en Posesión de los Particulares*. https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo125102.html

Ministerio de Ciencia, Tecnología e Innovación. (2025). *Plan estratégico de tecnologías de la información (PETI) y de transformación digital 2023-2026* (Código D103DE01). MinCiencias.

Ministerio de Economía, Fomento y Turismo de Chile. (2026, 1 de septiembre). *Gobierno propone ampliar plazo para implementar nueva Ley de Protección de Datos*. https://www.economia.gob.cl/2026/09/01/gobierno-propone-ampliar-plazo-para-implementar-nueva-ley-de-proteccion-de-datos-y-institucionalidad.htm

Ministerio de Tecnologías de la Información y las Comunicaciones. (2023). *MGGTI.GE.ES.03 – Guía para la construcción del PETI* (Versión 3.0). MinTIC.

Ministerio de Tecnologías de la Información y las Comunicaciones. (2023). *Plantilla PETI* y *Herramientas para la construcción del PETI* [Anexos 1 y 2]. MinTIC.

Ministerio de Tecnologías de la Información y las Comunicaciones. (s. f.). *Marco de Referencia de Arquitectura Empresarial, versión 3.0* [VERIFICAR año]. MinTIC.

National Institute of Standards and Technology. (2023). *Artificial intelligence risk management framework (AI RMF 1.0)* (NIST AI 100-1). https://doi.org/10.6028/NIST.AI.100-1

Perficient. (2025, 5 de junio). *Perficient achieves premier partner status with Snowflake*. https://blogs.perficient.com/perficient-achieves-premier-partner-status-with-snowflake/

Perficient. (2025, 23 de septiembre). *Perficient recognized as a Microsoft AI Business Solutions Inner Circle partner*. https://blogs.perficient.com/perficient-recognized-as-a-microsoft-ai-business-solutions-inner-circle-partner/

Perficient. (2025, 11 de diciembre). *Perficient named a major player in IDC MarketScape reports*. https://blogs.perficient.com/2025/12/11/perficient-named-a-major-player-in-2-idc-marketscape-reports/

Perficient. (2026, 18 de febrero). *Perficient earns Databricks Brickbuilder specialization for healthcare & life sciences*. https://blogs.perficient.com/perficient-earns-databricks-brickbuilder-specialization-for-healthcare-life-sciences/

Perficient. (2026, 26 de marzo). *Perficient's evolved brand*. https://www.perficient.com/About/Newsroom/News-Releases/Perficients-Evolved-Brand

Perficient. (2026, 27 de mayo). *From frontier models to business outcomes: Perficient and Lovable partner* [Comunicado, Business Wire]. https://finance.yahoo.com/sectors/technology/articles/frontier-models-business-outcomes-perficient-153000150.html

Perficient. (2026, 8 de julio). *Perficient and Gradial partner to accelerate agentic marketing in the enterprise* [Comunicado, Business Wire]. https://finance.yahoo.com/technology/ai/articles/perficient-gradial-partner-accelerate-agentic-130000291.html

Perficient. (2026, 9 de septiembre). *Perficient achieves Databricks Brickbuilder specializations*. https://blogs.perficient.com/perficient-achieves-databricks-brickbuilder-specializations/

Perficient. (s. f.). *Customer security statement*. Recuperado en septiembre de 2026 de https://www.perficient.com/customer-security

PeopleCert. (2019). *ITIL 4: Foundation* (Edición 2019) [VERIFICAR editor de la edición citada]. AXELOS.

Presidencia de la República de Colombia. (2022). *Decreto 767 de 2022, por el cual se establecen los lineamientos generales de la Política de Gobierno Digital*.

The Open Group. (2022). *The TOGAF Standard* (10.ª ed.). The Open Group.

U.S. Securities and Exchange Commission. (s. f.). *Perficient, Inc. (CIK 0001085869): Filings*. Recuperado el 19 de septiembre de 2026 de https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001085869

Uruguay. (2008). *Ley 18.331 de protección de datos personales*. https://www.impo.com.uy/bases/leyes/18331-2008

## 16. Control de cambios

| Versión | Fecha | Numerales | Descripción |
|---|---|---|---|
| 1.0 | 2026-09 | Todos | Versión inicial, con la estructura del PETI de MinCiencias |
| 1.1 | 2026-09 | 3, 5-7, 9, 13-15, 18 | Clasificación de información, registro de evidencias, delimitación del alcance, condición societaria y puertas de validación |
| 2.0 | 2026-09-19 | Todos | Reestructuración según la plantilla PETI y la Guía MGGTI.GE.ES.03: metodología, procesos, DOFA, tendencias, estrategia de TI con metas, brechas con tiempo y costo, catálogo de proyectos, hojas de vida de indicadores, riesgos con tratamiento, comunicaciones y referencias |
| 2.1 | 2026-09-19 | Todos | Correcciones de la auditoría de conformidad, evidencias y fuentes. Herramientas de la cuenta analizada nombradas por categoría. P1.1 en el mes 0 con contingencia; Comité Directivo constituido antes de la aprobación. Metas METI01 a METI16 alineadas con KPI-01 a KPI-16 (nuevos KPI-13 a KPI-16; KPI-07 solo ISO). Catálogo de proyectos con dominio, meta e inicio; brechas con proceso y dominio único. Nuevas BRE-016 a BRE-018, OPT-007, P1.9 y R11. Capacidades de TI, mapa de integraciones, calificación de seguridad, compromisos con plazo, presupuesto por fase, criterios de priorización y dependencias. Alianzas, SOX y leyes de datos por país con evidencia (PUB-004 a PUB-015). Referencias ampliadas |

Elaboró: equipo académico del PETI, en el rol de equipo de arquitectura y gobernanza de TI de la operación LATAM.
Revisó: CTO y CISO (propuesto).
Aprobó: Comité Directivo del PETI (pendiente de constitución).

## Anexo A. Equivalencia con los identificadores del Anexo 1

| Elemento | Identificador en este PETI | Identificador del Anexo 1 |
|---|---|---|
| Objetivos de TI | OETI01 a OETI04 | OETI01 a OETI04 |
| Metas de TI | METI01 a METI16 | METI01 a METI16 |
| Brechas | BRE-001 a BRE-018 | B001 a B018 |
| Proyectos | P1.1 a P4.6 (30) | IT001 a IT030, en el orden del catálogo |
| Indicadores | KPI-01 a KPI-16 | IND.ES.01 a IND.ES.16; se usa el prefijo ES como único para todo el tablero, y el dominio va en la hoja de vida |

## Anexo B. Procesos del PETI frente a marcos de referencia

| Dominio operativo | Proyecto o elemento | Marco | Referencia |
|---|---|---|---|
| Marco de gobierno | P2.8 | COBIT 2019 | EDM01 Asegurar el establecimiento y mantenimiento del marco de gobierno |
| Portafolio | §9 | COBIT 2019 | APO05 Gestionar el portafolio |
| Registro de tiempos y costos | P2.4, P2.7 | COBIT 2019 | APO06 Gestionar el presupuesto y los costos |
| Talento | P1.5, P1.7 | COBIT 2019 / ISO/IEC 27001:2022 | APO07 Gestionar los recursos humanos; 6.3 Concienciación, educación y formación |
| Gestión de riesgos de TI | §11 | COBIT 2019 | APO12 Gestionar el riesgo |
| Operación de servicios | P2.5 | COBIT 2019 / ITIL 4 | DSS01 Gestionar las operaciones; práctica de monitoreo y gestión de eventos |
| Obligaciones legales | P1.9 | ISO/IEC 27001:2022 | 5.31 Requisitos legales, estatutarios, reglamentarios y contractuales |
| Datos personales | P1.9 | ISO/IEC 27001:2022 | 5.34 Privacidad y protección de la información de identificación personal |
| Uso de nube | P2.6, P2.7 | ISO/IEC 27001:2022 | 5.23 Seguridad de la información para el uso de servicios en la nube |
| Inventario de IA | P1.3 | ISO/IEC 27001:2022 | 5.9 Inventario de información y otros activos asociados |
| Infraestructura como código | P2.6 | ISO/IEC 27001:2022 | 8.9 Gestión de la configuración |
| Seguridad de aplicaciones | P2.2, P2.3 | ISO/IEC 27001:2022 | 8.28 Codificación segura; 8.29 Pruebas de seguridad en desarrollo y aceptación |
| Registro y monitoreo | P2.5 | ISO/IEC 27001:2022 | 8.15 Registro de eventos; 8.16 Actividades de monitoreo |
| Gobierno de IA | P1.2 a P1.4 | ISO/IEC 42001 / NIST AI RMF | Funciones gobernar, mapear, medir y gestionar |
| Ciclo de vida | P2.1 | ITIL 4 | Prácticas de gestión de cambios y de despliegue |
