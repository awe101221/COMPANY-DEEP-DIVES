# MELI research changelog

Dated views only. Do not silently overwrite.

## 2026-08-26 — Incremental run (Galperin / Argentina mora mix)

- **Trigger:** scheduled cron 2026-08-26T12:01:25Z. Prior successful run 2026-08-25 ~12:30 UTC on `cursor/meli-intelligence-update-aa93` (PR #12). This branch is based on current `main` (`261a59f`).
- **Company event:** none. No 8-K after 2026-08-06. IR calendar unchanged.
- **External event:** Galperin 2026-08-25 X posts (after last-run cutoff) defending MP mora on dollar-share / median-ticket grounds. Fernández / Pública note: 19.0% of people / 2.9% of dollars. Pública still works for MELI (La Nación).
- **Tape:** 2026-08-25 close $1,997.00. EV restated $107.67bn. DCF not rebuilt.
- **Thesis:** **No thesis change.** Bull 25 / base 45 / bear 30. Confidence stays ~48%.
- **Does not supersede:** PRs #6–#12.
- **Status:** `research progress only`.

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
