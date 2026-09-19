# Registro de evidencias y clasificación de información

**Estado:** obligatorio para la versión publicable del PETI  
**Versión:** 1.1 — septiembre de 2026  
**Propietario del registro:** Equipo de Arquitectura y Gobernanza de TI (equipo académico del PETI)

Este registro separa los hechos verificables de las hipótesis y propuestas del PETI. Ninguna afirmación marcada como privada debe copiarse a una versión pública sin la aprobación del propietario de la información y una evaluación de anonimización.

## Clasificación

| Marca | Uso permitido | Tratamiento |
|:---|:---|:---|
| **Público** | Puede aparecer en la versión publicable del PETI. | Conservar URL, fecha de consulta y cita directa. |
| **Interno** | Solo para el equipo del PETI. | No publicar ni compartir externamente sin aprobación. |
| **Restringido** | Entrevistas, arquitecturas, operaciones de clientes o información contractual. | Mantener fuera del repositorio versionado; citar solamente el ID de evidencia y el alcance autorizado. |
| **Propuesto** | Objetivo o decisión aún no aprobada. | No presentarlo como estado actual; indicar responsable y puerta de decisión. |

## Fuentes registradas

| ID | Clasificación | Fuente y fecha | Afirmación que puede soportar | Alcance / limitación |
|:---|:---|:---|:---|:---|
| PUB-001 | Público | [EQT Completes Acquisition of Perficient](https://www.perficient.com/news-room/news-releases/2024/eqt-completes-acquisition-of-perficient), 2-oct-2024 | Perficient pasó a ser una compañía privada y dejó de cotizar en NASDAQ. | Reemplaza el uso de PRFT/SEC como condición vigente del período 2026-2028. 19-sep-2026: no se pudo reabrir (HTTP 429); respaldada indirectamente por PUB-004. |
| PUB-002 | Público | [Customer Security Statement](https://www.perficient.com/customer-security), consultado en sep-2026 | Certificación ISO 27001:2022, auditor A-Lign y certificado ISMS-PE-101123. | La fecha aparece como `10/11/2026` sin indicar formato ni si es la de vencimiento. No prueba el detalle operativo de un cliente ni otros controles. 19-sep-2026: no se pudo reabrir (HTTP 429) y el directorio de certificados de A-LIGN no devolvió el registro. Fecha sin resolver. |
| PUB-003 | Público | [Perficient's Evolved Brand](https://www.perficient.com/About/Newsroom/News-Releases/Perficients-Evolved-Brand), 26-mar-2026 | Evolución pública de marca hacia servicios y consultoría AI-native. | No demuestra adopción de una herramienta concreta en todas las células o regiones. Reabrir antes de publicar (429 el 19-sep-2026). |
| PUB-004 | Público | [SEC EDGAR, Perficient Inc. (CIK 0001085869)](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001085869&type=&dateb=&owner=include&count=40), consultado el 19-sep-2026 | Form 8-K (2-oct-2024) de cierre de la adquisición y Form 15-12G (15-oct-2024) de terminación del registro bajo la sección 12(g); sin presentaciones posteriores. | No prueba la ausencia de otras obligaciones (deuda, contratos, otras jurisdicciones): validar con Legal/Finanzas. |
| PUB-005 | Público | [Perficient Recognized as a Microsoft AI Business Solutions Inner Circle Partner](https://blogs.perficient.com/perficient-recognized-as-a-microsoft-ai-business-solutions-inner-circle-partner/), blog de Perficient, 23-sep-2025; consultado el 19-sep-2026 | Perficient integra el "2025–2026 Microsoft AI Business Solutions Inner Circle". | Fuente de Perficient; no se abrió la página de Microsoft. No prueba renovación para 2026-2027 ni un percentil. |
| PUB-006 | Público | [Perficient Achieves Databricks Brickbuilder Specializations](https://blogs.perficient.com/perficient-achieves-databricks-brickbuilder-specializations/), blog de Perficient, 9-sep-2026; consultado el 19-sep-2026 | Cuatro especializaciones Brickbuilder de producto (Lakeflow, Security & Governance, Data Warehouse Migration, AI); Gold Partner. | Sin confirmación en página de Databricks. No prueba uso en proyectos LATAM. |
| PUB-007 | Público | [Perficient Earns Databricks Brickbuilder Specialization for Healthcare & Life Sciences](https://blogs.perficient.com/perficient-earns-databricks-brickbuilder-specialization-for-healthcare-life-sciences/), blog de Perficient, 18-feb-2026; consultado el 19-sep-2026 | Especialización Brickbuilder de industria en salud y ciencias de la vida. | Ídem PUB-006. |
| PUB-008 | Público | [Perficient Achieves Premier Partner Status with Snowflake](https://blogs.perficient.com/perficient-achieves-premier-partner-status-with-snowflake/), blog de Perficient, 5-jun-2025; consultado el 19-sep-2026 | Perficient pasó de Select a Premier Partner de Snowflake. | Estado a junio de 2025; no confirma nivel vigente en 2026 ni uso en LATAM. |
| PUB-009 | Público | [Perficient and Lovable partner](https://finance.yahoo.com/sectors/technology/articles/frontier-models-business-outcomes-perficient-153000150.html), comunicado distribuido por Business Wire, 27-may-2026; consultado el 19-sep-2026 | "Perficient to become Lovable's first enterprise implementation partner"; autodescripción 2026: "global AI and technology consulting firm… 7,000+ advisors, engineers, and designers". | Alianza anunciada con programas previstos para 2026; la primacía la declaran las partes. |
| PUB-010 | Público | [Perficient and Gradial Partner to Accelerate Agentic Marketing](https://finance.yahoo.com/technology/ai/articles/perficient-gradial-partner-accelerate-agentic-130000291.html), comunicado distribuido por Business Wire, 8-jul-2026; consultado el 19-sep-2026 | Alianza de co-innovación en marketing agéntico. | No prueba adopción en LATAM. |
| PUB-011 | Público | [Perficient Named a Major Player in IDC MarketScape Reports](https://blogs.perficient.com/2025/12/11/perficient-named-a-major-player-in-2-idc-marketscape-reports/), blog de Perficient, 11-dic-2025; consultado el 19-sep-2026 | Major Player en IDC MarketScape Worldwide Experience Build Services 2025, Experience Design Services 2025 y CX Strategy Consulting Services 2025. | Posición "Major Player", no "Leader". No se abrió el informe de IDC. |
| PUB-012 | Público | [Ley 25.326, Argentina.gob.ar](https://www.argentina.gob.ar/normativa/nacional/ley-25326-64790), consultado el 19-sep-2026 | Ley argentina de protección de datos personales (2000), vigente. | No se revisaron decreto reglamentario ni resoluciones de la AAIP. |
| PUB-013 | Público | [Gobierno propone ampliar plazo para implementar nueva Ley de Protección de Datos](https://www.economia.gob.cl/2026/09/01/gobierno-propone-ampliar-plazo-para-implementar-nueva-ley-de-proteccion-de-datos-y-institucionalidad.htm), Ministerio de Economía de Chile, 1-sep-2026; consultado el 19-sep-2026 | Propuesta de que la Ley 21.719 entre en vigencia el 1-dic-2027. | Propuesta no aprobada a la fecha de consulta; la fecha vigente (1-dic-2026) no se confirmó en BCN. |
| PUB-014 | Público | [LFPDPPP, Orden Jurídico Nacional](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo125102.html), consultado el 19-sep-2026 | Nueva ley mexicana publicada en el DOF el 20-mar-2025, vigente desde el día siguiente; abroga la de 2010; autoridad: Secretaría Anticorrupción y Buen Gobierno. | Texto compilado; no se contrastó con el DOF. |
| PUB-015 | Público | [Ley 18.331, IMPO](https://www.impo.com.uy/bases/leyes/18331-2008), consultado el 19-sep-2026 | Ley uruguaya de protección de datos (2008) y sus modificaciones (entre ellas 19.670 y 20.075). | No se revisó el decreto reglamentario. |
| PRV-001 | Restringido | Entrevistas y notas operativas anonimizadas, 2026. | Prácticas observadas de una cuenta de cliente: roles, ALM, solicitudes de licencia y operación. | Representa una cuenta/equipo; no permite inferir una política corporativa de Perficient o de LATAM. Archivo local excluido de Git. Los nombres de productos de la cuenta no se publican. |
| PRV-002 | Restringido | Resumen técnico anonimizado de arquitectura, 2026. | Riesgos técnicos y dependencias de un sistema de cliente. | No es evidencia de arquitectura corporativa. Debe permanecer local y no incorporarse a versiones públicas. |
| INT-001 | Interno | Análisis del equipo del PETI, septiembre de 2026: DOFA por dominio, objetivos corporativos formulados por el equipo, valoraciones de cubrimiento, afirmaciones de ausencia ("no se encontró en la evidencia revisada") y supuestos de costo (bajo < USD 50.000; medio USD 50.000-250.000; alto > USD 250.000, con tope de USD 1.000.000 para estimar presupuesto). | Priorización, costos relativos, objetivos corporativos e inferencias del PETI v2.x. | Elaboración propia; no es un dato de Perficient. Objetivos y costos por validar con la dirección y Finanzas. |

## Reglas de uso en el PETI

1. Cada hecho del AS-IS debe llevar un ID del registro, su propietario y la fecha de validación.
2. Toda inferencia a escala corporativa o LATAM debe contar con evidencia de ese alcance; una evidencia de cuenta se redacta como “observado en la cuenta analizada”.
3. Las iniciativas TO-BE se etiquetan **Propuesto** hasta que exista aprobación, caso de negocio y patrocinador.
4. Antes de publicar, el responsable realiza una revisión de reidentificación: combinación de proveedor, tecnología, flujo, región, rol y fechas. En el PETI, las herramientas de la cuenta analizada se nombran por categoría, no por producto.
5. La exclusión por `.gitignore` previene adiciones accidentales, pero no sustituye control de acceso, cifrado o un repositorio privado para la evidencia restringida.

## Pendientes de validación

- Confirmar la fecha inequívoca de vencimiento del certificado ISO (formulario de a-lign.com/iso-certificate o certificado PDF); mientras tanto el plan asume la más temprana (11-oct-2026).
- Existencia, tipo, periodo y alcance de un informe SOC 2 de Perficient.
- Países de la operación nearshore, industrias, líneas de servicio y página About (perficient.com respondió 429 el 19-sep-2026).
- Alianza con AWS; vigencia 2026-2027 del Microsoft Inner Circle.
- Capacitación obligatoria corporativa (periodicidad y temas).
- Fecha vigente de la Ley 21.719 de Chile en BCN.
- Validar con Legal/Finanzas las obligaciones regulatorias aplicables tras la privatización.
