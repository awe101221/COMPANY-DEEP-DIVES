# MELI customer-funds / restricted-cash mapping — 2026-08-20

**Question:** How do funds payable to customers, restricted cash, card-settlement payables, and “available cash” sit on the 2026-06-30 balance sheet, and what does that do to the EV bridge?  
**Status:** First completed mapping from primary 10-Q Note 3 + liquidity MD&A + net-debt recon. Not a country-by-country legal-regime memo (that residual is still open).  
**As-of:** 2026-08-20. Balance sheet 2026-06-30. Price used only for a restated EV, not a new DCF.

Epistemic labels are marked. Arithmetic is **my calculation** on reported 10-Q figures.

---

## 1. Bottom line

The 2026-08-16 reverse DCF already treated customer funds as **float, not excess cash**. The 10-Q mapping confirms that classification and adds three facts that were not previously sized:

1. **Restricted cash is not 1:1 with funds payable.** Restricted cash $13,114mn covers **81.8%** of funds payable to customers $16,035mn. The $2,921mn gap sits in unrestricted cash and working capital. Combined cash + restricted cash ($16,763mn) covers funds payable with a **$728mn** cushion.
2. **Brazil is the pile.** Banco Central do Brasil mandatory-guarantee cash is **$11,174mn — 85.2%** of restricted cash, up from $7,865mn at YE 2025 (+$3,309mn in six months). A BCB reserve-rule change is the concentrated customer-fund risk, not a generic “LatAm float” risk.
3. **Owner cash is still $6,751mn.** Management’s available-cash recon already strips restricted cash, guarantee securities, VIE securitization investments, equity at cost, and $155mn of GAAP cash under management-restriction policies. Using Yahoo-style “total cash $5.7bn / total debt $13bn” still misstates the same 10-Q.

This does **not** change the reverse-DCF conclusion. It raises confidence that the $6.425bn net-debt figure is the right plug, and it elevates Brazil payments regulation inside R6/R7.

---

## 2. Reported stock (10-Q, $ millions)

| Line | 2026-06-30 | 2025-12-31 | Δ H1 | Label |
|---|---:|---:|---:|---|
| Cash and cash equivalents | 3,649 | 3,670 | −21 | Reported — Note 3 / BS |
| Restricted cash and cash equivalents | 13,114 | 9,867 | +3,247 | Reported — Note 3 |
| **Cash + restricted (CFS total)** | **16,763** | **13,537** | **+3,226** | Reported — CFS |
| Short-term investments | 2,081 | 2,629 | −548 | Reported |
| Long-term investments | 1,715 | 1,764 | −49 | Reported |
| **Cash + restricted + investments** | **20,559** | **17,930** | **+2,629** | Calculated |
| of which non-U.S. subsidiaries | 18,724 | — | — | Reported — liquidity MD&A; **91.1%** |
| held outside the U.S. | — | — | — | Reported: **83.6%** of the consolidated cash+restricted+investments pile |
| Funds payable to customers | 16,035 | 13,029 | +3,006 | Reported — BS / CFS |
| Amounts payable due to credit and debit card transactions (current) | 4,996 | 3,584 | +1,412 | Reported |
| Same, non-current | 188 | 187 | +1 | Reported |
| **Card-settlement payables** | **5,184** | **3,771** | **+1,413** | Calculated |
| Credit card receivables and other means of payments, net | 8,349 | 6,893 | +1,456 | Reported — current asset |
| Available cash, investments and digital assets (non-GAAP) | 6,751 | 6,710 | +41 | Non-GAAP — net-debt / FCF recon |
| Net debt (mgmt, incl. leases) | 6,425 | 4,682 | +1,743 | Non-GAAP |

**Source:** [Q2 2026 10-Q](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000023/meli-20260630.htm) Note 3, balance sheet, cash-flow statement, liquidity MD&A, and the net-debt / adjusted-FCF reconciliations. Δ and ratios are **calculated**.

---

## 3. Restricted-cash composition (Note 3)

