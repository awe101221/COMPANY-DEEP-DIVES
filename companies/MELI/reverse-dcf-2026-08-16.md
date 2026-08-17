# MELI reverse DCF and SOTP — 2026-08-16

**Question:** What growth, margin, reinvestment, and duration does the 2026-08-14 close of $1,844.58 imply, once cash, debt, customer funds, and the credit book are classified correctly?  
**Status:** First completed reverse DCF. Not a full integrated forecast.  
**As-of:** 2026-08-16. Price 2026-08-14 16:00 EDT. Balance sheet 2026-06-30.

Epistemic labels are marked. This memo is **my calculation** on top of reported facts and third-party consensus.

---

## 1. Capital structure (do not treat customer funds as excess cash)

| Item | Amount | Source / label |
|---|---:|---|
| Diluted weighted-average shares (Q2 2026) | 50,697,301 | Reported — Q2 8-K / 10-Q |
| Price | $1,844.58 | Third-party — Yahoo / StockAnalysis, 2026-08-14 close |
| **Equity market value** | **$93.52bn** | Calculated: 1,844.58 × 50,697,301 |
| Cash and cash equivalents | $3.649bn | Reported — 10-Q |
| Restricted cash | $13.114bn | Reported — customer-fund / regulatory / SPE |
| Short-term investments | $2.081bn | Reported |
| Long-term investments | $1.715bn | Reported |
| Available cash, investments and digital assets | $6.751bn | Non-GAAP — 10-Q reconciliation |
| Funds payable to customers | $16.035bn | Reported — matched to restricted cash + working capital |
| Loans payable (current + non-current) | $10.626bn | Reported: 6,482 + 4,144 |
| Operating lease liabilities | $2.550bn | Reported: 513 + 2,037 |
| Total debt (mgmt definition) | $13.176bn | Reported recon |
| **Net debt (mgmt, incl. leases)** | **$6.425bn** | Non-GAAP |
| **Enterprise value** | **$99.94bn** | Calculated: 93.52 + 6.425 |
| Gross loans receivable | $16.375bn | Reported — Note 4 |
| Allowance | $4.379bn | Reported |
| Net loans | $11.996bn | Reported |
| Unused card commitments | $14.047bn | Reported — off-balance |
| Book equity | $7.834bn | Reported → P/B **11.9×** |

**Classification rules used:**

- Restricted cash and funds payable to customers are **not** excess cash or ordinary net debt. They are the Mercado Pago float.
- Net loans are an **operating asset** of a lender, not a hidden cash pile.
- Unused card lines are a contingent credit exposure, not added to EV as debt.
- Yahoo “total cash $5.74bn / total debt $13.21bn” is a third-party compression of the same 10-Q; my EV uses the company’s own net-debt recon.

Yahoo TTM levered FCF $353mn and TTM OCF $13.91bn (key statistics, retrieved 2026-08-16) illustrate the same point: OCF is not owner earnings.

---

## 2. Starting economics (TTM through 2026-06-30)

| Metric | Value | Label |
|---|---:|---|
| Revenue TTM | $35.182bn | Calculated from primary quarters |
| EBIT TTM | $2.907bn (8.26%) | Calculated: 724+889+611+683 |
| Net income TTM | $1.863bn | Calculated: 421+559+417+466 |
| Diluted EPS TTM | $36.75 | Calculated |
| Q2 2026 EBIT margin | 6.72% | Reported / calculated |
| H1 2026 incremental EBIT | −4.7% | Calculated |
| H1 2026 adj. FCF | $0.158bn | Non-GAAP |
| H1 2026 effective tax | 25.5% (302/1,185) | Calculated from 10-Q |
| FY2025 effective tax | 29.7% (845/2,842) | Calculated from 10-K / Q4 letter |
| Tax used in DCF | 28% | Assumption |
| US 10-year | 4.70% | Third-party, 2026-08-14 |
| Yahoo beta (5Y) | 1.31 | Third-party |

**Cost of capital (my construction):**

- Damodaran-style: 4.70% + 1.31 × 5.0% ERP + ~2.9% revenue-weighted LatAm CRP ≈ **14.2%**. At that rate today’s price is not defensible without heroic margins *and* duration. I do not use 14% as the market-clearing rate.
- Market-style (USD mega-cap, no extra CRP): 4.70% + 1.31 × 4.5% ≈ **10.6%**.
- **Base WACC used: 10%.** Sensitivities at 9% and 12%.
- After-tax cost of debt is low-single-digits on $13.2bn of total debt; net debt is only 6% of EV, so WACC ≈ CoE.

