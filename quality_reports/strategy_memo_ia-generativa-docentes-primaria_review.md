# Strategy Memo Review — ia-generativa-docentes-primaria

**Target:** `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md` + companion decision record, pseudo-code, robustness plan, falsification tests
**Phase:** Strategy (severity: constructive/medium)
**Score: 87/100 — PASS** (gate: 80)

## Phase 1 — Claim identification
The analytic object is clearly scoped: a supraordinate representation with two "champs de représentation" (aula/tareas), N=14 convenience-sample teachers, no causal claims (correctly avoids INV-8-style overreach — language is interpretive throughout). No issues.

## Phase 2 — Core design validity (the Vergès-substitution question)
This is handled unusually well. The substitution of Abric's qualitative centrality criteria (frequency, connotative force, organizing function, domain stability) for the classic Vergès rank×frequency/free-association instrument is disclosed **consistently** across every artifact — memo §2.3 ("Honest methodological note... must appear in the thesis's methods section, not buried"), §6 objection 5, §7 delivery-check table, and the Decision Record's risk table and "What Would Invalidate This Strategy" section. Hedged language ("candidatos al núcleo central") is used uniformly in `pseudo_code.md`, `robustness_plan.md`, and `falsification_tests.md` — no slippage into presenting this as a completed Vergès-style verification anywhere. The memo also pre-emptively recommends downgrading `positioning.md`'s unhedged "reconstrucción explícita de núcleo central" claim (§7) — correctly identifying that this is the exact point where the lit review's positioning vs. Carvalho & Corrallo/CFE Uruguay could overclaim relative to what N=14 semi-structured interviews can support.

**Issues found:**
- **MAJOR (-6):** Assumption A1 (that Abric's own writing licenses these four qualitative criteria as a legitimate alternative identification route, not just informal researcher judgment) is asserted but never pinned to a specific citation/page. Since this is the load-bearing defense against "this is just thematic analysis relabeled" (referee objection 5, the single biggest risk), it needs verification against Abric (2001) or Abric's "central system/peripheral system" work before the writer phase, not asserted on faith.
- **MINOR (-3):** §7's downgrade recommendation is phrased as advisory ("Recommend softening... flag to the writer") rather than a hard gate the writer-critic is instructed to enforce. For a memo this self-aware, tying it explicitly to a checkable writer-critic rule (e.g., "reject any use of unhedged 'núcleo central' language") would close the loop.

## Phase 3 — Inference soundness (rigor criteria, saturation, data problems)
Credibility/transferability/dependability/confirmability are operationalized concretely, not as boilerplate — each has a specific implementation (intra-participant domain triangulation, partial member-checking, codebook versioning, verbatim-quote requirement per candidate). This meets the BJET/Teaching and Teacher Education bar in `journal-profiles.md` (Lincoln & Guba, documented protocols) well above generic level.

**Data-problem positions:**
- *Finish transcribing all 14 before coding:* Defensible — correctly identifies the depth-of-evidence confound risk, and the field-note fallback is honestly labeled as a compromise, not a preferred design.
- **MINOR (-3):** The fidelity concern is worth partial credit — the memo never checks whether recordings are archived/intact or whether *contextual* memos (interviewer impressions, nonverbal cues) were captured close-in-time for the *already-transcribed* subset, not just for the fallback cases. Verbatim transcription itself doesn't decay with time if recordings are intact, but interpretive context can. Recommend adding this check.
- *Convenience sample + thick description:* This is the textbook-correct qualitative move (explicit non-generalization + thick description is exactly what BJET's "What is transferable beyond this specific school context?" asks for) — not a deficiency, properly scoped rather than oversold as "solving" transferability.
- **MINOR (-2):** The 8/14 frequency threshold is asserted with only a promise to "document and justify" later; sensitivity-tested (7/14, 9/14) in the robustness plan, which mitigates but doesn't replace an ex-ante rationale.

## Phase 4 — Polish/completeness
Referee-objection responses (§6) are genuinely responsive, not generic — each pairs a response with a pre-planned analysis, matches `domain-profile.md` and `journal-profiles.md` Education-section concerns nearly verbatim. Robustness plan and falsification tests correctly translate causal-inference equivalents (saturation ≈ power, negative-case analysis ≈ falsification, inter-coder ≈ clustering) without forcing quantitative-paper vocabulary onto qualitative work.
**MINOR (-2):** No formal research spec exists; RQ was reconstructed (ASSUMED) — already flagged by the memo itself, residual risk carried forward, not a new finding.

## Summary of deductions
MAJOR: Abric-citation grounding for A1 (-6). MINOR: advisory (not gated) positioning downgrade (-3); recording/context-memo fidelity gap (-3); threshold justification deferred (-2); no formal research spec (-2). Total -13/100.

**No CRITICAL issues.** No three-strikes fix-and-rereview round is required — the memo can proceed to the writer phase, with the Abric-citation verification and the writer-critic gate on hedged núcleo language flagged as pre-write action items.

Files reviewed: `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md`, `quality_reports/decisions/strategy_ia-generativa-docentes-primaria.md`, `quality_reports/strategy/ia-generativa-docentes-primaria/{pseudo_code.md,robustness_plan.md,falsification_tests.md}`, `.claude/references/domain-profile.md`, `quality_reports/lit_review_ia-generativa-docentes-primaria.md`, `quality_reports/literature/ia-generativa-docentes-primaria/positioning.md`, `.claude/references/journal-profiles.md`.