| Bucket | 2026-06-30 | 2025-12-31 | Share of 6/30 restricted | Label |
|---|---:|---:|---:|---|
| Cash in bank accounts — **BCB mandatory guarantee (Brazil)** | 11,174 | 7,865 | **85.2%** | Reported |
| Time deposits + cash — **CNBV mandatory guarantee (Mexico)** | 892 | 809 | 6.8% | Calculated: 39+853 / 127+682 |
| Cash + time deposits — **CMF mandatory guarantee (Chile)** | 290 | 332 | 2.2% | Calculated: 244+46 / 288+44 |
| Cash in bank accounts — **BCRA mandatory guarantee (Argentina)** | 360 | 394 | 2.7% | Reported |
| Securitization transactions (restricted to third-party investors) | 311 | 387 | 2.4% | Reported; fn (2) |
| Money market + cash/wallets held for **Meli Dólar** holders | 78 | 62 | 0.6% | Calculated: 67+11 / 50+12 |
| Other restricted cash and cash equivalents | 9 | 18 | 0.1% | Reported |
| **Total restricted cash** | **13,114** | **9,867** | 100% | Reported |

**Arithmetic check:** 11,174 + 892 + 290 + 360 + 311 + 78 + 9 = 13,114.

H1 Brazil BCB reserve **+$3,309mn** vs H1 funds-payable **+$3,006mn**. The restricted-cash build is Brazil-reserve build, not a Mexico/Argentina story.

Additional **restricted investments** sit off the restricted-cash line (Note 3 footnotes + liquidity MD&A):

- Liquidity MD&A: main liquidity source is $5,271mn of cash + ST investments, **excluding $459mn of restricted investments**.
- Note 3 fn (1) on ST foreign-government debt: **$202mn** restricted for the BCB mandatory guarantee (was $786mn at YE 2025).
- Same footnote: **$16mn** restricted for the Central Bank of Uruguay mandatory guarantee.
- Net-debt recon excludes time deposits / foreign debt / foreign-government securities “restricted and held in guarantee,” VIE securitization investments, and equity at cost.

Do not add the $459mn restricted investments on top of the $13,114mn restricted-cash line and call the sum “customer funds.” Some of it is the same BCB guarantee in securities form; some is credit-line / VIE collateral.

---

## 4. What maps to what

### A. Mercado Pago customer float

| Object | 2026-06-30 | Cover |
|---|---:|---|
| Funds payable to customers | 16,035 | Liability — wallet / payment balances owed to users |
| Restricted cash | 13,114 | 81.8% of the liability |
| Unrestricted cash + restricted cash | 16,763 | 104.5% of the liability |
| Residual (funds payable − restricted cash) | 2,921 | **Not** ring-fenced on the restricted-cash line |

**Inference (not a legal opinion):** MELI does not keep a dollar of restricted cash for every dollar of funds payable. Brazil’s BCB mandatory guarantee is the dominant ring-fence. The residual $2.9bn is economically still a customer claim; it is just not in the restricted-cash account. Combined cash + restricted still covers the claim. That is why the reverse DCF correctly refused to treat $13.1bn of restricted cash as excess cash **and** refused to treat $16.0bn of funds payable as ordinary debt.

### B. Card-settlement float (different object)