**Owner-earnings starting point is the hard part.** TTM NI $1.86bn overstates cash available to equity while the credit book is growing $4.1bn in six months. H1 adj. FCF $158mn understates a mature-book run-rate. The operating DCF therefore starts from EBIT and an explicit reinvestment ratio rather than from NI or adj. FCF.

---

## 3. Consensus used as the near-term revenue path (third-party)

Yahoo Finance analysis page, retrieved 2026-08-16:

| | 2026E | 2027E |
|---|---:|---:|
| Revenue (analysts) | $41.63bn (n=22) | $53.12bn (n=24) |
| YoY | +44.1% vs FY25 $28.89bn | +27.6% |
| EPS | $38.31 (n=19) | $55.99 (n=20) |
| Implied NI (× 50.697mn) | $1.94bn | $2.84bn |
| 30-day-ago EPS | $39.92 | $57.39 |
| Revision | −4.0% | −2.4% |

**My calculation — street-implied EBIT** (NI / 0.72 + $0.2bn net interest/FX drag): ~**$2.90bn (7.0% margin) in 2026** and ~**$4.14bn (7.8%) in 2027**. Near-term street is a *margin-trough* forecast. The recovery is in the multiple, not in 2026–27 consensus EBIT.

Forward multiples at $1,844.58: **48.1× 2026E EPS, 32.9× 2027E EPS, 2.25× 2026E sales, EV/S 2026E 2.40×, EV/EBIT TTM 34.4×.**

---

## 4. Operating reverse DCF

**Revenue path (assumption):** street 2026–27, then fade 22 / 18 / 15 / 12 / 10 / 8 / 6 / 4%. 2035 revenue **$129bn** (16% CAGR from FY2025 $28.89bn). Faster-growth sensitivity fades 25 → 8% and reaches $176bn (20% CAGR).

**Reinvestment (FCFF = EBIT × (1 − 28%) × (1 − reinvestment ratio)):**

| Case | Years 1→10 reinvestment | Economic meaning |
|---|---|---|
| Bear | 80% → 35% | Credit book keeps compounding; FCF stays thin |
| Base | 65% → 25% | Credit growth slows after 2027; capex stays elevated early |
| Bull | 40% → 20% | Deposits/AUM fund most of the book; logistics capex levered |

Terminal reinvestment = g / ROIC with g = 3% and ROIC 12–15%. Terminal growth 3%. EBIT margin interpolates linearly from 7.0% in 2026 to the terminal year.

### Implied terminal EBIT margin that hits $99.9bn EV

| WACC | Bear reinv | Base reinv | Bull reinv |
|---|---:|---:|---:|
| 9% | 14.8% | 13.8% | 13.0% |
| 10% | 18.4% | 17.0% | 16.0% |

MELI reported EBIT margins (10-K, calculated): **14.6% (2023), 12.7% (2024), 11.1% (2025), 6.7% (Q2 2026).** A 16–18% terminal margin at 10% WACC is **above any year in the sourced history**. A 13% terminal margin at 9% WACC is **inside** the 2023–24 range and is the least heroic combination that clears the current price.

### Equity value per share (calculated; not a rating)

| Case | EV | Equity | $/share | vs $1,845 |
|---|---:|---:|---:|---:|
| 6.7% EBIT forever, 10% WACC, base reinv | $43.1bn | $36.6bn | **$723** | −61% |
| 11% terminal (2025 level), 10% WACC, base reinv | $67.0bn | $60.6bn | **$1,196** | −35% |
| 11% terminal, 9% WACC, bull reinv | $85.7bn | $79.3bn | **$1,564** | −15% |
| 13% terminal, 9% WACC, bull reinv | $99.7bn | $93.2bn | **$1,839** | ~0% |
| 14.5% terminal (2023 peak), 9% WACC, base reinv | $104.9bn | $98.5bn | **$1,943** | +5% |

**Implied unlevered IRR if the street-like revenue path is right** (base reinv, start 7% EBIT): ~6.2% if terminal EBIT stays 6.7%; ~7.9% if it recovers to 11%; ~8.4% if it recovers to 12.7%. Those IRRs are **below** a 10% cost of capital — i.e., the market must be using a lower discount rate, a fatter terminal margin, or both.

