# Pseudo-Code: Coding/Analysis Workflow — ia-generativa-docentes-primaria

**Paper type:** Descriptive/interpretive (qualitative). This is specification-level pseudo-code for the coding and structural-classification workflow, not a statistical estimation script. See `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md` §2 for full justification of each step.

---

## Phase 0 — Data Readiness Gate

```text
transcribed_n <- count(interviews with full verbatim transcription)

IF transcribed_n < 14:
    STATUS <- "GATE NOT CLEARED"
    ACTION <- complete_remaining_transcriptions()
    IF time_constraint_binding:
        ACTION <- documented_field_note_fallback_protocol()
        # See strategy_memo §5.2: verbatim quotes only for cited fragments,
        # structured field notes within 48h of interview for the rest,
        # explicit per-participant data-source flag (transcript vs. field note)
ELSE:
    STATUS <- "GATE CLEARED — proceed to Phase 1"
```

## Phase 1 — Familiarization

```text
for interview in corpus (n=14):
    read(interview, full=True)
    write_reflexive_memo(interview, researcher_positionality)
    # memo dated and stored — feeds Confirmability (strategy memo §3)
```

## Phase 2 — Deductive + Inductive Coding

```text
codebook_v0 <- {
    # deductive families — strategy memo §2.1
    structural: [candidato_nucleo_central, periferico_proximo, periferico_lejano, contra_nucleo],
    function: [funcion_organizadora, funcion_normativa, funcion_generadora_practicas],
    component: [componente_cognitivo, componente_afectivo_valorativo, componente_normativo],
    contrast_frame: [utilidad_percibida, facilidad_de_uso_percibida, norma_social_pares,
                      conocimiento_tecno_pedagogico],
    narrative: [narrativa_herramienta, narrativa_amenaza, narrativa_colega_par,
                 narrativa_instrumentalista_desconectada],
    discourse_source: [eco_discurso_institucional, voz_experiencial_propia],
    domain: [aula, tareas_docentes, general_no_diferenciado]
}

for interview in corpus:
    apply(codebook_v0, interview)                 # deductive pass
    new_codes <- inductive_open_coding(interview)  # Braun & Clarke phases 2-3
    tag_every_segment(domain, discourse_source)    # mandatory dual tag, not optional

codebook_v1 <- merge(codebook_v0, new_codes)
log_version_diff(codebook_v0, codebook_v1, date, rationale)  # Dependability audit trail
```

## Phase 3 — Structural Classification (candidatos a núcleo central)

```text
for theme in codebook_v1.thematic_codes:
    freq          <- count(distinct participants mentioning theme) / 14
    connotative   <- qualitative_judgment(theme, criterion="non-negotiable framing")
    organizing    <- qualitative_judgment(theme, criterion="structures other cited elements")
    domain_stable <- (theme appears in >=1 'aula'-tagged segment) AND
                      (theme appears in >=1 'tareas_docentes'-tagged segment)

    if freq >= 8/14 and connotative == HIGH and organizing == HIGH:
        classification <- "candidato_nucleo_central"
    elif freq >= 8/14 and domain_stable:
        classification <- "candidato_nucleo_central"   # qualifies via criterion (d) alone
        flag_basis("stability-only qualification — report explicitly")
    elif freq_moderate and linked_to_some_core_candidate:
        classification <- "periferico_proximo"
    else:
        classification <- "periferico_lejano"

    record(theme, classification, evidence_quotes>=1, basis_criteria_met)
```

## Phase 4 — Negative Case Analysis + Saturation Check

```text
for candidate in nucleo_central_candidates:
    deviant_cases <- search(corpus, contradicts=candidate)
    document(deviant_cases, resolution)  # confirms, qualifies, or overturns candidacy

running_new_codes <- []
for i, interview in enumerate(corpus, start=1):
    running_new_codes[i] <- count(codes first appearing in interview_i)
plot_or_tabulate(running_new_codes)  # saturation curve, strategy memo §4 Robustness #1
report(saturation_reached: code-level vs meaning-level, explicitly)
```

## Phase 5 — Triangulation (IRAMUTEQ, secondary)

```text
corpus_text <- export(transcripts, format="iramuteq_corpus")
lexical_output <- run_iramuteq(corpus_text, analyses=["word_frequency", "similarity_analysis"])
# NOT running full CHD as primary evidence — corpus too small (n=14) for stable classes,
# see strategy memo §2.4

compare(lexical_output.top_terms, phase3.nucleo_central_candidates)
document(agreement, disagreement, no_silent_reconciliation=True)
```

## Phase 6 — Domain-Stability Reporting

```text
report_separately(
    corpus_completo = phase3.classification,
    segmentos_aula = phase3.classification.filter(domain="aula"),
    segmentos_tareas = phase3.classification.filter(domain="tareas_docentes")
)
conclude(nucleo_estable_across_domains OR nucleo_fragmentado_across_domains)
# This is the empirical delivery of the "dual coverage" contribution — strategy memo §1, §7
```

## Phase 7 — Institutional-Discourse Sensitivity

```text
nucleo_with_institutional  <- classify(corpus_completo, include_eco_discurso_institucional=True)
nucleo_without_institutional <- classify(corpus_completo, include_eco_discurso_institucional=False)
compare(nucleo_with_institutional, nucleo_without_institutional)
if nucleo_collapses_without_institutional_segments:
    report_as_substantive_finding("representación aún dependiente de discurso oficial")
    # strategy memo §5.5 — this is a finding, not just a limitation
```
