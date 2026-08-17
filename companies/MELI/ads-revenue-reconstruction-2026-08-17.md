# MELI ads-revenue reconstruction

**As-of:** 2026-08-17.  
**Question:** What is Mercado Ads revenue and incremental margin in dollars? (open question #4)  
**Status:** Progressed, not closed. GAAP still does not break out advertising.  
**Epistemic labels:** reported fact / management claim / third-party estimate / calculation / inference are marked inline.

---

## Bottom line

Advertising is **not a GAAP line**. The last company-reported ads/GMV print is **Q4 2024: 2.1% of GMV** ([Q4’24 letter](https://www.sec.gov/Archives/edgar/data/1099590/000109959025000004/meli-20250220xex991.htm); same sentence in the [IR/news reprint](https://news.mercadolibre.com/en/financial-results-fourth-quarter-2024)). After that, letters give **growth rates only**.

Chaining those growth rates off the last reported take-rate and the last reported GMV dollars produces a **Q2 2026 ads range of about $480–630mn**, with a **base case ~$560mn** (calculation). That is **~2.2–2.9% of Q2 GMV** and **~4.7–6.2% of Q2 revenue**. TTM ads land around **$1.7–2.1bn** (calculated envelope; base sketch ~$1.9bn).

That is a real high-margin engine. It does **not** change 25/45/30. Moving ads from ~2.55% to 4% of TTM GMV would add on the order of **+$1.1bn ads** and, at a 70–90% incremental contribution assumption (inference / analog, not disclosed), **~+2 ppts of TTM EBIT margin**. Useful for the reverse-DCF debate. Not a reason to raise bull probability today.

**Scale, not an economic offset:** Q2 2026 provision for doubtful accounts was **$1,276mn** (reported). Reconstructed base ads revenue is about **0.4×** that expense. Advertising revenue and credit provisions are **not directly comparable P&L measures** — ads is a commerce-services revenue line; PDA is a credit operating expense. Only an undisclosed ads *contribution* could be compared economically to an expense. The 0.4× figure is a scale check, not a netting identity.

**Working confidence in the dollar range: ~55%.** The growth rates and the Q4’24 2.1% anchor are primary. The Q2’24 take-rate used to start the Q2 chain is interpolated.

---

## 1. What the company actually discloses

| Period | What was disclosed | Source | Label |
|---|---|---|---|
| Q2 2022 | Ads “reaching 1.2% of GMV this quarter” | [Q2’22 EX-99.1](https://www.sec.gov/Archives/edgar/data/1099590/000156276222000324/meli-20220803xex99_1.htm) | Reported (letter) |
| FY 2022 | 1.3% of ~$34bn GMV | [Q4’23 EX-99.1](https://www.sec.gov/Archives/edgar/data/1099590/000109959024000005/meli-20240222xex991.htm) | Reported (letter) |
| FY 2023 | 1.6% of ~$45bn GMV; Q4’23 also 1.6% | Same Q4’23 letter | Reported (letter) |
| Q4 2024 | Ads +41% YoY USD / +88% FXN, **2.1% of GMV** | [Q4’24 EX-99.1](https://www.sec.gov/Archives/edgar/data/1099590/000109959025000004/meli-20250220xex991.htm) | Reported (letter) |
| Q2 2025 | +38% USD / +59% FXN; “revenue relative to GMV rose across-the-board” | [Q2’25 EX-99.1](https://www.sec.gov/Archives/edgar/data/1099590/000109959025000041/meli-20250804xex991.htm) | Reported (growth); take-rate qualitative |
| Q3 2025 | +56% USD / +63% FXN | [Q3’25 press / letter](https://www.businesswire.com/news/home/20251029534041/en/Mercado-Libres-Strategic-Investments-Drive-Net-Revenue-to-%247.4-Billion-in-Q3-2025-Marking-the-27th-Consecutive-Quarter-of-Growth-Above-30-YoY) | Reported (growth) |
| Q4 2025 | +70% USD / +67% FXN. Call: penetration “still small compared to its potential” | [Q4’25 EX-99.1](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000003/meli-20260224xex991.htm); [Q4’25 call](https://www.fool.com/earnings/call-transcripts/2026/02/26/mercadolibre-meli-q4-2025-earnings-transcript/) | Reported (growth); management claim (penetration) |
| Q1 2026 | +73% USD / +63% FXN; “4x the market in 2025” | [Q1’26 letter via 8-K](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000014/meli-20260507xex991.htm) | Reported (growth); management claim (vs market) |
| Q2 2026 | +73% USD / +62% FXN; “surpassed 10% share of the digital advertising market in Latin America for the first time”; “one of our highest-margin revenue lines” | [Q2’26 EX-99.1](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000021/meli-20260805xex991.htm) | Reported (growth); management claims (share, margin rank) |

**2025 10-K** describes Mercado Ads products (Product Ads, Brands Ads, Display, Video) and folds “advertising sales fees” into Commerce **services** revenue. No dollar breakout ([10-K](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000006/meli-20251231.htm)).

Commerce revenue definition (letter): marketplace fees, shipping, 1P, **ad sales**, classifieds, membership, ancillary. Q2 2026 commerce revenue **$5.8bn**, +50% USD (IR press release / letter highlights).

---

## 2. Anchors that can be multiplied

### A. Q4 2024 — last reported take-rate (preferred anchor)

- GMV Q4’24 = **$14,548mn**; Q4’23 = **$13,450mn** ([Q4’24 letter table](https://www.sec.gov/Archives/edgar/data/1099590/000109959025000004/meli-20250220xex991.htm)).
- Ads Q4’24 = 2.1% × $14,548mn = **$305.5mn** (calculation).
- Cross-check: Q4’23 ads = 1.6% × $13,450mn = **$215.2mn**; × 1.41 = **$303.4mn**. Matches the 2.1% print within rounding.

### B. Q4 2025 — growth applied to A

- Letter: ads +70% USD.
- Ads Q4’25 = $305.5mn × 1.70 = **$519mn** (calculation).
- GMV Q4’25 = **$19.9bn** (letter) → implied take-rate **2.61%** (calculation).

### C. Q2 chain — requires an interpolated Q2 2024 take-rate

Q2 GMV (reported except Q2’24, which is a residual):

| Period | GMV $mn | USD YoY | Source |
|---|---:|---:|---|
| Q1 2024 | 11,365 | +20% | [Q1’24 letter](https://www.sec.gov/Archives/edgar/data/1099590/000109959024000015/meli-20240502xex991.htm) |
| Q2 2024 | **12,647** | — | Calculation: FY24 GMV $51,467 − Q1 $11,365 − Q3 $12,907 − Q4 $14,548 ([10-K](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000006/meli-20251231.htm) / letters) |
| Q3 2024 | 12,907 | +14% | [Q3’24 letter](https://www.sec.gov/Archives/edgar/data/1099590/000109959024000039/meli-20241106xex991.htm) |
| Q4 2024 | 14,548 | +8% | Q4’24 letter |
| Q2 2025 | 15,258 | +21% | [Q2’25 / Q2’26 letters](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000021/meli-20260805xex991.htm) |
| Q2 2026 | 21,926 | +44% | Q2’26 letter |

Q2’25 / Q2’24 = 15,258 / 12,647 = **+20.6%**, vs letter +21%. Residual GMV is consistent.

Ads USD growth: Q2’25 **+38%**, Q2’26 **+73%** → two-year factor **1.38 × 1.73 = 2.387**.

Q2’24 take-rate is **not disclosed**. Bounds from nearby reported prints:

| Q2’24 take-rate assumption | Q2’24 ads | Q2’25 ads | Q2’26 ads | Q2’26 ads/GMV | Q2’26 ads / $10,169mn rev |
|---|---:|---:|---:|---:|---:|
| 1.6% (FY23 / Q4’23 reported) | 202 | 279 | **483** | 2.20% | 4.7% |
| 1.85% (linear Q4’23 1.6% → Q4’24 2.1%) | 234 | 323 | **559** | 2.55% | 5.5% |
| 2.1% (Q4’24 reported peak, applied to Q2) | 266 | 366 | **634** | 2.89% | 6.2% |

**Base case = $559mn / 2.55% of GMV / 9.6% of $5.8bn commerce.** The 1.85% start is an interpolation (inference), not a company number.

Implied take-rate expansion Q2’25→Q2’26, independent of the start: ads +73% vs GMV +44% ⇒ take-rate × **1.20** (calculation). That is the cleanest primary-sourced statement: **ads monetization per GMV dollar rose about 20% YoY in Q2 2026.**

---

## 3. TTM sketch (wider error bars)

Using the same method on the other three TTM quarters, with Q3’24 take-rate interpolated ~1.9% and Q1’25 ~1.8–2.0%:

| Quarter | Ads $mn (base) | Method |
|---|---:|---|
| Q3 2025 | ~380 | Q3’24 GMV $12,907 × ~1.9% × 1.56 |
| Q4 2025 | 519 | Q4’24 2.1% anchor × 1.70 |
| Q1 2026 | ~415–460 | Q1’25 GMV residual $13,336mn × ~1.8–2.0% × 1.73 |
| Q2 2026 | 559 | Q2 chain base |
| **TTM** | **~$1.9bn** (calculated envelope **~$1.7–2.1bn**) | Sum of the four quarters; high end uses the 2.1% start-rate bound on Q2 and nearby quarters |

Q1 2025 GMV residual: FY25 GMV $65,037 − Q2 $15,258 − Q3 $16,543 − Q4 $19,900 = **$13,336mn** (calculation). Q1’26 GMV $18,951 / $13,336 = +42%, matching the letter.

Treat TTM as a **sketch**, not a model input with three-decimal precision.

---

## 4. The “10% of LatAm digital ads” claim

Management claim, Q2’26 letter: first time above **10% of Latin America’s digital advertising market**.

Third-party market sizes disagree by 2×:

| Source | What it measures | Size | 10% would imply | Fit vs ~$1.9bn TTM |
|---|---|---|---|---|
| [eMarketer, 2025-06-25](https://www.emarketer.com/content/latin-america-ad-spending-2025) | Total LatAm ad spend >$40bn; digital **56.6%** of that | Digital ≈ **$22.6bn** | ≈ **$2.3bn** | Close to the reconstruction |
| IMARC (paywalled summary) | “Digital advertising” 2025 | $43.5bn | $4.4bn | ~2× too high vs take-rate chain |
| Research and Markets Q1’26 databook | Digital ad spend 2025 / 2026 | $45.3bn / $50.1bn | $4.5–5.0bn | Same problem |

**Inference:** either MELI is using a narrower market (retail media / digital excluding some search-social, or a different vendor), or the broad “digital advertising” reports are not the denominator management has in mind. Do **not** invert 10% × $45bn into a $4.5bn MELI ads number — it fights the take-rate chain and management’s own “still small vs potential” comment.

eMarketer-implied ~$2.3bn is a **consistency check**, not an independent proof.

---

## 5. Incremental margin and the 4% GMV thought experiment

**Reported / management:** ads is “one of our highest-margin revenue lines” (Q2’26 letter). Incremental margin is **not disclosed**.

**Analog (third-party / competitor):** Amazon 2025 advertising services **$68.635bn** ([AMZN 2025 10-K](https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm)). Amazon does **not** report ads/GMV. Sell-side/alt-data “~7–8% of GMV” figures are third-party estimates. Use Amazon only as a **long-run ceiling analog**, not as a MELI run-rate.

**Calculation / inference** (show the formula; do not treat as a forecast):

- TTM GMV Q3’25–Q2’26 = 16,543 + 19,900 + 18,951 + 21,926 = **$77,320mn**.
- Base ads/GMV ~2.55%. Gap to 4.0% = **145 bps**.
- 1.45% × $77.32bn = **+$1.12bn ads**.
- If incremental contribution is 70–90% (unverified analog): **+$0.78–1.01bn** of contribution.
- TTM revenue $35,182mn; TTM EBIT $2,907mn (8.26%). Adding $1.12bn revenue **and** $0.78–1.01bn EBIT → new TTM EBIT margin **~10.2–10.8%** (calculation: $3,691–3,916mn / $36,302mn).

That is **one** path toward the reverse DCF’s embedded ~13% terminal EBIT (`reverse-dcf-2026-08-16.md`). Credit losses and shipping subsidies remain separately large near-term P&L items; they are not netted against ads revenue.

**Scale check (not an offset):** Q2’26 PDA **$1,276mn** (reported expense) vs base ads **~$559mn** (reconstructed revenue) ≈ **0.4×**. These lines do not net. An ads contribution at an unverified 70–90% incremental margin would be ~$390–500mn — still a different economic object from PDA.

---

## 6. What this does and does not do to the thesis

- **Does:** replace “ads is a mystery high-margin residual” with a sourced **$0.5–0.6bn quarterly / ~$2bn TTM** working range and a **~20% YoY take-rate expansion** in Q2.
- **Does:** show why a 4% GMV ads outcome is still **material** to terminal margin (~+2 EBIT ppts on today’s GMV) and why the 4× residual-sales idea in open question #4 is not crazy — it is just **unearned**.
- **Does not:** change 25 / 45 / 30. The investment cycle is still credit + free shipping. Ads is the best **identified** high-margin growth line in the reconstruction, not a demonstrated payback and not a net against PDA.
- **Does not:** justify treating street FY27 EPS $55.99 as ads-driven. Street does not publish an ads line I can audit.

**Falsifiers for this reconstruction:**

1. Next letter (or GS 2026-09-08) gives an ads/GMV print **outside 2.0–3.2%** for Q2 or Q3 2026.
2. FXN ads growth falls below **40%** for two quarters — the 4% GMV path lengthens.
3. A 10-K/10-Q disaggregation shows ads **materially below $1.5bn** TTM.

---

## 7. What remains unknown

- Exact quarterly ads dollars after Q4 2024.
- Ads gross margin, contribution margin, or opex allocation (AI search / HBO Max / off-platform inventory).
- On-platform vs off-platform / CBT / Top Brands mix in dollars.
- Whether “10% digital-ad share” uses eMarketer-like digital, retail media only, or another vendor.
- Country ads mix (Q4’23 call: Argentina ~20% of GMV but ~10% of ads — that dilution can still move the consolidated take-rate).

---

## 8. Pre-merge review (2026-08-17)

Rechecked arithmetic before PR #5 review. Unchanged after recheck: Q4’24 ads $305.5mn (2.1% × $14,548mn); Q4’23 cross-check $215.2mn × 1.41 = $303.4mn; Q2’24 GMV residual $12,647mn; Q2 chain $483 / $559 / $634mn; take-rate expansion 1.73 / 1.44 ≈ 1.20; 4% GMV gap +$1.12bn ads.

Corrected in this review: TTM calculated envelope **~$1.7–2.1bn** (was rounded to $2.2bn on the high end); 4% thought-experiment TTM EBIT margin **~10.2–10.8%** after adding both ads revenue and assumed contribution to the TTM (was ~10.1–10.7%). Labels unchanged: reported take-rates and growth rates vs calculations vs interpolated Q2’24 start-rate vs inferences.
