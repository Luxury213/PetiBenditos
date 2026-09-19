# PetiBenditos

Plan Estratégico de Tecnologías de la Información (PETI) 2026-2028 de **Perficient Inc.** para su operación nearshore de Latinoamérica. Es un trabajo académico de Gobierno de TI que aplica la metodología del MinTIC de Colombia (Guía MGGTI.GE.ES.03 v3.0, plantilla PETI y herramientas de construcción) a una empresa privada.

> **Estado documental:** borrador de trabajo (v2.1, septiembre de 2026). La versión publicable solo puede usar evidencia clasificada como pública y validada en el [registro de evidencias](docs/registro-de-evidencias.md).

## Entregables del Primer Parcial

| Documento | Descripción |
|---|---|
| [PETI_Perficient_2026-2028_v2.1.docx](docs/PETI_Perficient_2026-2028_v2.1.docx) | **Entregable 1 (PETI vigente)** en Word, con los estilos de la plantilla del MinTIC. Al abrirlo, actualizar el índice (clic derecho > Actualizar campo) |
| [perficient_peti_v2_2026_2028.md](docs/perficient_peti_v2_2026_2028.md) | Fuente en Markdown del v2.1: 16 numerales según la plantilla, 18 brechas, 30 proyectos en 4 fases, 16 indicadores con hoja de vida, 11 riesgos |
| [Informe_Ejecutivo_Lineamientos_IA_USC.docx](docs/Informe_Ejecutivo_Lineamientos_IA_USC.docx) | **Entregable 3 (Informe Ejecutivo IA USC)** en Word formal, basado en la Circular Normativa DGI No. 001 de 2025 |
| [informe_ejecutivo_lineamientos_ia_usc.md](docs/informe_ejecutivo_lineamientos_ia_usc.md) | Fuente en Markdown del Informe Ejecutivo de Lineamientos de IA para la USC |
| [PETI_Perficient_Colombia_2026-2028_v1.0.docx](docs/PETI_Perficient_Colombia_2026-2028_v1.0.docx) | Versión alternativa enfocada exclusivamente en Colombia (fuente: [perficient_peti_colombia_2026_2028.md](docs/perficient_peti_colombia_2026_2028.md)) |
| [perficient_peti_plan_estrategico_2026_2028.md](docs/perficient_peti_plan_estrategico_2026_2028.md) | Versión 1.1 (histórica), estructurada sobre el referente de MinCiencias |
| [registro-de-evidencias.md](docs/registro-de-evidencias.md) | Fuentes con ID (`PUB-`, `INT-`, `PRV-`), clasificación, alcance y reglas de uso |

Para regenerar el Word después de editar el Markdown:

```
python .claude/skills/guia-peti/scripts/md_a_docx.py docs/perficient_peti_v2_2026_2028.md docs/PETI_Perficient_2026-2028_v2.1.docx
```

## Norma y referencias

| Rol | Documento |
|---|---|
| Metodología | `docs/MGGTI.GE.ES.01 - Guia de construccion PETI - Gobierno Digital-v. 3.0.pdf` (el código interno del documento es MGGTI.GE.ES.03) |
| Estructura | `docs/Anexo 2. Plantilla PETI.docx` |
| Formatos por actividad | `docs/Anexo 1. Herramientas_para_la_construccion_del_PETI.xlsx` |
| Referente del profesor | `docs/Plan-Estratégico-de-Tecnologías-de-la-Información_2025-V02.pdf` (PETI de MinCiencias 2023-2026) |
| Referente del profesor | `docs/articles-274095_recurso_1.pdf` (PETI del MinTIC) |

## Insumos de investigación

`docs/perficient_*.md`: resúmenes sobre la empresa (oferta, alianzas, seguridad, marcos de gobierno, reporte financiero histórico, propuesta de arquitectura). Sus citas numéricas `[n]` no tienen bibliografía; sirven para saber qué buscar, no como fuente de un hecho del PETI.

## Manejo de información

- Los insumos de entrevistas y de arquitectura de cliente son **restringidos**: permanecen locales, excluidos de Git, y no se listan ni se enlazan desde la documentación.
- Anonimizar los nombres no basta para publicar una arquitectura: las combinaciones de tecnologías, flujos y comportamientos también pueden reidentificar una cuenta.
- Antes de compartir el PETI, cada afirmación de la situación actual se valida por su ID de evidencia, su alcance, su propietario y su fecha de verificación.

## Trabajo con Claude Code

`.claude/` contiene el contexto del proyecto y las herramientas de apoyo:

- Skills: `guia-peti` (norma del MinTIC y scripts de extracción y de exportación a Word), `redaccion-peti` (estilo), `evidencias-peti`, `marcos-referencia`, `trazabilidad-peti` (con script de verificación), `/auditar-peti` y `/commit`.
- Agentes: `auditor-conformidad`, `auditor-evidencias`, `verificador-fuentes`.
