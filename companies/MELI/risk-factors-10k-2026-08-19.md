# 2025 10-K Item 1A inventory (as-of 2026-08-19)

**Purpose:** Complete the outstanding foundation item — a full read of MercadoLibre’s 2025 Form 10-K Item 1A — and map it onto the live risk register.  
**Primary source:** [2025 Form 10-K](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000006/meli-20251231.htm), filed 2026-02-25. Item 1A begins at “ITEM 1A. RISK FACTORS / Summary of Risk Factors.”  
**Q2 update:** [2026 Form 10-Q](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000023/meli-20260630.htm) Item 1A: “As of June 30, 2026, there have been no material changes in our risk factors from those disclosed in the Company’s 2025 10-K.” **Reported fact.**  
**Epistemic status:** The 40 bullets below are the company’s own summary of principal risks (reported fact). Mapping to register IDs and 12-month probabilities is **inference**. 10-K language is not a forecast and is written to be comprehensive.

This memo does **not** change thesis probabilities. It fills a documentation gap and identifies which 10-K factors are already live in the register versus which were under-weighted.

---

## 1. Company summary — 40 principal risks

Copied in compressed form from the 10-K summary. Grouped here for use; original order preserved.

### Business and operations (10-K: “Risks related to our business and operations”)

| # | 10-K summary (abridged) | Closest register ID | Gap vs prior register |
|---:|---|---|---|
| 1 | Growth of LatAm e-commerce, fintech activity, and Internet reliability | Background / country dossiers | Implicit, not a numbered row |
| 2 | Highly competitive and evolving environment | R5 | Covered |
| 3 | AI/ML labor, legal, regulatory, and social risks | — | **Unmapped.** New row candidate. |
| 4 | Reliance on Google Play / Apple app stores | — | **Unmapped.** Distribution choke. |
| 5 | Adapt operations to changing industry/tech standards, cost-effectively | R2 | Partial (investment-cycle, not tech-adapt) |
| 6 | May not maintain profitability | R2 | Covered |
| 7 | Liability / reputation from user default or ecosystem-service failure | R1, R9 | Partial |
| 8 | User fraud → results, brand, usage | R9 | Covered as tail; 10-K treats as ongoing |
| 9 | Consumer-trend / category-demand miss | — | **Unmapped.** Casas Bahia bulky-goods gap sits here. |
| 10 | Manufacturers limit distributor/e-commerce access | — | **Unmapped.** |
| 11 | Failure by MELI or partners to manage Mercado Pago user funds | R6 | Under-specified. Open Q #9. |
| 12 | Banks / funds / processors; card-association fees, rules, practices | R6 | Under-specified. |
| 13 | Failure of financial-institution counterparties | R6 | Partial |
| 14 | Higher rates may cut Mercado Pago payment volume | Country / R8 | Directionally opposite to the current Selic-cut tape |
| 15 | Funding-mix and ticket-mix shifts hurt Pago | R6 | Partial |
| 16 | Lending exposes MELI to merchant and consumer credit risk | **R1** | Covered. Full text below. |
| 17 | Logistics-network / Mercado Envios reliability | R2 | Partial |
| 18 | Fulfillment-network operation (incl. crime, inventory, construction delay) | R2 | Under-specified. 10-K names organized crime in some regions. |
| 19 | Third-party service-provider failure (hosting, shipping, payments) | R6, R9 | Partial |
| 20 | Cannot compete for ads spend, or merchants cut ads | Ads memo | **Unmapped as a risk row.** Ads were treated as an opportunity. |
| 21 | Strategic investments / M&A may not pay; dilution | — | Low current relevance (no live deal) |
| 22 | Key-person loss | R10 | Covered |
| 23 | Inadequate business insurance | — | Tail |
| 24 | Debt-instrument covenants; rating-agency outlook | R6 | Partial |
| 25 | Digital-asset price volatility and unique loss risks | — | Tail; AUM $23bn is mostly cash/investments, not crypto |
| 26 | ESG / climate stakeholder expectations | — | Tail |
| 27 | Crypto buy/hold/sell feature risks | — | Tail |
| 28 | Natural disaster, climate, geopolitics, pandemic, transport shock | R8 / country | Tail |

### Regulation, IP, technology, emerging markets, shares

