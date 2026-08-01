# Pseudo-Code: Coding/Analysis Workflow — ia-generativa-docentes-primaria

**Paper type:** Descriptive/interpretive (qualitative), Grounded Theory. This is specification-level pseudo-code for the coding and category-development workflow, not a statistical estimation script. REBUILT 2026-07-28 — supersedes the version built for the discarded Abric-structural design. See `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md` §2 for full justification of each step.

**Revision 2 (2026-07-28) — fix per strategist-critic round 1, Issue 2.1 (MAJOR):** Phase 3 below uses "Eje A-D," this memo's own analytic coding axes derived from the 5 objetivos específicos. These are **not** the same as the guión de entrevista's own, explicitly-named "cuatro ejes de análisis" (representaciones sobre la IAG en educación; preocupaciones y expectativas; concepciones sobre el potencial pedagógico; usos proyectados en propuestas didácticas), stated verbatim in the thesis plan (p. 12) and the Ateneo (§2). See strategy memo §1.0 for the full reconciliation and crosswalk between the two structures. The methods section of the eventual paper describes the interview guide using the real, verbatim guión ejes; "Eje A-D" below is this analysis's own coding-scheme layer, not a restatement of the guión.

**Revision 3 (2026-08-01) — mid-analysis codebook expansion, 5th núcleo (matches strategy memo Revision 4):** Phase 2's `codebook_v0` dict below is extended with 3 new deductive codes under `nucleo4` (`imaginario_inevitabilidad_tecnologica`, `imaginario_desigualdad_estructural`, `imaginario_rol_docente_futuro` — content codes, distinct from the provenance codes already in `nucleo4`) and a new `nucleo5` key (`criterio_sentido_pedagogico`, `criterio_contextual_grupo`, `uso_iai_apoyo_administrativo`, `tension_autoria_impronta`), proposed by the researcher after exploratory coding of P2. Source of truth for exact code wording: `quality_reports/strategy/ia-generativa-docentes-primaria/codebook_v0_manual.md`. Phase 5's per-núcleo forcing check is extended to iterate over núcleos 1-5. The "Castañeda et al. (2025)" citation invoked for 3 of the new codes was initially `% UNVERIFIED` (not in `Bibliography_base.bib`) and has since been verified and added to the bibliography within this same revision (2026-08-01) — see strategy memo §2.1 for the full reference and Decision Record Alternative 8/Key Assumption A7 for the resolution history.

---

## Phase 0 — Data Readiness Gate

```text
transcribed_n <- count(interviews with usable transcription, out of 14-15 completed)
protocol_coverage_log <- for each interview, record which of the 7 blocks were administered

IF transcribed_n < completed_n:
    STATUS <- "GATE NOT CLEARED"
    ACTION <- complete remaining transcriptions, or document a field-note fallback
              (verbatim quotes minimum for cited fragments; structured field notes
              within 48h for the rest; flag data-source type per participant)
ELSE:
    STATUS <- "GATE CLEARED — proceed to Phase 1"

# This gate is mandatory regardless of theoretical framework — carried forward
# unchanged from general qualitative-data-readiness practice.
```

## Phase 1 — Build the Light Imaginaries Reference Corpus (once, before interview coding)

```text
reference_docs <- [
    "Guía para la integración de las inteligencias artificiales en educación (2025, PaideIA)",
    "Educ.ar (2025) - IA y educación. Usos y representaciones de la comunidad educativa"
]

marker_list_v0 <- close_read(reference_docs, mode="single_pass, not exhaustive line coding")
# Extract 10-20 recurring discursive markers of the official/national imaginary
# e.g., "aprendizaje personalizado", "acompañamiento docente" (not replacement),
# "uso responsable/ético", "necesidad de formación/capacitación",
# "brecha de formación", "integración progresiva", "eficiencia"

log(marker_list_v0, source_document, source_location)  # auditable from the start
# marker_list is a living instrument — refined in Phase 3 as interview coding reveals
# echoes not anticipated in this first pass. Document every addition with its trigger.
```

## Phase 2 — Familiarization + Deductive/Inductive Coding (interviews)

