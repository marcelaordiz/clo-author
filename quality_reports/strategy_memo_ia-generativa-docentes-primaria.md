# Strategy Memo: ia-generativa-docentes-primaria

**Date:** 2026-07-28
**Paper type:** Descriptive / interpretive (qualitative) — primary type. No reduced-form, IV, RDD, or structural component. Secondary component: none (theorist agent not applicable per domain-profile.md).
**Primary analytic strategy:** Teoría de las Representaciones Sociales, enfoque estructural adaptado a datos de entrevista (Moscovici/Jodelet/Abric) + análisis temático (Braun & Clarke, 2006) como técnica de codificación subordinada al marco SRT. Complemento lexicométrico (IRAMUTEQ) para triangulación, no como método primario.

---

## Pre-Strategy Report

**Date:** 2026-07-28
**Project:** ia-generativa-docentes-primaria

### Inputs Read
**Research spec:** Not found. No `/discover interview` output exists for this project — the researcher went directly to `/discover lit`. **ASSUMED**: the research question below is reconstructed from the lit review's title, framing, and positioning statement, not from a formal spec. This is flagged as a gap; a retrospective research-spec / thesis-plan document is recommended before the writer phase so the paper's stated RQ and this memo do not silently diverge.
**Literature review:** `quality_reports/lit_review_ia-generativa-docentes-primaria.md` (loaded in full — 356 lines, 31 references).
**Data assessment:** No formal `quality_reports/data-assessment/` doc exists. Data situation described directly in the task brief (below) and treated as authoritative in place of an explorer report.
**Domain profile:** Loaded — `.claude/references/domain-profile.md` (qualitative/interpretive field profile, "Common Identification Strategies" repurposed as "Common Analytic Strategies").
**Journal profiles:** Loaded — `.claude/references/journal-profiles.md`, Education section (Computers & Education, BJET, Teaching and Teacher Education, RIE/RELIEVE/Profesorado).
**Literature sub-files:** `annotated_bibliography.md`, `frontier_map.md`, `positioning.md` all loaded from `quality_reports/literature/ia-generativa-docentes-primaria/`.

### Research Question (reconstructed — ASSUMED, no formal spec)
¿Cuál es el contenido y la estructura (núcleo central / elementos periféricos) de la representación social que construyen docentes de nivel primario en ejercicio sobre la IA generativa, para su uso en el aula y para sus propias tareas docentes (planificación, corrección, feedback, elaboración de materiales)?

### Key Findings from Literature
- The international literature on teacher perceptions of generative AI at the primary level (Calleja & Camilleri 2025; Han et al. 2024; Yu, Lee & Kim 2025) uses individual acceptance/HCI frameworks (TAM), not structural SRT, and typically covers one bounded task rather than the full aula/tareas duality.
- The only three Latin American studies combining SRT + generative AI (Arigón — Argentina, secondary; CFE Uruguay thesis — primary, framing unconfirmed; Carvalho & Corrallo — Brazil, vocational) leave a specific gap: primary + in-service + structural SRT + dual aula/tareas + Argentine context. This thesis's contribution rests on actually delivering the structural (núcleo central/periférico) analysis, not a looser "perceptions" study — this is the single biggest execution risk for the analytic strategy (see Threats §5.5 and Decision Record).
- Carvalho & Corrallo (2024) is the closest *methodological* precedent: núcleo central + free-word-association + IRAMUTEQ (classification hiérarchique descendante). Critically, **that study used a structured elicitation instrument** (free association), which this thesis's already-collected semi-structured interviews did not use — this constrains which structural-identification technique is honestly available (see §2.3).
- No saturation precedent specific to SRT-interview studies was found in the project bibliography. General qualitative-methods literature on saturation (Guest, Bunce & Johnson 2006; Hennink & Kaiser 2022) is used below as an external anchor — **flagged ASSUMED / not verified against this project's bibliography**, since it wasn't returned by the librarian's search. Recommend the librarian add a targeted saturation-methodology search in a future pass.