**Faster-growth overlay:** 20% 10-year revenue CAGR + bull reinvestment + 12% terminal EBIT at 10% WACC ≈ $100bn EV. That is the other way the tape can be right: **duration instead of margin.** It requires MELI to be a ~$175bn-revenue company by 2035 with credit no longer eating cash.

---

## 5. Simple two-stage check on owner earnings

If one instead capitalizes a single owner-earnings number for 10 years then 3% forever:

| Starting OE | 9% CoE implied 10y g | 10.5% CoE implied 10y g |
|---|---:|---:|
| $0.35bn (Yahoo TTM levered FCF) | 40% | 45% (bound) |
| $0.75bn (optimistic TTM adj. FCF) | 29% | 34% |
| $1.86bn (TTM NI) | 17% | 21% |
| $1.94bn (2026E NI) | 17% | 20% |

Even granting TTM net income as owner earnings — which H1 cash conversion says is too generous — the price needs **mid-teens to ~20% earnings compounding for a decade** at a 9–10.5% cost of equity. That only happens if margins recover while revenue is still growing 20%+.

---

## 6. SOTP (illustrative, wide error bars)

Ads, credit interest, and acquiring take-rate are **not** separately disclosed in GAAP. This is a bounding exercise.

| Piece | Method | Value | Label |
|---|---|---:|---|
| Credit | 1.0× net book | $12.0bn | Reported book × assumed multiple |
| Credit | 1.2× net book (base) | $14.4bn | Assumption: mid-cycle ROE ~15%, clean bank P/B |
| Credit | 1.5× net book | $18.0bn | Bull: cards earn through; NIMAL mean-reverts |
| Residual EV at 1.2× credit | $99.9 − $14.4 | **$85.5bn** | Calculated |
| Residual / estimated 2026 non-credit sales (~$21bn) | | **~4.1×** | Assumption: ~half of $41.6bn is commerce+ads+acquiring fees |

A 4× sales multiple on the non-credit ecosystem is what a high-teens incremental-margin marketplace/ads business can bear. It is **not** what a 6.7% group EBIT / negative incremental EBIT business deserves unless the investments are treated as temporary. Card NIMAL of −2.5% and unused lines of $14.0bn argue for the low end of the credit multiple (≤1.0×), which would push even more of the EV onto commerce — i.e., make the residual multiple *more* demanding.

Argentina produced **40% of Q2 direct contribution** on 18% of revenue (foundation-run calculation from the Q2 letter). Any SOTP that capitalizes group EBIT at a single multiple is overweighting a high-margin, high-FX, high-inflation cash-flow stream.

---

## 7. What the price appears to embed (inference)

The 2026-08-14 close is consistent with **one** of these bundles, not with a 6–8% mid-cycle:

1. **Margin-recovery tape:** WACC ~9%, terminal EBIT ~13%, cash conversion improves as the card book seasons. Closest to management’s stated intent.
2. **Duration tape:** WACC ~10%, terminal EBIT ~12%, but revenue still ~$175bn by 2035 (faster than street fade).
3. **Low-rate tape:** WACC ≤8.5% with 11% terminal EBIT. I do not underwrite this with the 10-year at 4.70% and beta 1.31.

It is **not** consistent with “growth is fine, 6.7% is the new mid-cycle, pay 33× 2027E.” That combination is a ~$700–850 stock in this model.

**Variant perception (unchanged in direction, now quantified):** after Q2 the market stopped paying for 12% EBIT *this year*. It is still paying for 12–15% EBIT *by the mid-2030s* at a discount rate that largely ignores LatAm country risk. The debate is whether ecosystem LTV produces that margin *and* frees cash from the credit book.

---

## 8. Limitations and next model work

- No quarter-by-quarter forecast of GMV, TPV, NIMAL, or country DC.
- Single-margin DCF; ads and credit not separated in the explicit period.
- Reinvestment ratios are assumptions, not fitted to a historical ROIC series (credit ROIC is not disclosed).
- Terminal year is 70%+ of EV in the 9–10% WACC cases — standard, and a reason to treat the point estimate as a range.
- Share count assumed flat (supported by H1 buybacks of $1mn and cash LTRP).
- No probability-weighted DCF output yet; the thesis ledger probabilities remain the 2026-08-16 morning set.

**Next:** eight-quarter estimate-vs-actuals (#6) to test whether street 2027 EPS $56 is a recency-biased rebound, then a country-level DC build.
