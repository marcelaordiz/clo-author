# Strategy Review: strategy_memo_ia-generativa-docentes-primaria.md

## Round 2 (current) — 2026-07-28

**Score: 95/100 — PASS at Commit gate (≥80) AND PR gate (≥90).**

Verified all 4 round-1 fixes directly against source files (not the Strategist's self-report):

- **Fix 1 (four-axis reconciliation) — VERIFIED, substantive, not cosmetic.** New §1.0 in the memo adds a genuine crosswalk table distinguishing the four theoretical núcleos, the guión's real verbatim four ejes, and Axes A-D, and states explicitly which structure governs the methods-section write-up (the real, verbatim four ejes). Propagates consistently to §2.1's terminological note, `pseudo_code.md` Phase 3, and the Decision Record (terminological clarification + new Alternative 7 + risk-table row). Resolves the discrepancy rather than papering over it.
- **Fix 2 (positioning.md) — VERIFIED, clean.** Item 4 rewritten to single-object framing; the old "objeto dual: aula + tareas docentes" phrase is gone, no residual trace found elsewhere in the file.
- **Fix 3 (three-group typology) — VERIFIED, substantive.** New §8 subsection engages Group 2 (ethics/plagio) with a concrete analysis-plan commitment tying it to Axis C.
- **Fix 4 (encuesta gate) — VERIFIED, substantive.** §6.6 now a hard pre-writer gate with three explicit confirmation questions, cronograma evidence, and Missing Inputs updated.

No new issues introduced by the fixes. Residual gap to 100 is stylistic density in §1.0/§8, not a substantive flaw.

Files reviewed: `quality_reports/strategy_memo_ia-generativa-docentes-primaria.md`, `quality_reports/literature/ia-generativa-docentes-primaria/positioning.md`, `quality_reports/strategy/ia-generativa-docentes-primaria/pseudo_code.md`, `quality_reports/decisions/strategy_ia-generativa-docentes-primaria.md`.

---

## Round 1 (superseded) — 2026-07-28

**Score: 82/100 — PASS at Commit gate only.** 2 MAJOR issues (four-axis schema drift undisclosed; leftover Abric-era fragment in positioning.md) and 2 MINOR issues (three-group typology unengaged; encuesta component under-weighted) — all four fixed and verified in Round 2 above. Full round-1 detail preserved in git history (commit `d4707c5`).

---

## Round 3 (Revision 4) — 2026-08-01

**Score: 92/100 — PASS at Commit gate (≥80) AND PR gate (≥90).**

Scope: targeted amendment review only (5th núcleo + 3 new Núcleo 4 codes + mid-analysis expansion protocol), per the orchestrator's instructions. Revisions 1-3 are treated as already-adjudicated (Round 2, 95/100) and not re-litigated.

### 1. Is Núcleo 5 analytically distinct from Núcleo 2 (Ausubel), or redundant?

**Sound, not redundant.** The memo's distinguishing rationale (§2.1, "Why Núcleo 5 is analytically separate from Núcleo 2") is specific and falsifiable, not just asserted: Núcleo 2 concerns the *student's* learning (does IAG help integrate new content with the student's prior knowledge); Núcleo 5 concerns the *teacher's* planning/design decisions. This is backed by a concrete discriminating rule that names the actual collision risk and resolves it: `criterio_contextual_grupo` (Núcleo 5 — teacher's decision based on the real group) vs. `adaptacion_saberes_previos` (Núcleo 2 — the AI's adaptive capacity) — different loci of agency (teacher vs. tool). `codebook_v0_manual.md` (§Núcleo 5) restates this with a worked example, and even reuses Ausubel as a *secondary* anchor for Núcleo 5 but explicitly "aplicado acá a la decisión docente, no al aprendizaje del alumno" — the right move (showing the same theorist can ground two different objects without conflating them), not a red flag.

Checked whether Núcleo 5 is redundant with the memo's own Axis D (usos half): it is not — Axis D's usos half previously had zero dedicated deductive codes and relied only on open/inductive coding; Núcleo 5 fills that specific, previously-undocumented gap rather than duplicating existing coverage (§1.0 crosswalk, row 4). A genuine methodological upgrade (deductive seeding of a previously-uncoded eje), not relabeling.

One thing not fully addressed (not deducted — minor and the codebook already models the right kind of disambiguation elsewhere): `uso_iai_apoyo_administrativo` (Núcleo 5) has plausible surface overlap with Núcleo 3's `competencia_tecnica_declarada`. Worth a one-line disambiguation rule before coding scales up.

### 2. Mid-analysis expansion protocol and retroactive re-coding of P1

**Methodologically sound, correctly identified as GT-legitimate** (comparación constante / theoretical sensitivity, not "forcing" in reverse) — the Decision Record's Alternative 8 explicitly considered and rejected freezing the codebook, on the correct grounds that refusing a data-driven expansion mid-stream is itself a forcing failure mode. The risk of inconsistent coding across waves is named explicitly in the Decision Record's risk table, with a concrete audit mechanism (`pseudo_code.md` Phase 2's per-interview `coded_date` check + Phase 5's `confirm(retroactive_recoding_completed=True)` gate). The memo does not claim the recoding has actually happened — it mandates and tracks it, the right epistemic stance for a strategy document that cannot itself verify field-work completion.

Two MINOR gaps flagged and **fixed same day**, 2026-08-01 (see Fixes below).

### 3. Content vs. provenance code distinction (§2.4) — internal consistency check

**Consistent with how the original two Núcleo 4 codes were defined in prior revisions.** Traced `eco_discurso_institucional` / `voz_experiencial_propia` back through the Round 2-approved memo text — both codes were, and remain, defined strictly in terms of discursive origin (institutional-echo vs. lived-experience), never in terms of what the segment claims. The new §2.4 Step 2c distinction (content vs. provenance) is orthogonal to that original definition, not a redefinition of it. `codebook_v0_manual.md` mirrors this distinction identically. No drift found.

### 4. Citation integrity — Castañeda et al. (2025)

**Clean.** `Bibliography_base.bib` carries a `% VERIFIED 2026-08-01` comment, not `% UNVERIFIED`, with full text-share provenance documented inline. The memo, `pseudo_code.md`, the Decision Record (Key Assumption A7), and `domain-profile.md` all consistently describe the citation as resolved/verified with matching DOI and bib key. No stray `% UNVERIFIED` markers found referencing this citation anywhere in `quality_reports/`.

### 5. Stale "4 núcleos" / "cuatro núcleos" language

No propagation failures within the three officially-scoped companion files (memo, `pseudo_code.md`, Decision Record) — remaining "4 núcleos" occurrences are legitimate historical/counterfactual references (dated changelog entries; the Decision Record's description of the *rejected* Alternative 8).

One MINOR gap found and **fixed same day**: `quality_reports/plans/2026-07-29_esquema-tesis-completa.md` (outside the three scoped files) still read "4 núcleos" and cited the memo's superseded 95/100 score.

### Deductions and Resolution

| # | Issue | Severity | Deduction | Status |
|---|---|---|---|---|
| 1 | `pseudo_code.md` retroactive-recoding line referenced undefined `codebook_v1.nucleo4_new_codes` | MINOR | -3 | **Fixed 2026-08-01** — line now defines `nucleo4_new_content_codes` explicitly before use |
| 2 | P2 not explicitly named for retroactive re-coding despite triggering the expansion | MINOR | -3 | **Fixed 2026-08-01** — memo §2.3 and `pseudo_code.md` now name P2 explicitly, with the specific rationale (read-closely-enough-to-propose ≠ already-coded-against) |
| 3 | `esquema-tesis-completa.md` plan file not updated to 5 núcleos / stale 95/100 score reference | MINOR | -2 | **Fixed 2026-08-01** — updated to 5 núcleos, current score, and Núcleo 5 cross-referenced to its Chapter 1 theoretical anchor (Palamidessi & Gvirtz) |

**Original total: -8 (Score: 92/100).** All three deductions addressed same-day — re-verification not re-run as a full round (fixes are small and mechanical; scope doesn't warrant a Round 4 for this revision). Score stands at 92/100 as the round's recorded result; the underlying issues no longer exist in the current files.

### What was verified clean (no issues found)

- Núcleo 5's separateness from Núcleo 2 is substantively argued with a concrete disambiguation rule, not asserted.
- The 5-théorie/4-axis asymmetry is proactively flagged and explained (§1.0), not left for a committee member to discover.
- The mid-analysis expansion is correctly classified as GT-legitimate, with the rejection-of-freezing alternative explicitly reasoned through in the Decision Record.
- Content-vs-provenance code distinction is consistent with the original Núcleo 4 code definitions from prior, already-approved revisions.
- Castañeda et al. (2025) citation handling is clean end-to-end across all four touched files.
- No stale "4 núcleos" language within the three officially-scoped companion files.

**Verdict: PASS at both Commit and PR gates. Strategy phase (Revision 4) closed.**