Credit-card receivables and other means of payment, net **$8,349mn** vs card-settlement payables **$5,184mn** → net **$3,165mn** acquiring receivable (calculation). This is settlement timing with card networks / issuers, not Mercado Pago wallet balances. 10-K Item 1A language on processors and card networks (extracted on PR #7) attaches here. Do not net it against funds payable.

### C. Owner / available cash (the EV plug)

Net-debt recon, 2026-06-30:

| | $ mn | Note |
|---|---:|---|
| GAAP cash and cash equivalents | 3,649 | BS |
| Cash used in available-cash recon | 3,494 | fn (1): excludes cash restricted by **management restriction policies** |
| Implied management-restricted cash inside GAAP cash | **155** | Calculated: 3,649 − 3,494 |
| Eligible ST investments | 1,622 | vs GAAP ST 2,081 |
| Eligible LT investments | 1,635 | vs GAAP LT 1,715 |
| **Available cash, investments and digital assets** | **6,751** | Non-GAAP |
| Total debt (loans + leases) | 13,176 | Non-GAAP |
| **Net debt** | **6,425** | Non-GAAP |

This is the same $6,751 / $6,425 pair used in `reverse-dcf-2026-08-16.md`. The mapping does not change the EV arithmetic. It documents *why* $13.1bn of restricted cash is excluded.

H1 adjusted FCF already subtracts **$2,023mn** of “increase in cash and cash equivalents and investments related to customer funds due to regulatory requirements and other restrictions (including management restriction policies) and equity securities held at cost.” That $2,023mn is smaller than the $3,247mn restricted-cash build because some of the build is funded by the funds-payable inflow (CFO +$2,456mn) and because the FCF line also nets restricted *investments* and equity-at-cost.

---

## 5. Restated EV at the 2026-08-19 close (not a new DCF)

| | 2026-08-14 close | 2026-08-19 close | Label |
|---|---:|---:|---|
| Price | $1,844.58 | $1,908.65 | Third-party — Yahoo chart |
| Diluted WAS | 50,697,301 | 50,697,301 | Reported — Q2 8-K / 10-Q |
| Equity market value | $93.52bn | **$96.76bn** | Calculated |
| Net debt (unchanged BS) | $6.425bn | $6.425bn | Non-GAAP, 2026-06-30 |
| **Enterprise value** | **$99.94bn** | **$103.19bn** | Calculated |
| vs $1,844.58 reverse DCF | — | **+3.3% EV / +3.5% equity** | Calculation |

The 2026-08-16 rule was: do not rebuild the reverse DCF unless price moves **>10%** or a new print arrives. $1,908.65 is +3.5% from $1,844.58 and +7.3% from the 2026-08-18 close used on PR #7. **No DCF rebuild.**

Forward multiples at $1,908.65 on unchanged Yahoo GAAP-style EPS $38.31 / $55.99: **49.8× 2026E / 34.1× 2027E** (calculation). At $1,844.58 those were 48.1× / 32.9×.

---

## 6. Investment implications

- **EV quality:** the $6.425bn net-debt plug survives a line-by-line cash map. Restricted cash is customer-fund / guarantee / SPE collateral. It is not a hidden $13bn cash pile.
- **Regulatory concentration:** 85% of restricted cash is a BCB mandatory guarantee. Open question #9’s remaining work is the *legal* Brazil payments-institution rule (what ratio, what eligible assets, what happens in a stress), not a hunt for a missing balance-sheet line.
- **Argentina is not the float:** BCRA mandatory-guarantee cash is only $360mn (2.7% of restricted). Argentina’s thesis weight is still **direct contribution and credit**, not trapped customer funds.
- **CFO remains not owner earnings.** H1 CFO $5,737mn includes +$2,456mn funds payable and +$1,209mn card-settlement payables. Adj. FCF $158mn is the company’s own attempt to strip that.

---

## 7. What is still unknown

1. The BCB (and CNBV / BCRA / CMF) **statutory reserve ratio** and eligible-asset list. Note 3 names the regulator; it does not print the formula.
2. How much of the $2,921mn funds-payable residual is Brazil wallet cash that is economically reserved in unrestricted accounts vs Mexico/Chile/other.
3. Meli Dólar legal structure beyond “held for holders” ($78mn).
4. Whether a BCB stress or a payments-license event would force MELI to top up the $11.2bn guarantee from available cash (that is the R6 path).
5. 10-K Item 1A #11–#13 full text lives on PR #7 (`risk-factors-10k-2026-08-19.md`), not yet on `main`. This memo uses the 10-Q numbers, not that inventory.

**Working confidence:** **70%** on the dollar map and the Brazil-concentration claim (both are Note 3 arithmetic). **40%** on any statement about what a BCB rule change would cost, because the ratio is not disclosed.

---

## 8. Sources

Primary: Q2 2026 10-Q Note 3; balance sheet; cash-flow statement; liquidity MD&A (non-U.S. 91.1% / outside-U.S. 83.6% / $459mn restricted investments / $5,271mn “main source”); net-debt recon; adjusted-FCF recon. Filed 2026-08-06.  
Prior work: `reverse-dcf-2026-08-16.md` EV rules.  
Price: Yahoo chart API, 2026-08-19 close $1,908.65.
