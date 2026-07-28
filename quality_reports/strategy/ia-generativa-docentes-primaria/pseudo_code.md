# Pseudo-Code: Coding/Analysis Workflow — ia-generativa-docentes-primaria

**Paper type:** Descriptive/interpretive (qualitative), Grounded Theory. This is specification-level pseudo-code for the coding and category-development workflow, not a statistical estimation script. REBUILT 2026-07-28 — supersedes the version built for the discarded Abric-structural design. See `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md` §2 for full justification of each step.

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
    nucleo4: [eco_discurso_institucional, voz_experiencial_propia],
    nucleo4_optional_inductive: [eco_imaginario_mercantil_mediatico],  # add only if it emerges

    # Cross-cutting / structural tags (not a theoretical núcleo, needed for analysis integrity)
    meta: [protocol_block_source (1-7), provenance_flag (deductivo|inductivo, dated)]
}

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
```

## Phase 3 — Constant Comparison + Axial Category Development

```text
for each code in codebook_v1:
    compare(code, all_previously_coded_segments)
    revise(code)  # merge, split, rename as warranted — not a one-pass tally

axial_categories <- group_related_codes(codebook_v1, guided_by=[
    "Eje A: competencias digitales <-> representación",
    "Eje B: conocimientos previos <-> representación del potencial",
    "Eje C: preocupaciones/expectativas",
    "Eje D: concepción IAG-aprendizaje significativo + usos proyectados en propuestas didácticas"
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
for each nucleo in [1, 2, 3, 4]:
    n_codes <- count(distinct codes under nucleo)
    n_counter_instances <- count(actively-sought counter-instances under nucleo)
    if n_codes <= 1 and elaboration_is_thin:
        report("este eje aparece subdesarrollado en el corpus", reason_hypothesis)
        # Do not pad the write-up to force apparent equal richness across núcleos
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
integrate(axial_categories, nucleo4_findings, objetivacion_anchor_table)
articulate(substantive_account_of="cómo se relacionan competencias digitales, conocimientos previos,
           preocupaciones, y concepción del potencial pedagógico de IAG en el diseño de propuestas
           didácticas, para docentes de nivel primario de CABA, incluyendo cómo su discurso dialoga
           con el imaginario oficial/nacional")
# This is the GT endpoint: a substantive theory grounded in the data, not a frequency table.
```
