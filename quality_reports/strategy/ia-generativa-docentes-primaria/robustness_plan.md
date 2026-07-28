# Robustness Plan: ia-generativa-docentes-primaria

**Design:** Descriptive/interpretive — Social Representations Theory (structural, adapted) + thematic analysis + lexicometric triangulation
**Date:** 2026-07-28

Qualitative equivalent of the standard robustness plan: ordered from most-threatening (assumption-threatening) to least-threatening (sensitivity/reporting refinements). See `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md` for full narrative justification of each item.

## Ordered Checks (Most Threatening First)

### Priority 1: Assumption-Threatening (equivalent to pre-trends/first-stage F)

| # | Check | Assumption Tested | Implementation | Expected/Reportable Result |
|---|-------|-------------------|----------------|-----------------|
| 1 | Saturation curve (cumulative new codes per interview) | N=14 is sufficient for code-level saturation | Tally new codes appearing per interview, in interview order; plot/tabulate | Curve flattens well before interview 14 for code-level saturation; explicitly report whether meaning-level saturation was also reached (likely not — state as scope limit, not failure) |
| 2 | Negative/deviant case search | Every núcleo central candidate is not merely majority opinion masquerading as structural centrality | For each candidate, actively search corpus for contradicting cases | Deviant cases found and documented; resolution (confirms/qualifies/overturns) stated explicitly, not silently dropped |
| 3 | Representación vs. opinión individual coding rule | Central-core candidates reflect socially-anchored, shared sense-making, not one participant's idiosyncratic view | Apply frequency threshold (≥8/14) + social-anchoring language criterion before allowing central-core classification | Idiosyncratic single-participant statements correctly excluded from núcleo candidacy; documented in classification log |
| 4 | Institutional-discourse sensitivity | The reported representation is genuine teacher sense-making, not an echo of official/ministerial discourse | Classify núcleo with vs. without segments coded `eco_discurso_institucional` | If núcleo is stable either way, strengthens credibility claim; if it collapses without institutional segments, report as a substantive finding (not hidden) |

### Priority 2: Specification Sensitivity (equivalent to alternative controls/estimator)

| # | Check | What Changes | Implementation | Expected Result |
|---|-------|-------------|----------------|-----------------|
| 5 | Manual coding vs. IRAMUTEQ lexical triangulation | Method of centrality identification | Compare Phase-3 manual classification against IRAMUTEQ word-frequency/similarity-analysis top clusters | Broad agreement expected on high-salience terms; documented, non-silent handling of any disagreement |
| 6 | Domain-split re-analysis (aula vs. tareas_docentes) | Whether núcleo is analyzed pooled or split by practice field | Run Phase-3 classification separately on `aula`-tagged and `tareas_docentes`-tagged segments | Either a stable shared núcleo across domains, or a documented fragmentation — both are valid, reportable outcomes |
| 7 | Alternative frequency threshold for core candidacy | Sensitivity of núcleo membership to the ≥8/14 cutoff | Re-run classification at 7/14 and 9/14 thresholds | Report which candidates are threshold-sensitive vs. robust across thresholds |

### Priority 3: Inference/Coding Reliability Robustness (equivalent to alternative clustering/inter-coder)

| # | Check | What Changes | Implementation | Expected Result |
|---|-------|-------------|----------------|-----------------|
| 8 | Partial double-coding | Whether classification depends on a single coder's judgment | 3–4 of 14 transcripts double-coded by thesis advisor/second reader | Report percent agreement or informal concordance; document any codebook revision triggered by disagreement |
| 9 | Peer debriefing sessions | Whether analytic judgment calls (connotative force, organizing function) are idiosyncratic to the researcher | At least one documented session with advisor reviewing codebook + núcleo candidates | Dated log of session, changes made as a result |

### Priority 4: Placebo and Falsification Equivalent

See companion file `falsification_tests.md` for the full list (negative case analysis is cross-referenced here as Priority 1 item #2; this section adds narrative-level and domain-level falsification checks).

### Priority 5: Sensitivity Analysis

| # | Check | What It Measures | Implementation | Expected Result |
|---|-------|-----------------|----------------|-----------------|
| 10 | Transcription-completeness sensitivity | Whether classification depends on including any field-note-only (lower granularity) participants | Compare classification using only fully-transcribed subsample vs. full N=14 (if fallback protocol, strategy memo §5.2, was triggered) | Report any element whose central/peripheral classification changes depending on inclusion of the lower-granularity subsample |
| 11 | Heterogeneity by prior AI exposure | Whether núcleo differs for teachers with habitual vs. no prior generative-AI exposure | Subgroup classification (descriptive, not causal) | Report descriptively; do not claim causal difference |
| 12 | Heterogeneity by school type (public/private) | Same as above, institutional context | Subgroup classification, if sample composition allows | Report descriptively |

---

## Design-Specific Notes

This robustness plan substitutes for the standard reduced-form/structural battery (no pre-trends, no first-stage F, no bandwidth sensitivity apply — there is no treatment, no instrument, no cutoff). The equivalent rigor concepts are: saturation (≈ sufficient statistical power), negative case analysis (≈ falsification test), inter-coder agreement (≈ alternative clustering/inference robustness), and triangulation across methods/domains (≈ alternative specification/estimator).
