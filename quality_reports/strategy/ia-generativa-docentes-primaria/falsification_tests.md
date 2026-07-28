# Falsification / Validation Tests: ia-generativa-docentes-primaria

**Paper type:** Descriptive/interpretive (qualitative) — these are the validation/falsification equivalents for a Social-Representations-Theory + thematic-analysis design, not placebo regressions. Cross-referenced with `robustness_plan.md` (Priority 1 and Priority 4).

---

## 1. Negative / Deviant Case Analysis (primary falsification device)

For every element classified as a `candidato_nucleo_central` (strategy memo §2.3), actively search the full corpus for participants whose discourse contradicts or complicates that classification.

- **What would falsify the candidacy:** A substantial minority (not just one participant) explicitly and consistently rejects the framing attributed to the núcleo (e.g., if "IA generativa como herramienta neutral" is a candidate, and 4+ participants instead frame it as inherently threatening with no neutral framing at all, the core candidacy is weakened, not confirmed).
- **Documented outcome required:** For each candidate, state explicitly: (a) how many deviant cases were found, (b) whether they were resolved by re-reading as a variant of the same core theme (still consistent), or (c) whether they genuinely contradict and should downgrade the element to peripheral or split it into two competing candidate cores.

## 2. Institutional-Discourse Falsification Check

- **What would falsify "genuine representation" claim:** If a candidato_nucleo_central *only* appears in segments coded `eco_discurso_institucional` and disappears entirely when those segments are excluded, this falsifies the claim that it reflects docentes' own constructed sense-making rather than repetition of official/ministerial discourse.
- **Implementation:** Re-run Phase 3 classification (pseudo_code.md) excluding `eco_discurso_institucional`-tagged segments; compare núcleo candidate lists.
- **Reportable outcomes:** (a) núcleo stable → strengthens genuineness claim; (b) núcleo collapses → report as a substantive finding about the representation's dependence on official discourse, explicitly flagged, not hidden.

## 3. Domain-Stability Falsification Check

- **What would falsify the "single supraordinate representation across aula/tareas" framing (strategy memo §1):** If the candidatos a núcleo central identified in `aula`-tagged segments share no elements at all with those identified in `tareas_docentes`-tagged segments, the single-object framing is falsified, and the thesis should instead report two distinct representations.
- **Implementation:** Compare Phase-3 classification run separately on each domain-tagged subsample (robustness_plan.md, Priority 2, #6).
- **Reportable outcomes:** Both a stable shared core and a fragmented/domain-specific core are legitimate, reportable findings — the check exists to prevent asserting stability (or fragmentation) without having actually tested it.

## 4. Individual-Opinion Falsification Check

- **What would falsify a proposed núcleo element:** If, on closer coding, an element that initially appeared frequent (≥8/14) turns out to be frequent only because participants are echoing the interviewer's own question wording (interview-effect artifact) rather than generating the framing spontaneously.
- **Implementation:** For each candidate, check whether the framing appears in participant answers to open/non-leading questions in the interview guide, not only in response to a question that already used that framing.
- **Reportable outcome:** Flag and downgrade any candidate whose apparent frequency is substantially an artifact of question wording.

## 5. Cross-Method Falsification (manual coding vs. IRAMUTEQ)

- **What would falsify confidence in a candidate:** If IRAMUTEQ's word-frequency/similarity-analysis output shows the term/theme is actually rare or peripheral in raw lexical terms, while manual coding classified it as central — this discrepancy must be investigated, not silently dropped.
- **Implementation:** robustness_plan.md Priority 2, #5.
- **Reportable outcome:** Document whether the discrepancy reflects a genuine limit of lexical-frequency methods (i.e., a theme can be central in meaning without being lexically frequent — legitimate in SRT theory, where connotative force ≠ raw frequency) or an actual overreach in manual coding.

## 6. Saturation Falsification

- **What would falsify the "N=14 is adequate" claim:** The cumulative new-codes-per-interview curve (robustness_plan.md Priority 1, #1) fails to flatten by interview 14 — i.e., interviews 12, 13, 14 still introduce substantial numbers of new codes.
- **Reportable outcome:** If saturation is not reached, state this explicitly as a scope limitation on the structural claims (do not claim a "complete" núcleo central reconstruction; frame findings as provisional/exploratory).