### Available Data
- **14 semi-structured interviews** already conducted with primary-level teachers (docentes de nivel primario en ejercicio).
- **Sampling:** convenience (access-based), NOT theoretical/purposive. This is a real, stated limitation — not glossed over (see §5.1).
- **Transcription status:** partial — some of the 14 are transcribed, some are not, at time of strategy design.
- **Coding status:** greenfield. An interview guide (protocolo de preguntas) exists and was used to conduct the interviews; no coding scheme, codebook, or analysis exists yet.
- **Known limitations:** (a) no free-association or hierarchized-evocation instrument was administered — only open/semi-structured interview questions — which constrains the technique available for identifying núcleo central formally; (b) uneven transcription depth across participants if left unresolved before coding; (c) single interview round per participant, no repeated contact — limits prolonged engagement and full member-checking; (d) likely solo-researcher thesis — limits inter-coder reliability options to partial double-coding/peer debriefing rather than full parallel coding.

### Candidate Designs (Analytic Strategies)
1. **SRT estructural (núcleo central/periférico) + análisis temático subordinado** — feasible with adaptation (qualitative centrality criteria in place of Vergès' rang×fréquence, since no free-association instrument exists). **Recommended primary strategy.**
2. **Análisis temático puro (Braun & Clarke), sin pretensión estructural** — feasible, lower risk, but **abandons the thesis's core positioning claim** (structural SRT is what differentiates it from Han et al., Yu/Lee/Kim, and the "perceptions" literature). Considered and rejected as primary; retained as the technique layer within Strategy 1.
3. **Análisis de discurso (narrativas de amenaza/herramienta/colega)** — feasible, complements Strategy 1 well for the "función simbólica/valorativa" dimension, but insufficient alone to deliver a núcleo/periférico structural claim. Considered as a secondary/triangulation lens, not primary.
4. **Análisis lexicométrico (IRAMUTEQ) como método primario** — **not feasible as primary method** given N=14 interviews (small corpus for stable Classification Hiérarchique Descendante classes); recommended only as a **complementary triangulation tool** (word-frequency, co-occurrence, similarity analysis) alongside manual coding.
5. **Teoría fundamentada (grounded theory) pura, sin anclaje SRT a priori** — feasible in principle but rejected: it would forfeit the deductive SRT scaffolding that the literature gap is built around, and would weaken, not strengthen, the positioning claim. See Decision Record for full comparison.

### Missing Inputs
- No formal research spec — RQ reconstructed and flagged ASSUMED above; recommend validating with the researcher before the writer phase.
- No formal data-assessment doc — data situation taken from the task brief directly as ground truth.
- Saturation-methodology citations not present in the project bibliography — flagged ASSUMED; recommend a follow-up librarian search specifically for "saturation qualitative interview education" and "Vergès rang-fréquence vs. approche interprétative" methodology sources.
- CFE Uruguay thesis (closest competitor by level) still unverified per the librarian's own flag — this analytic strategy does not depend on resolving that, but the final positioning language in the paper does (per `positioning.md`).

Proceeding to strategy design.

---

## 1. Estimand → Analytic Object

**What exactly is being reconstructed?**

The analytic object is **una representación social supraordinada — "la IA generativa en la práctica docente de nivel primario"** — analizada a través de **dos campos de práctica (champs de représentation)** que pueden activar el mismo núcleo de manera diferencial: (a) el uso de IA generativa **en el aula** (con y para estudiantes) y (b) el uso de IA generativa **para las tareas propias del/de la docente** (planificación, corrección, feedback, elaboración de materiales, comunicación con familias, gestión administrativa).

**Position taken (and why):** This memo treats aula and tareas-docentes as **two practice fields of a single representational object**, not as two independent social representations to be coded and reported separately from scratch. This follows Abric/Flament's own theoretical apparatus: a central core can be common across contexts of activation of the same object, while peripheral elements adapt, contextualize, and sometimes fragment across practice fields. Concretely:

- Every coded segment carries a **domain tag** (`aula` / `tareas_docentes` / `general_no_diferenciado`) in addition to thematic and structural (central-candidate / peripheral) codes.
- The analysis asks, as an explicit empirical question (not a presupposition): **is the núcleo central stable across both fields, or does it fragment into field-specific cores?** Both outcomes are reportable findings — a stable shared core across aula/tareas is itself a finding; a fragmented core is also a finding, and arguably a more interesting one given the literature gap.
- This delivers the literature's "dual coverage" contribution claim (positioning.md, axis 3) as an actual analytic result, rather than as two parallel unconnected analyses that risk reading as two separate mini-studies bolted together.

**Population:** Docentes de nivel primario en ejercicio en escuelas a las que la investigadora tuvo acceso (ver §5.1 sobre alcance/transferibilidad — explícitamente NO se reclama representatividad de "docentes de nivel primario" en general).

**Unit of analysis:** El discurso de cada docente entrevistado (n=14), segmentado en unidades de sentido (fragmentos de entrevista) codificadas según el esquema en §2.

---

## 2. Specification → Coding / Analysis Plan

### 2.1 Deductive codes (from SRT theory + literature frontier map)

| Code family | Source | Examples of codes |
|---|---|---|
| **Dimensión estructural** | Abric (2001), Moscovici (1961/1979) | `candidato_nucleo_central`, `periferico_proximo`, `periferico_lejano`, `elemento_contra-nucleo` (contra-elementos, per Flament) |
| **Función de la representación** | Abric (2001) | `funcion_organizadora` (da sentido/estructura a otros elementos), `funcion_normativa` (juicio de valor), `funcion_generadora_practicas` |
| **Componentes de la representación** | Moscovici; Jodelet (2011) | `componente_cognitivo`, `componente_afectivo_valorativo`, `componente_normativo` |
| **Marco de contraste (no-SRT)** | Davis (1989); Venkatesh et al. (2003); Mishra & Koehler (2006) | `utilidad_percibida`, `facilidad_de_uso_percibida`, `norma_social_pares`, `conocimiento_tecno-pedagogico` — coded explicitly so the thesis can *empirically* show these acceptance-style categories are subsumed within/distinct from the SRT account, not merely asserted theoretically (pre-empts referee objection #1, §6) |
| **Narrativa/valencia (from discourse-analysis literature review)** | Frontier map — "herramienta / amenaza / colega" pattern documented in Parreira et al. (2021), Ramos Ramón & Frías López (2019) | `narrativa_herramienta`, `narrativa_amenaza`, `narrativa_colega/par`, `narrativa_instrumentalista_desconectada` |
| **Discurso institucional vs. genuino** | Field-specific referee concern (domain-profile.md) | `eco_discurso_institucional` (lenguaje de capacitaciones/currículum oficial), `voz_experiencial_propia` |
| **Dominio de práctica** | Own design decision (§1) | `aula`, `tareas_docentes`, `general_no_diferenciado` |

### 2.2 Inductive codes

Applied through Braun & Clarke's (2006) six-phase thematic analysis, run as the **technique layer subordinate to the SRT framework** (not a competing method — thematic analysis produces the candidate themes; SRT theory organizes and classifies them into central/peripheral/functional categories):

1. Familiarización (lectura completa de las 14 transcripciones — ver §5.2 sobre por qué las 14 deben estar transcriptas antes de esta fase).
2. Generación de códigos iniciales (línea por línea, primeras 3-4 entrevistas, sin restricción al esquema deductivo).
3. Búsqueda de temas (agrupar códigos en temas candidatos).
4. Revisión de temas (contra el corpus completo y contra el esquema deductivo de §2.1 — fusión, división, o creación de nuevos códigos deductivos si emergen categorías no anticipadas).
5. Definición y nombramiento de temas.
6. Producción del informe — con explícita traducción de "temas" a "candidatos a elementos centrales/periféricos" vía los criterios de centralidad de §2.3.

### 2.3 From themes to núcleo central / periférico — the critical adaptation

**Honest methodological note (must appear in the thesis's methods section, not buried):** The classic technique for identifying núcleo central (Vergès' rang × fréquence, or hierarchized-evocation questionnaires, as used by Carvalho & Corrallo 2024 via free word association) requires a structured elicitation instrument that **was not administered** in these 14 semi-structured interviews. Since the data are already collected, this instrument cannot be retrofitted. The strategy therefore uses **Abric's own qualitative centrality criteria**, applied to interview discourse, as the identification procedure:

An element (theme/code) is a **candidate for the núcleo central** if it shows, across the corpus:
- **(a) Frecuencia/consensualidad:** aparece en la mayoría de las 14 entrevistas (umbral operacional: ≥ 8/14, dos tercios redondeados hacia abajo — documentar y justificar el umbral elegido).
- **(b) Fuerza connotativa/no-negociabilidad:** el/la docente lo expresa como innegociable o evidente ("no se puede pensar la IA sin...", "eso es lo que es, siempre"), no como una opinión contingente.
- **(c) Función organizadora:** el elemento estructura o le da sentido a otros elementos periféricos citados por el/la mismo/a docente (p. ej., "es una herramienta" organiza subsecuentes justificaciones sobre uso/no-uso).
- **(d) Estabilidad entre dominios:** se mantiene tanto en segmentos codificados como `aula` como en los codificados `tareas_docentes` (ver §1).

Elementos que muestran **variabilidad entre participantes, dependencia del contexto concreto, o función de protección/adaptación del núcleo frente a información disonante** se codifican como **periféricos** (próximos si aparecen con frecuencia moderada y ligados directamente al núcleo; lejanos si son idiosincráticos o anecdóticos).

**Reporting convention:** Following the hedge already used by this literature for non-Vergès designs (Ramos Ramón & Frías López 2019; and the qualitative framing implied for the CFE Uruguay thesis), results are reported as **"candidatos al núcleo central identificados mediante criterios cualitativos de centralidad (frecuencia, fuerza connotativa, función organizadora, estabilidad entre dominios)"** — not as a definitive Vergès-style structural verification. This is a deliberate, disclosed scope decision, not an oversight (see §6, objection 5, the single largest risk to the positioning claim).

### 2.4 Software / method recommendation

| Tool | Role | Justification |
|---|---|---|
| **Manual/CAQDAS coding (Atlas.ti recommended; RQDA or Taguette as free alternatives)** | **Primary.** Multi-layer coding: domain tag × deductive/inductive theme × structural classification (central-candidate/peripheral) × institutional-echo flag. | N=14 is a small qualitative N, but the coding scheme has 4+ overlapping layers per segment — a CAQDAS tool is justified not by corpus size but by coding-scheme complexity and by the audit-trail/traceability benefit for dependability (§3) and INV-22-style claim-source traceability for the eventual paper. |
| **IRAMUTEQ** | **Secondary/triangulation only.** Word-frequency, similarity analysis (analyse de similitude), simple co-occurrence maps on the transcribed corpus. | N=14 interview transcripts is a small corpus for stable Classification Hiérarchique Descendante (CHD) classes — Carvalho & Corrallo's IRAMUTEQ use was on a larger, questionnaire-based free-association corpus, a different data type better suited to CHD. Using IRAMUTEQ only for descriptive lexical signals (most frequent terms, co-occurrence around "IA"/"inteligencia artificial") provides a partial quantitative corroboration of manual centrality judgments (§2.3, criterion a) without overclaiming statistical structural validity from too small a corpus. This limitation must be stated explicitly if IRAMUTEQ output appears in the thesis. |
| **Spreadsheet (fallback only)** | Not recommended as primary given multi-layer coding complexity, but acceptable as an audit-trail export format from the CAQDAS tool for appendices. | — |

### 2.5 Pseudo-code (coding/analysis workflow — for the coder/data-engineer if any script-assisted steps are used, e.g. corpus prep for IRAMUTEQ or a coding-frequency tally)

```text
# Phase 0 — Data readiness gate (see §5.2)
IF transcribed_interviews < 14:
    HALT analysis start
    complete transcription of remaining interviews (or execute documented
    field-note fallback protocol per §5.2) before Phase 1

# Phase 1 — Familiarization
for each of 14 transcripts:
    read fully, write reflexive memo (see §3, confirmability)

# Phase 2 — Deductive + inductive coding (Atlas.ti)
codebook_v0 <- deductive_codes(section 2.1)  # seeded before coding begins
for each transcript:
    apply codebook_v0 codes where they fit
    inductively create new codes for uncoded meaningful segments
    tag every coded segment with domain in {aula, tareas_docentes, general}
    tag every coded segment with discourse_source in {experiencial, eco_institucional}
codebook_v1 <- revise(codebook_v0, emergent_codes)  # document version diff

# Phase 3 — Structural classification
for each code in codebook_v1 (thematic level):
    freq <- count(participants mentioning code) / 14
    connotative_force <- qualitative_judgment(criterion b, §2.3)
    organizing_function <- qualitative_judgment(criterion c, §2.3)
    domain_stability <- check(code appears in both aula AND tareas_docentes segments)
    if freq >= 8/14 AND connotative_force == high AND organizing_function == high:
        classify as candidato_nucleo_central
    elif freq >= 8/14 AND domain_stability == True:
        classify as candidato_nucleo_central  # criterion (d) alone can qualify, document which
    else:
        classify as periferico_proximo or periferico_lejano (per proximity to core, §2.3)

# Phase 4 — Negative case / saturation checks (see robustness plan)
run cumulative_new_codes_per_interview() -> plot/table for saturation assessment
search_explicitly for deviant cases contradicting each candidato_nucleo_central

# Phase 5 — Triangulation
export corpus_text -> IRAMUTEQ
run word_frequency, analyse_de_similitude
compare top lexical clusters against candidatos_nucleo_central from Phase 3
document agreement / disagreement explicitly

# Phase 6 — Reporting
report candidatos_nucleo_central and elementos_perifericos
   separately for: (i) corpus completo, (ii) segmentos "aula", (iii) segmentos "tareas_docentes"
report whether núcleo is STABLE or FRAGMENTED across domains (§1)
```

---

## 3. Assumptions → Rigor Criteria (Lincoln & Guba, operationalized for this study)

### Credibility
- **Statement:** Los hallazgos reflejan de manera creíble el sentido que los/las docentes entrevistados/as le dan a la IA generativa, y no un artefacto de la interpretación de la investigadora.
- **Operationalization for this study:**
  - Triangulación intra-participante entre dominios (aula vs. tareas_docentes) dentro de la misma entrevista.
  - Triangulación de método: coincidencia (o divergencia documentada) entre clasificación manual (§2.3) y señales léxicas de IRAMUTEQ (§2.4).
  - Peer debriefing: al menos una sesión de revisión del codebook y de los candidatos a núcleo central con el/la director/a de tesis, documentada con fecha y cambios resultantes.
  - Member checking parcial y factible: envío a cada uno de los 14 docentes de una síntesis de una página con sus propios fragmentos codificados y la interpretación asignada, solicitando confirmación o corrección — factible dado N=14 y bajo costo de tiempo por participante (a diferencia de una revisión de transcripción completa, que no se propone por carga de tiempo).
  - Análisis de casos negativos/desviantes (ver Robustness Plan, Prioridad 1).
- **Testable implication:** Documentar explícitamente cuántos casos negativos se encontraron y cómo se resolvieron (¿matizaron el núcleo? ¿lo confirmaron por exclusión?).

### Transferability
- **Statement:** Los lectores pueden juzgar a qué otros contextos se transfieren estos hallazgos, sin que la investigadora reclame representatividad estadística.
- **Operationalization:** Tabla de descripción densa (thick description) de los 14 participantes: años de antigüedad, tipo de escuela (pública/privada), grado/ciclo a cargo, exposición previa a IA generativa (nula/exploratoria/habitual), infraestructura TIC de la escuela, ubicación (urbana/suburbana). Declaración explícita en el texto: "los hallazgos se transfieren a docentes con perfiles y contextos institucionales similares a los descritos en la Tabla X; no se reclama representatividad del universo de docentes de nivel primario" (ver §5.1).

### Dependability
- **Statement:** El proceso de análisis es sistemático, documentado y, en principio, auditable por otro/a investigador/a.
- **Operationalization:** Historial de versiones del codebook (v0 deductivo → v1, v2... con fecha y justificación de cada cambio) exportado desde Atlas.ti; protocolo de entrevista (guía) incluido como apéndice; bitácora de decisiones analíticas (memo qualitativo por cada sesión de codificación).

### Confirmability
- **Statement:** Los hallazgos están anclados en los datos y no únicamente en las predisposiciones de la investigadora.
- **Operationalization:** Reflexividad explícita (ver abajo); memos analíticos con fecha; auditoría de codificación parcial (ver Robustness Plan, Prioridad 3); cita textual (verbatim) de al menos un fragmento por cada candidato a núcleo central y por cada elemento periférico reportado, para que el lector pueda evaluar la inferencia.

### Reflexivity Plan
La investigadora debe redactar, antes de comenzar la codificación formal, una declaración de reflexividad que incluya explícitamente:
1. Su propia postura/uso previo de IA generativa (docente investigadora vs. investigadora externa al campo — aclarar el vínculo institucional con las escuelas de acceso, dado el muestreo por conveniencia).
2. Expectativas previas sobre lo que esperaría encontrar (para poder contrastarlas post-hoc con lo hallado y detectar confirmación motivada).
3. Relación previa con los/las docentes entrevistados/as (colegas, conocidos, terceros) — relevante tanto para deseabilidad social (§5.3) como para credibilidad.
Esta declaración se actualiza (memo) durante el proceso de codificación, no solo se escribe una vez al inicio.

---

## 4. Robustness Plan → Qualitative Equivalent

See companion file `quality_reports/strategy/ia-generativa-docentes-primaria/robustness_plan.md` for the full ordered table. Summary, most-threatening-first:

1. **Saturation assessment at N=14** — cumulative new-themes-per-interview curve; report explicitly whether code saturation (likely, per Guest et al. 2006/Hennink & Kaiser 2022 — ASSUMED, unverified against this project's bibliography) vs. meaning saturation (less likely at N=14) was reached, and scope claims accordingly.
2. **Negative/deviant case analysis** for every candidato a núcleo central.
3. **Representación vs. opinión individual** — explicit coding rule (frequency + social-anchoring language) to exclude idiosyncratic single-participant statements from central-core candidacy.
4. **Discurso institucional vs. genuino** — flag and compare núcleo candidates with/without segments coded `eco_discurso_institucional` included.
5. **Partial double-coding / peer debriefing** — 3–4 of 14 transcripts double-coded by the thesis advisor (or a second reader), percent agreement or informal concordance reported.
6. **Manual coding vs. IRAMUTEQ lexical triangulation** — agreement/disagreement documented explicitly, not silently reconciled.
7. **Sensitivity to the transcription-completeness gate** — if any field-note-only data ends up in the analytic sample (fallback scenario, §5.2), report core/peripheral classification separately for the fully-transcribed subsample vs. the full N=14, and flag any element whose classification depends on including the lower-granularity subsample.
8. **Domain-stability check (aula vs. tareas_docentes)** — already central to the design (§1), reported as its own robustness dimension: is the núcleo the same across domains?

---

## 5. Threats / Limitations (addressed explicitly, not papered over)

### 5.1 Convenience sampling → transferability limits
Not theoretical/purposive sampling. Response: thick description table (§3, Transferability) + explicit non-generalization statement in the paper + reporting sample heterogeneity that does exist (years of experience, school type, prior AI exposure) as a partial substitute for designed heterogeneity, so readers can see the actual range covered even though it wasn't sampled by design.

### 5.2 Partial transcription — position taken
**Recommendation: complete transcription of all 14 interviews before starting formal coding (Phase 1).** Rationale: mixing verbatim-transcribed segments with lower-granularity field-note-coded segments would introduce a **systematic depth-of-evidence confound between participants** — a participant coded only from field notes would mechanically show fewer/thinner peripheral elements, which could be mistaken for a genuine representational difference rather than a data-quality artifact. This directly threatens Assumption 3 (Dependability) and Assumption 1 (Credibility).

**If time genuinely does not allow completing all 14 transcriptions before the thesis deadline**, the documented fallback is:
- Transcribe verbatim at minimum the segments used as direct quotes in the final report, for every participant.
- For untranscribed interviews, produce **detailed structured field notes within 48 hours of the interview** (not relying on memory at analysis time), coded at the *thematic* level only (not attempting fine-grained central/peripheral connotative-force judgments, which require verbatim wording).
- Explicitly report, in the methods section, which participants' data came from full transcripts vs. structured field notes, and run the Priority-7 robustness check (§4) comparing results with/without the field-note-only subsample.
This fallback is a documented compromise, not a preferred design choice — the primary recommendation remains full transcription first.

### 5.3 Social-desirability bias
Docentes pueden minimizar rechazo o desconocimiento de la IA generativa frente a la entrevistadora. Mitigation: (a) en el reporte de hallazgos, distinguir explícitamente entre lo que el/la docente *declara hacer* y ejemplos *concretos y recientes* que relata (las declaraciones generales de aceptación son más vulnerables a deseabilidad que los relatos de episodios específicos — priorizar estos últimos como evidencia de mayor peso para candidatos a núcleo central); (b) declarar la limitación explícitamente en la sección de limitaciones del paper, sin pretender haberla eliminado; (c) si la guía de entrevista ya usada incluye preguntas indirectas ("¿qué dirían tus colegas...?"), aprovecharlas como una fuente de datos con menor carga de deseabilidad social — revisar la guía existente para identificar si estas preguntas están presentes y ponderarlas en consecuencia durante la codificación.

### 5.4 Representación social genuina vs. opinión/actitud individual
Ver regla de codificación en §2.3 y §4.3: solo elementos con anclaje social (frecuencia + lenguaje de generalización — "se dice", "en general los docentes...", "todos pensamos") califican como candidatos al núcleo; enunciados idiosincráticos de un solo participante se codifican como opinión individual y se excluyen de la clasificación estructural (aunque pueden reportarse como casos periféricos o desviantes interesantes).

### 5.5 Distinción entre discurso institucional y representación genuina (mayor riesgo metodológico, ver también §6.5)
Ver `eco_discurso_institucional` en §2.1. Riesgo: que la "representación docente" reportada sea en realidad una repetición del discurso oficial de capacitaciones/currículum sobre IA en la escuela, no una construcción genuina de sentido de los/las docentes. Mitigation: coding explícito de segmentos que citan o parafrasean lenguaje institucional/normativo vs. lenguaje experiencial propio; comparar núcleo candidato con y sin estos segmentos (Robustness Plan #4); si el núcleo colapsa al excluir el discurso institucional, esto es en sí mismo un hallazgo relevante para el paper (sugiere una representación aún poco autónoma, un hallazgo sustantivo, no solo un problema de método).

---

## 6. Referee Objection Anticipation (Top 5)

Drawing from `.claude/references/domain-profile.md` (Field-Specific Referee Concerns) and the Education section of `.claude/references/journal-profiles.md` (Teaching and Teacher Education; BJET; Computers & Education; RIE/Profesorado).

1. **"¿Por qué representaciones sociales y no simplemente actitudes/percepciones?"** (domain-profile.md; Teaching and Teacher Education profile: "Is this a representation, an attitude, or a belief — and does the paper distinguish them?")
   - **Response:** Marco teórico dedica una subsección explícita al contraste SRT vs. TAM/UTAUT/TPACK (Davis 1989; Venkatesh et al. 2003; Mishra & Koehler 2006), y el esquema de codificación (§2.1) codifica *empíricamente* categorías de tipo "aceptación" (utilidad percibida, facilidad de uso) para mostrar cómo se relacionan con o se subsumen en la estructura núcleo/periférico — no se trata solo de una defensa teórica declarativa.
   - **Pre-planned analysis:** Reportar explícitamente si los elementos de tipo "aceptación individual" aparecen como periféricos (contextuales, variables entre docentes) mientras que el núcleo muestra un carácter más colectivo/normativo — esa distinción empírica es la respuesta más fuerte a esta objeción.

2. **"¿Cómo se garantiza la fiabilidad de la codificación?"** (domain-profile.md; BJET profile)
   - **Response:** Auditoría documentada (codebook versionado con fechas), peer debriefing con director/a de tesis, doble codificación parcial de 3–4 entrevistas.
   - **Pre-planned analysis:** Reportar el nivel de acuerdo (aunque sea informal/porcentual, dado N pequeño de doble codificación) y cualquier revisión del codebook que resultó de discrepancias.

3. **"Tamaño y composición de la muestra — muestreo por conveniencia"** (domain-profile.md; BJET: "How were teachers selected? What is transferable beyond this specific school context?")
   - **Response:** Reconocimiento explícito y sin eufemismos del muestreo por conveniencia; tabla de descripción densa; declaración de alcance de transferibilidad acotada; contextualizar N=14 frente a precedentes comparables de tamaño similar en la literatura (Han et al. 2024, 16 entrevistas docentes) para normalizar el N en estudios cualitativos de este tipo, sin usar esa comparación para exagerar la solidez del muestreo (que sigue siendo por conveniencia, no intencional).
   - **Pre-planned analysis:** Reportar explícitamente la curva de saturación (§4, Robustness #1) como evidencia de que N=14, aunque no sea muestreo teórico, alcanzó al menos saturación de códigos.

4. **"Sesgo de deseabilidad social"** (domain-profile.md; BJET: "Is there a risk of social-desirability bias in teacher self-report on AI use?")
   - **Response:** Ver §5.3. Declarar la limitación explícitamente; priorizar episodios concretos relatados sobre declaraciones generales de actitud como evidencia de mayor peso.

5. **"¿Esto es realmente un análisis estructural (núcleo central/periférico) o es, en el fondo, análisis temático con otro nombre?"** (implícito en Computers & Education / Teaching and Teacher Education: exigencia de que el análisis vaya "beyond descriptive opinion into a genuine social-representations account"). **Este es el riesgo metodológico más grande de todo el diseño** (ver Decision Record, "Risks and Mitigations").
   - **Response:** Transparencia total sobre la adaptación metodológica (§2.3): no se usó instrumento de asociación libre/evocación jerarquizada (Vergès), por lo que la identificación de núcleo central se basa en criterios cualitativos de centralidad (frecuencia, fuerza connotativa, función organizadora, estabilidad entre dominios), no en el método cuantitativo clásico. Esta decisión se declara explícitamente en la sección de métodos, no se oculta ni se disfraza de análisis estructural pleno.
   - **Pre-planned analysis:** Usar la triangulación con IRAMUTEQ (§2.4, §4) como corroboración parcial y cuantitativa de los candidatos a núcleo central identificados cualitativamente, y usar lenguaje hedged y consistente ("candidatos al núcleo central") en todo el manuscrito, replicando la convención ya usada por antecedentes similares sin instrumento estructurado (Ramos Ramón & Frías López 2019).

---

## 7. Relationship to the Literature Review's Positioning Claim — Delivery Check

`positioning.md` claims the thesis delivers: (a) SRT estructural explícita (núcleo central/periférico), (b) docentes de primaria en ejercicio, (c) IA generativa específicamente, (d) cobertura dual aula/tareas docentes, (e) contexto argentino.

| Positioning axis | Delivered by this strategy? | How |
|---|---|---|
| (a) SRT estructural | **Partially, with disclosed adaptation** | §2.3 qualitative centrality criteria + IRAMUTEQ triangulation, reported with hedged "candidatos al núcleo" language — NOT a full Vergès-style verification. **Recommend softening the positioning.md contribution statement** from "reconstrucción explícita de núcleo central" to "identificación de candidatos al núcleo central mediante criterios cualitativos de centralidad, triangulados lexicométricamente" — flag this to the writer for the final manuscript's framing. |
| (b) Primaria en ejercicio | Yes | Sample as described in the task brief. |
| (c) IA generativa específica | Yes | Interview guide and coding scheme both genAI-specific (not general TIC/IA). |
| (d) Cobertura dual aula/tareas | Yes, and strengthened | §1 treats this as an empirical question (stable vs. fragmented core across domains), not just parallel double-coding — this is a sharper contribution than simply "we coded both." |
| (e) Contexto argentino | Yes | By construction (UNSAM, sample location). |

**Action item for the writer/strategist-critic:** axis (a) is the one place where the analytic strategy, if not paired with the disclosed-hedge language above, could cause the positioning claim to overclaim relative to what N=14 semi-structured interviews (no elicitation instrument) can actually support. This must be resolved in the writing phase, not glossed over.

---

## Secondary Analyses

### Heterogeneity (descriptive, not causal)
- Docentes con exposición previa a IA generativa (habitual/exploratoria) vs. sin exposición previa — ¿el núcleo central difiere?
- Docentes de escuela pública vs. privada, si la heterogeneidad de la muestra lo permite (documentar en la tabla de descripción densa, §3).

### Mechanism / Interpretive Depth
- Función organizadora de las narrativas herramienta/amenaza/colega (§2.1) como mecanismo interpretativo de cómo los elementos periféricos se generan a partir del núcleo.
- Comparación explícita con el patrón "instrumentalista/desconectada" documentado en Ramos Ramón & Frías López (2019) para TIC pre-genAI: ¿se repite el mismo patrón representacional con IA generativa, o aparece algo cualitativamente distinto?
