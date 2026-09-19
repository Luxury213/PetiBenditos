---
name: evidencias-peti
description: Usar cuando hay que respaldar con evidencia una afirmación del PETI de Perficient (AS-IS, motivadores, contexto corporativo, certificaciones, alianzas, cifras), buscar la fuente primaria de un dato, registrar una fuente nueva en docs/registro-de-evidencias.md, clasificar información como pública, interna, restringida o propuesta, decidir si algo de las entrevistas o de la arquitectura de la cuenta puede aparecer en el PETI, hacer la revisión de reidentificación antes de compartir, o armar la sección de referencias bibliográficas.
argument-hint: "[afirmación, fuente o numeral]"
---

# Evidencia, clasificación y fuentes del PETI

## Principio

Una fuente que no se abrió no existe. Un hecho del PETI vale si tiene un ID en `docs/registro-de-evidencias.md` que apunte a una fuente abierta en una sesión, con fecha de consulta y alcance. Lo que no tiene ID es hipótesis. Esto es lo que separa un PETI defendible de un resumen de la página web de Perficient.

La segunda mitad del principio es de confidencialidad: la evidencia restringida sostiene el diagnóstico, pero no se ve en el documento. Solo se ve su ID y lo que el alcance autorizado permite decir.

## Clasificación (del registro)

| Marca | Qué es | En el PETI |
|---|---|---|
| **Público** (`PUB-`) | Fuente abierta: sitio de Perficient, comunicado, norma, página de un socio, informe de un analista | Se cita con ID; va a referencias bibliográficas |
| **Interno** (`INT-`) | Análisis del equipo del PETI (DOFA, estimaciones, supuestos de costo) | Se cita con ID como "elaboración propia"; no se comparte fuera del equipo sin aprobación |
| **Restringido** (`PRV-`) | Entrevistas, arquitectura u operación de una cuenta de cliente, información contractual | Solo el ID y el alcance autorizado; el archivo queda local y fuera de Git |
| **Propuesto** | Objetivo o decisión no aprobada | No se presenta como estado actual; responsable y puerta de decisión |

`INT-` no existe todavía en el registro; créalo con el primer análisis interno que se cite (por ejemplo, los supuestos de costo del portafolio).

## Procedimiento para respaldar una afirmación

1. **Descomponer** la afirmación en la unidad verificable ("Perficient está en el 1 % superior de socios de Microsoft" → reconocimiento, año, quién lo otorga, qué mide).
2. **Buscar si ya tiene ID** en el registro. Si lo tiene, revisa que el alcance cubra lo que el texto dice.
3. **Buscar la fuente de mayor jerarquía** (tabla siguiente) con `WebSearch` y ábrela con `WebFetch`. Los `docs/perficient_*.md` sirven solo como pista de qué buscar: sus referencias `[n]` no tienen bibliografía.
4. **Leer** el fragmento que respalda la afirmación y anotar URL, título, entidad, fecha de publicación y fecha de consulta.
5. **Clasificar** y **registrar** una fila nueva: ID, clasificación, fuente y fecha (con enlace), afirmación que puede soportar, alcance o limitación. El alcance dice también lo que la fuente **no** prueba.
6. **Reformular** la afirmación del PETI al tamaño de la evidencia. Si la fuente dice menos, el texto dice menos. Si la contradice, se reporta y se corrige el texto, nunca la fuente.

Si no hay acceso web en la sesión, entrega la afirmación con `[EVIDENCIA: qué buscar y dónde]` y no la registres.

## Jerarquía de fuentes

| Tema | Fuente preferida | Aceptable | Débil (no sostiene un hecho sola) |
|---|---|---|---|
| Datos corporativos, marca, oferta | perficient.com (newsroom, páginas corporativas, customer security) | Comunicado del adquirente o del socio | Blogs, agregadores, perfiles de LinkedIn |
| Propiedad y condición societaria | Comunicado oficial (EQT, Perficient), SEC EDGAR para lo histórico | Prensa económica de referencia | Wikipedia |
| Certificaciones | Certificado o registro del organismo (A-Lign), declaración oficial de Perficient | Página de seguridad del cliente con número de certificado | Menciones en propuestas o blogs |
| Alianzas y reconocimientos | Página del socio o del analista (Microsoft, Databricks, Snowflake, IDC) | Comunicado de Perficient | Notas de prensa pagadas |
| Operación LATAM | Páginas oficiales de Perficient LATAM | Ofertas de empleo oficiales (solo para "existe presencia en X") | Opiniones de empleados |
| Operación de la cuenta | Entrevistas y documentos del equipo (PRV) | — | Suposición a partir de la industria |
| Marcos y normas | Emisor oficial (ISO, NIST, AICPA, ISACA, The Open Group, PeopleCert, MinTIC, Función Pública) | Resumen oficial del emisor | Blogs de consultoras |

## Revisión de reidentificación (antes de compartir o publicar)

Para cada mención de la cuenta analizada o de su arquitectura, responde:

1. ¿Aparece el nombre del cliente, de un proyecto, de un sistema, de una tabla o de una persona? → se elimina.
2. ¿La combinación de **industria + proveedor + tecnología + flujo + región + rol + fecha** permitiría a alguien del sector adivinar la cuenta? → se generaliza el elemento más específico (por ejemplo, "un proveedor de nube" en lugar del servicio concreto, "2026" en lugar de la fecha).
3. ¿Se atribuye a Perficient o a LATAM algo que solo se observó en la cuenta? → se acota.
4. ¿Hay copias literales de los archivos restringidos en el PETI, en un commit, en un artefacto o en un mensaje de agente? → se retiran y se avisa.
5. ¿Algún archivo restringido dejó de estar en `.gitignore` o aparece en `git status`? → se detiene todo y se avisa.

La revisión se reporta como tabla: fragmento (sin reproducir el dato sensible), riesgo, cambio propuesto.

## Contrato de salida

Por cada afirmación trabajada:

| Campo | Contenido |
|---|---|
| Afirmación | Texto exacto del PETI |
| Estado | respaldada / parcialmente respaldada / no encontrada / contradicha / restringida |
| ID | Existente o propuesto (fila nueva para el registro) |
| Enlace | URL abierta y fecha de consulta |
| Fragmento | Cita breve o dato con su ubicación |
| Alcance | Qué prueba y qué no |
| Redacción sugerida | Oración con el ID |

Más, si se pidió registrar: las filas listas para pegar en el registro.

## Referencias bibliográficas

El PETI necesita un numeral de referencias (la plantilla lo pide). Se construye a partir de las filas `PUB-` del registro, en APA 7, con el formato de [formato-referencias.md](formato-referencias.md). Las filas `PRV-` no van a la bibliografía; se mencionan en la metodología como "entrevistas y documentación de una cuenta de cliente, anonimizadas".

## Lo que esta skill no hace

- No da por verificada una fuente que no abrió.
- No copia contenido restringido a ningún archivo versionado, ni siquiera "anonimizado a mano".
- No reemplaza la aprobación del propietario de la información para publicar algo `INT-` o `PRV-`.