```text
codebook_v0 <- {
    # Núcleo 1 — SRT clásica (Moscovici/Jodelet)
    nucleo1: [objetivacion_imagen_concreta, anclaje_tecnologia_previa, anclaje_figura_humana],

    # Núcleo 2 — Aprendizaje significativo (Ausubel)
    nucleo2: [potencia_integracion_sustantiva, limita_integracion_sustantiva,
              adaptacion_saberes_previos],

    # Núcleo 3 — Alfabetización digital docente (Lankshear & Knobel)
    nucleo3: [competencia_tecnica_declarada, competencia_critica_reflexiva,
              relacion_no_lineal_competencia_representacion],  # explicit non-causal rule

    # Núcleo 4 — Imaginarios sociotécnicos (activo)
    nucleo4: [eco_discurso_institucional, voz_experiencial_propia,
              # ^ provenance codes (discursive origin: institutional echo vs. lived experience)
              imaginario_inevitabilidad_tecnologica, imaginario_desigualdad_estructural,
              imaginario_rol_docente_futuro],
              # ^ content codes (added 2026-07-31, Revision 3/strategy-memo-Revision-4) —
              #   what is represented as inevitable/unequal/role-transforming; can coexist
              #   with the provenance codes above on the same segment (see strategy memo §2.4 Step 2c)
    nucleo4_optional_inductive: [eco_imaginario_mercantil_mediatico],  # add only if it emerges

    # Núcleo 5 — Concepciones sobre diseño didáctico y uso pedagógico de la IAG
    # (added 2026-07-31/08-01, researcher-proposed after exploratory coding of P2;
    #  see strategy memo §2.1 for why this is kept separate from nucleo2: nucleo2 is about
    #  the STUDENT's learning, nucleo5 is about the TEACHER's planning/design decisions)
    nucleo5: [criterio_sentido_pedagogico, criterio_contextual_grupo,
              uso_iai_apoyo_administrativo, tension_autoria_impronta],

    # Cross-cutting / structural tags (not a theoretical núcleo, needed for analysis integrity)
    meta: [protocol_block_source (1-7), provenance_flag (deductivo|inductivo, dated)]
}
# NOTE (resolved 2026-08-01): 3 of the codes above (imaginario_desigualdad_estructural,
# uso_iai_apoyo_administrativo, tension_autoria_impronta) cite "Castañeda et al. (2025)" per
# the researcher's own codebook notes. This citation was initially NOT in Bibliography_base.bib
# and flagged UNVERIFIED; the researcher subsequently shared the full text and it has been
# verified and added to Bibliography_base.bib as `Castaneda2025_beyond_tools_power_structures`
# (strategy memo §2.1 has the full reference). Citable now.

for interview in corpus (n = 14-15, in the order coded):
    read(interview, full=True)
    write_reflexive_memo(interview, includes_2024_prior_study_expectation_check=True)
    # ^ mandatory per strategy memo §3, Reflexivity — not optional

    apply(codebook_v0, interview)                       # deductive pass
    new_codes <- inductive_open_coding(interview)         # line-by-line, GT open coding
    for each coded segment:
        tag(protocol_block_source)                       # mandatory — feeds §6.1 coverage caveat
        tag(nucleo4, against=marker_list_v0)              # eco_institucional vs voz_propia
        if segment_looks_like_marketing_or_media_echo AND not in marker_list_v0:
            flag_candidate("eco_imaginario_mercantil_mediatico")  # inductive addition, see Phase 1

codebook_v1 <- merge(codebook_v0, new_codes)
log_version_diff(codebook_v0, codebook_v1, date, rationale)   # Dependability audit trail

# RETROACTIVE RE-CODING (Revision 3/strategy-memo-Revision-4, mandatory — still open as of this
# revision, see Decision Record risk table):
# any interview coded BEFORE 2026-07-31 (e.g., P1) must be revisited against the
# expanded nucleo4 (3 new codes) and nucleo5 (4 new codes) — the expansion applies
# retroactively, not only prospectively. Log which interviews were coded against the
# 4-núcleo scaffold vs. the 5-núcleo scaffold, and when each was re-coded.
for interview in corpus where coded_date < 2026-07-31:
    reapply(codebook_v1.nucleo4_new_codes + codebook_v1.nucleo5, interview)
    log_recoding(interview, date, codes_added)
```

## Phase 3 — Constant Comparison + Axial Category Development

