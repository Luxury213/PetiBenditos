# Auditoría del PETI v2.0 (2026-09-19)

Alcance: `docs/perficient_peti_v2_2026_2028.md` v2.0, registro de evidencias, README. Agentes: `auditor-conformidad` (39 hallazgos: 5 altos, 20 medios, 14 bajos), `auditor-evidencias` (28: 4 críticos, 9 altos, 11 medios, 3 bajos), `verificador-fuentes` (21 verificaciones; perficient.com respondió HTTP 429). Script de trazabilidad: 7 hallazgos antes, 1 bajo informativo después.

Veredicto: requería correcciones. Se aplicaron en la v2.1 salvo lo listado como pendiente.

## Hallazgos consolidados y estado

| ID | Sev. | Hallazgo | Origen | Estado |
|---|---|---|---|---|
| AUD-01 | Crítica | Repositorios remotos públicos cuyo historial contiene insumos derivados de la evidencia restringida y la v1.1 con la huella de herramientas de la cuenta | AE-01, AE-02 | **Pendiente: decisión del usuario** (poner repos en privado, avisar al propietario, reescribir historial) |
| AUD-02 | Crítica | La v2.0 nombraba las herramientas de la cuenta analizada, combinación que permite acotar el cliente | AE-03, AE-04, AE-24 | Corregido: categorías genéricas y nota en §2.3 |
| AUD-03 | Alta | P1.1 terminaba después del posible vencimiento ISO; BRE-006 "por confirmar" | AC-01, AE-19 | Corregido: mes 0, contingencia, hito "decisión antes del 2026-10-11", R02 probabilidad alta |
| AUD-04 | Alta | El PETI lo aprobaba un comité inexistente | AC-02 | Corregido: constitución del Comité Directivo como condición previa (§13.3) |
| AUD-05 | Alta | Metas e indicadores incoherentes; KPI-07 con "no conformidades" SOC 2 | AC-03, AC-05, AC-16 | Corregido: METI01-16 ↔ KPI-01-16; KPI-13 para SOC 2 |
| AUD-06 | Alta | Catálogo de proyectos y brechas sin columnas del Anexo 1 | AC-04, AC-18 | Corregido: dominio, meta, inicio, proceso, dominio único |
| AUD-07 | Alta | Afirmaciones atribuidas a PRV-001 que no contiene, o contradichas por ella; alianzas y datos corporativos sin ID | AE-06 a AE-10, AE-14 a AE-18 | Corregido con PUB-004 a PUB-015 o marca [EVIDENCIA] |
| AUD-08 | Alta | Documento presentado como oficial de Perficient | AE-11, AC-23 | Corregido: equipo académico declarado |
| AUD-09 | Media | Alcance contradictorio con infraestructura del cliente | AE-12, AC-10 | Corregido: §2.2, R11, KPI-02 acotado |
| AUD-10 | Media | Dependencias y calendarios (P1.4, P1.5, P4.1, R07) | AC-07 a AC-09 | Corregido: P1.9, dependencias, P4.1 meses 13-24 |
| AUD-11 | Media | Hallazgos sin brecha; capacidades de TI; calificación de seguridad; presupuesto y priorización | AC-11 a AC-17 | Corregido: BRE-016-018, §6.1.4, §6.7, §9.4, criterios |
| AUD-12 | Media | Referencias incompletas | AC-25, AE-28 | Corregido: §15 ampliado |
| AUD-13 | Baja | Varios de forma y consistencia | AC-26 a AC-39 | Corregidos |

## Pendientes

1. AUD-01 (decisión del usuario).
2. Fecha y tipo de fecha del certificado ISO/IEC 27001 (formulario de A-LIGN o certificado PDF).
3. SOC 2: existencia, periodo y alcance.
4. Reabrir perficient.com (429): PUB-001, PUB-002, PUB-003, países LATAM, About, industrias, servicios, capacitación, AWS.
5. Chile: fecha vigente de la Ley 21.719 en BCN.
6. Validar con la dirección y Finanzas los objetivos corporativos y los supuestos de costo (INT-001).
