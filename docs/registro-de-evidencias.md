# Registro de evidencias y clasificación de información

**Estado:** obligatorio para la versión publicable del PETI  
**Versión:** 1.0 — septiembre de 2026  
**Propietario del registro:** Equipo de Arquitectura y Gobernanza de TI

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
| PUB-001 | Público | [EQT Completes Acquisition of Perficient](https://www.perficient.com/news-room/news-releases/2024/eqt-completes-acquisition-of-perficient), 2-oct-2024 | Perficient pasó a ser una compañía privada y dejó de cotizar en NASDAQ. | Reemplaza el uso de PRFT/SEC como condición vigente del período 2026-2028. |
| PUB-002 | Público | [Customer Security Statement](https://www.perficient.com/customer-security), consultado en sep-2026 | Certificación ISO 27001:2022, auditor A-Lign y certificado ISMS-PE-101123. | La fecha aparece como `10/11/2026`; confirmar el formato contra el certificado antes de fijar un hito. No prueba el detalle operativo de un cliente. |
| PUB-003 | Público | [Perficient's Evolved Brand](https://www.perficient.com/About/Newsroom/News-Releases/Perficients-Evolved-Brand), 26-mar-2026 | Evolución pública de marca hacia servicios y consultoría AI-native. | No demuestra adopción de una herramienta concreta en todas las células o regiones. |
| PRV-001 | Restringido | Entrevistas y notas operativas anonimizadas, 2026. | Prácticas observadas de una cuenta de cliente: roles, ALM, solicitudes de licencia y operación. | Representa una cuenta/equipo; no permite inferir una política corporativa de Perficient o de LATAM. Archivo local excluido de Git. |
| PRV-002 | Restringido | Resumen técnico anonimizado de arquitectura, 2026. | Riesgos técnicos y dependencias de un sistema de cliente. | No es evidencia de arquitectura corporativa. Debe permanecer local y no incorporarse a versiones públicas. |

## Reglas de uso en el PETI

1. Cada hecho del AS-IS debe llevar un ID del registro, su propietario y la fecha de validación.
2. Toda inferencia a escala corporativa o LATAM debe contar con evidencia de ese alcance; una evidencia de cuenta se redacta como “observado en la cuenta analizada”.
3. Las iniciativas TO-BE se etiquetan **Propuesto** hasta que exista aprobación, caso de negocio y patrocinador.
4. Antes de publicar, el responsable realiza una revisión de reidentificación: combinación de proveedor, tecnología, flujo, región, rol y fechas.
5. La exclusión por `.gitignore` previene adiciones accidentales, pero no sustituye control de acceso, cifrado o un repositorio privado para la evidencia restringida.

## Pendientes de validación

- Confirmar la fecha inequívoca de vencimiento del certificado ISO desde el documento oficial.
- Validar con Legal/Finanzas las obligaciones regulatorias aplicables tras la adquisición y privatización.
- Asignar una fuente, línea base y propietario para cada afirmación de los numerales 9, 14 y 15 del PETI.
