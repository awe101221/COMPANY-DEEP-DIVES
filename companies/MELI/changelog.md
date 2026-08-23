# MELI research changelog

Dated views only. Do not silently overwrite.

## 2026-08-23 — Incremental run (13D residual / Amendment No. 1)

- **Trigger:** scheduled cron 2026-08-23T12:02:54Z. Prior successful run 2026-08-22 ~14:00 UTC on `cursor/meli-intelligence-update-9891` (PR #10, BCB ratio). This branch is based on current `main` (`261a59f`).
- **Company event:** none. No 8-K after 2026-08-06. Price still 2026-08-21 close $1,922.73. Consensus unchanged.
- **Deep research:** leftover of #11. Amendment No. 1 is a wrap at 3,550,136 / 7.00%. The 150k vs April 2026 proxy matches the 2025 Meliga Form 144 program (117,986 sold / $272.0mn reported; 32,014 remainder inferred). Memo: `13d-residual-2026-08-23.md`.
- **Thesis:** **No thesis change.** Bull 25 / base 45 / bear 30. Confidence stays ~48%.
- **Does not supersede:** PRs #6, #7, #8, #9, or #10.
- **Status:** `research progress only`.
- **Do not merge automatically.**

## 2026-08-17 — Pre-merge review of PR #5

- **Base:** PR #5 is based on current `main` (`ef1cdb2`). `main` is not empty: it already has the repo scaffold, MELI folder templates, and the MELI analyst skill. This PR only changes files under `companies/MELI/`.
- **Supersedes:** PR #5 supersedes PRs #3 and #4 as the merge candidate. It includes the accumulated thesis / reverse DCF / eight-quarter work plus the ads reconstruction.
- **Ads vs PDA:** reframed as a scale comparison (reconstructed ads revenue ≈ 0.4× reported Q2 PDA). Not an economic offset; the lines are not nettable.
- **Arithmetic recheck:** Q2 chain $483 / $559 / $634mn unchanged. TTM envelope tightened to ~$1.7–2.1bn. 4% GMV EBIT-margin math corrected to ~10.2–10.8% after adding both revenue and assumed contribution.
- **Do not merge automatically.**

## 2026-08-17 — Incremental run (ads reconstruction)

- **Trigger:** scheduled cron 2026-08-17T00:31:13Z. Prior successful run ~01:30 UTC the same day on `cursor/meli-intelligence-update-9125`. This branch is based on current `main`; durable MELI files on `main` were uninitialized templates, so prior research was ported in.
- **Company event:** none. No 8-K after 2026-08-06. Price still 2026-08-14 close $1,844.58. Consensus unchanged.
- **Deep research:** ads-revenue reconstruction (`ads-revenue-reconstruction-2026-08-17.md`). Last reported take-rate Q4’24 2.1% of GMV; Q2’26 working range ~$480–630mn (base ~$560mn). TTM envelope ~$1.7–2.1bn. Q2 PDA $1,276mn is a scale comparison only, not an ads offset.
- **Thesis:** **No thesis change.** Bull 25 / base 45 / bear 30. Confidence stays ~48%.
- **Status:** `research progress only`.

## 2026-08-17 — Incremental run (eight-quarter estimate history)

- **Trigger:** scheduled cron 2026-08-17T00:24:58Z. Prior successful run 2026-08-16 ~12:30 UTC on `cursor/meli-intelligence-agent-instructions-303d` (ported onto that branch because `main` still had uninitialized MELI templates).
- **Company event:** none. No 8-K after 2026-08-06. Price still 2026-08-14 close $1,844.58. Consensus unchanged.
- **Deep research:** eight-quarter estimate-vs-actuals (`estimate-vs-actuals-2026-08-17.md`). Revenue beat/in-line 8/8; investment-cycle NI missed until the small Q2’26 beat. FY27 EPS $55.99 is not a high-confidence rebound.
- **Thesis:** **No thesis change.** Bull 25 / base 45 / bear 30. Confidence ~40% → ~48%.
- **Status:** `research progress only`.

## 2026-08-16 afternoon — Incremental run (this workspace)

- **Trigger:** scheduled cron 2026-08-16T12:01:54Z. Prior successful run ~05:18 UTC the same day on branch `cursor/meli-intelligence-agent-instructions-1f5e`.
- **Company event:** none. No 8-K after 2026-08-06.
- **Deep research:** reverse DCF + EV bridge + SOTP (`reverse-dcf-2026-08-16.md`). Price embeds ~13% terminal EBIT at ~9% WACC (or faster duration).
- **Thesis:** **No thesis change.** Bull 25 / base 45 / bear 30.
- **Knowledge base:** ported foundation files into `companies/MELI/`; filled Q3/Q4 2025 EBIT/NI from primary 8-Ks.
- **Status:** `research progress only`.

## 2026-08-16 morning — Foundation run (other branch)

- **Trigger:** first scheduled automation run; no prior memory. Written to `research/meli/` on `cursor/meli-intelligence-agent-instructions-1f5e`.
- **Material event ingested:** Q2 2026 results (8-K 2026-08-05; 10-Q 2026-08-06) plus post-print macros.
- **Thesis:** initial bull 25 / base 45 / bear 30.
- **Deep research:** credit-card NIMAL −2.5% vs 10-Q aging and unused commitments.
- **Status:** `material update`.