| # | 10-K summary (abridged) | Closest register ID | Gap |
|---:|---|---|---|
| 29 | Extensive government regulation; future rules can constrain one or more businesses | **R7** | Covered at high level; 10-K is the inventory |
| 30 | Hard to enforce US-court judgments | — | Structural (Uruguay HQ / Delaware corp) |
| 31 | IP-infringement liability on listings / user content | — | Ongoing marketplace legal |
| 32 | Cannot protect own IP; may infringe others | — | Tail |
| 33 | Delay / failure upgrading IT infrastructure | R9 | Partial |
| 34 | Security breaches, disruption, confidential-data theft | R9 | Covered |
| 35 | Cannot secure licenses for relied-on technologies | — | Tail |
| 36 | Political/economic crisis, terrorism, labor conflict, expropriation, corruption | R3, R4, country | Covered via country dossiers |
| 37 | LatAm governments exercise significant economic influence | R7, country | Covered |
| 38 | Local-currency depreciation, volatility, **exchange controls** | **R8, R3** | Covered; AR bands are the live case |
| 39 | Weaknesses of secure payment methods in LatAm | R9 / fraud | Partial |
| 40 | Charter / Delaware provisions (staggered board, 20% vote cap, poison-pill authority) | Dossier governance | Not a 12-month P&L risk |

---

## 2. Lending language that now binds the consignado launch

10-K Item 1A, “Our lending solution exposes us to the credit risk of our merchants and consumers, among other risks” (reported fact, filed 2026-02-25):

- Credit success “depends on the effective management of the credit-related risk.”
- Underwriting uses an internally developed model that “may not accurately predict their creditworthiness due to inaccurate assumptions … or **limited product history**.”
- Model accuracy can be hit by “legal or regulatory changes (e.g., bankruptcy laws and minimum payment regulations), competitors’ actions, changes in consumer behavior, funding resources, changes in the economic environment, **changes in regulation on interest rates**.”
- Users may default; receivables can become uncollectible; write-offs can hit liquidity.
- “The funding and growth of our lending business are directly related to interest rates; a rise in interest rates may negatively affect our lending business.”

**Inference for the 2026-08-17 Mercado Pago consignado-privado launch:** payroll loans are a new product with *limited product history* in MELI’s model — exactly the risk the 10-K flags. Industry BCB-cited NPL of 8.6% in June 2026 (Folha, 2026-07-30, quoting BCB statistics chief Fernando Rocha) is **not** MELI’s book. It is the strongest available industry prior that “payroll deduction ≠ low NPL” in the Crédito do Trabalhador rail. Folha also reports the government attributes more than half of that NPL to a job-change withholding-transfer failure, not borrower incapacity — an **operational** risk, which is also inside the 10-K lending paragraph (regulatory/process change), not only R1 credit-cycle.

---

## 3. What the prior register already had right

The live pair **R1 (credit cycle) / R2 (investment-cycle payback)** remains the 10-K’s highest-density cluster: #6, #16, #17, #18.  
**R3/R4/R8** map cleanly onto #36–#38.  
**R5** maps onto #2 and #20.  
**R6** maps onto #11–#15 and #24.  
**R7** is #29 plus the country-influence bullets.  
**R9** is #8, #33, #34.  
**R10** is #22.

The 10-K does **not** contain a separately numbered “Brazil free-shipping never earns back” factor. That is our R2 formulation, not the company’s.

---

## 4. Factors that were under-weighted

Decision-useful additions, not a 40-row rewrite:

1. **Ads as a risk, not only an opportunity (#20).** A merchant ads-spend cut in a Brazil consumption scare would hit the high-margin line just reconstructed (TTM envelope ~$1.7–2.1bn). Add as a leading indicator under R5, not a new high-P row.
2. **Customer-funds / processor / card-network (#11–#13).** Open question #9 is the right workstream. 10-K language is stronger than the current R6 wording.
3. **App-store distribution (#4).** Low probability, high-impact tail if Apple/Google change fee or fintech rules in BR/MX.
4. **AI/ML (#3).** Labor/regulatory, not a 2026 P&L driver. Watch only.
5. **Category/manufacturer (#9–#10).** The Casas Bahia partnership was an assortment patch for bulky goods. The 10-K already said category gaps and manufacturer limits are material. See the 2026-08-19 update.
6. **Fulfillment-network crime and construction delay (#18).** Specific 10-K language not previously in the register. Leading indicator: Envios disruptions, warehouse-opening delays in letters.

---

## 5. What this does *not* do

- Does not re-score R1–R10 probabilities. The 10-Q said no material change through 2026-06-30, and no 8-K has updated Item 1A since.
- Does not replace the credit deep-dive. 10-K lending text is qualitative; the quantitative aging is still 10-Q Note 4.
- Does not complete an integrated forecast workbook. That foundation gap remains.

**Working confidence that the 10-K inventory is now complete enough for underwriting:** ~70% (the summary plus the lending/logistics/ads full paragraphs were read; some later emerging-market paragraphs were scanned, not line-edited).