```text
for each code in codebook_v1:
    compare(code, all_previously_coded_segments)
    revise(code)  # merge, split, rename as warranted — not a one-pass tally

# "Eje A-D" below = this memo's own analytic coding axes (strategy memo §1 table),
# derived from the 5 objetivos específicos — NOT the guión de entrevista's own four
# "ejes de análisis" (representaciones / preocupaciones-expectativas / concepciones del
# potencial pedagógico / usos proyectados, verbatim thesis plan p.12 & Ateneo §2).
# See strategy memo §1.0 for the full reconciliation crosswalk before using this
# labeling in any writer-facing output. As of strategy memo Revision 4, Axis D's "usos"
# half is additionally seeded by nucleo5 (previously covered only by open/inductive coding).
axial_categories <- group_related_codes(codebook_v1, guided_by=[
    "Eje A: competencias digitales <-> representación",
    "Eje B: conocimientos previos <-> representación del potencial",
    "Eje C: preocupaciones/expectativas",
    "Eje D: concepción IAG-aprendizaje significativo + usos proyectados en propuestas didácticas
             (usos half now seeded by nucleo5, strategy memo §1.0/§2.1)"
])
# NOTE: no aula/tareas_docentes domain axis — explicitly dropped, see strategy memo §6.2

for each axial_category:
    actively_search(corpus, for="counter-instances / negative cases")
    document(deviant_cases, resolution)
```

## Phase 4 — Objetivación Anchor (Bloque 3, Pregunta 1) — Privileged Analysis

```text
for interview in corpus:
    if block_3_q1_administered(interview):
        first_spontaneous_metaphor <- extract(interview, block=3, question=1)
        code(first_spontaneous_metaphor, family="nucleo1.objetivacion_imagen_concreta",
             note="privileged/unprompted elicitation moment — treat as higher-weight evidence")

report_table(participant_id, first_spontaneous_metaphor)  # standalone table for the paper
```

## Phase 5 — Theoretical Sensitivity vs. Forcing Check

```text
for each nucleo in [1, 2, 3, 4, 5]:  # updated Revision 3/strategy-memo-Revision-4 (was [1,2,3,4])
    n_codes <- count(distinct codes under nucleo)
    n_counter_instances <- count(actively-sought counter-instances under nucleo)
    if n_codes <= 1 and elaboration_is_thin:
        report("este eje aparece subdesarrollado en el corpus", reason_hypothesis)
        # Do not pad the write-up to make all five núcleos appear equally rich
    if nucleo == 5:
        # nucleo5 was added mid-analysis (after P2) — confirm retroactive re-coding
        # of interviews coded before 2026-07-31 was actually completed (Phase 2 note)
        confirm(retroactive_recoding_completed=True)
```

## Phase 6 — Saturation Assessment

```text
running_new_codes <- []
for i, interview in enumerate(corpus, start=1):
    running_new_codes[i] <- count(codes/properties first appearing in interview_i)
plot_or_tabulate(running_new_codes)  # code-level saturation curve

for each axial_category:
    theoretical_saturation[axial_category] <- (
        "reached" if last 2-3 interviews added no new PROPERTIES/RELATIONSHIPS
        else "not clearly reached"
    )
report(code_level_saturation, theoretical_saturation, per axial_category, explicitly and honestly)
```

## Phase 7 — Institutional-Echo Sensitivity (imaginaries guardrail)

```text
for each axial_category or key finding involving nucleo4:
    finding_with_institutional  <- classify(corpus, include_eco_discurso_institucional=True)
    finding_without_institutional <- classify(corpus, include_eco_discurso_institucional=False)
    compare(finding_with_institutional, finding_without_institutional)
    trace_each_marker_to_source_document_line()  # auditable inference chain, strategy memo §7 obj.5
    if finding_collapses_without_institutional_segments:
        report_as_substantive_finding("representación aún dependiente de discurso oficial en este eje")
```

## Phase 8 — Coverage-Conditioned Reporting

```text
for each frequency-style claim ("n docentes mencionaron X"):
    denominator <- count(participants for whom the relevant protocol block was administered)
    report(f"{n}/{denominator}", not f"{n}/14-15")
    # Mandatory per strategy memo §6.1 — semi-structured coverage caveat
```

## Phase 9 — Substantive Theory / Integration

```text
integrate(axial_categories, nucleo4_findings, nucleo5_findings, objetivacion_anchor_table)
articulate(substantive_account_of="cómo se relacionan competencias digitales, conocimientos previos,
           preocupaciones, concepción del potencial pedagógico, y decisiones de diseño didáctico
           de IAG en el diseño de propuestas didácticas, para docentes de nivel primario de CABA,
           incluyendo cómo su discurso dialoga con el imaginario oficial/nacional")
# This is the GT endpoint: a substantive theory grounded in the data, not a frequency table.
```
