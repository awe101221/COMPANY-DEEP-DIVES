# BCB payments-institution e-money safeguard — 2026-08-22

**Question:** What *statutory ratio* and eligible-asset list apply to Mercado Pago’s Brazil customer-fund pile, and does that change the EV / ALM reading?  
**Status:** Leftover of open question #9 after the 2026-08-20 dollar map on PR #8 (`customer-funds-2026-08-20.md`). This memo does **not** redo that map.  
**As-of:** 2026-08-22. Rule text is Resolução BCB nº 80 (DOU 2021-03-29). Balance-sheet figures are 2026-06-30.

Epistemic labels are marked. Arithmetic is **my calculation** on reported 10-Q figures.

---

## 1. Bottom line

Brazil’s customer-fund rule is a **100% safeguard**, not a bank reserve.

Resolução BCB nº 80, art. 22 (in force 2021-05-03; Resolução BCB nº 494/2025 later changed *authorization* calendars, not art. 22) requires an *emissor de moeda eletrônica* to hold **liquid resources corresponding to** prepaid e-money balances at STR close, plus in-transit e-money and amounts received but not yet freely available to the payee. Eligible assets are only:

1. cash at Banco Central do Brasil in a Conta Correspondente a Moeda Eletrônica (CCME), or
2. Brazilian federal government securities in Selic (BRL, not FX-linked, max 540 days to maturity; repos allowed with a commercial bank).

That is **100% of the Brazil prepaid-wallet stock**, not the 21% demand-deposit *compulsório* that applies to banks. Coupon on the treasuries is free cash to the payment institution.

The 10-Q mapping is consistent with that statute and does **not** imply MELI is under-reserved on Brazil e-money:

| Object (2026-06-30) | $ mn | Label |
|---|---:|---|
| BCB mandatory-guarantee cash | 11,174 | Reported — Note 3 |
| BCB-restricted foreign-government securities | 202 | Reported — Note 3 fn (1) |
| **Brazil BCB ring-fence** | **11,376** | Calculated |
| Consolidated funds payable to customers | 16,035 | Reported — not Brazil-only |
| Brazil ring-fence / consolidated funds payable | 70.9% | Calculated — **not** the statutory test |
| Securities share of Brazil ring-fence | 1.8% | Calculated; was 9.1% at YE 2025 |

Art. 22 is tested against **Brazil prepaid e-money**, which the 10-Q does not isolate. The $2,921mn gap between consolidated funds payable and restricted cash (PR #8) is therefore **not** evidence of a Brazil shortfall. It is the rest of the group: Mexico / Chile / Argentina wallets, card-scheme collateral, Meli Dólar, and any residual that is economically a customer claim but is not Brazil prepaid e-money.

**Thesis: no change.** This raises confidence that the $13.1bn restricted-cash pile is a regulatory ring-fence, not hidden owner cash. The live ALM risk is wallet *growth* forcing more cash into CCME (already +$3.3bn of BCB cash in H1), not a secret fractional-reserve hole.

**Working confidence:** **75%** on the 100% reading (DOU text is unambiguous). **55%** that Note 3’s “cash in bank accounts (Central Bank of Brazil mandatory guarantee)” is specifically CCME. **50%** that the $202mn “foreign government debt securities” are Selic tesouro that satisfy art. 22 §6 (USD-parent “foreign” includes Brazil; duration is not disclosed).

---

## 2. What the statute says (reported fact)

Source: [Resolução BCB nº 80, de 25 de março de 2021](https://www.in.gov.br/en/web/dou/-/resolucao-bcb-n-80-de-25-de-marco-de-2021-310910168), DOU 2021-03-29, Seção 1, p. 69. In force 2021-05-03 (art. 27).

**Art. 3, I** defines an *emissor de moeda eletrônica* as a payment institution that manages a **prepaid** end-user payment account and transacts against e-money previously funded in that account. E-money is “recursos em reais armazenados em dispositivo ou sistema eletrônico” (art. 3 §1).

**Art. 22 *caput*:** those issuers “devem manter recursos líquidos **correspondentes aos** saldos de moedas eletrônicas mantidas em contas de pagamento,” measured at the close of the STR regular grid, **plus**:

- I — e-money in transit between payment accounts at the same institution; and
- II — amounts received for credit to a payment account that are not yet freely available to the destination user.

“Correspondentes aos” is the ratio. There is no 80%, 90%, or haircut in the article. Secondary commentary (e.g. ABCripto consultation reply) restates this as statutory 100% protection of the e-money stock. I treat 100% as the legal reading, not a MELI disclosure.

**Art. 22 §1 — eligible assets, exclusive list:**

- I — *espécie* at Banco Central do Brasil; or
- II — *títulos públicos federais* registered in Selic.

**§2:** cash must sit in the issuer’s CCME, on the STR close *before* the extra PIX Conta PI window. Resolução BCB nº 237 (2022-08-24) is the CCME operating rule.

**§3–§5:** Selic allocation may be via repo; the repo counterparty must be a commercial bank / *caixa*; free rehypothecation of the pledged securities is forbidden.

**§6 — security screens:** BRL-denominated; bought in the secondary market; **maximum 540 days** to maturity; not FX-referenced.

**§8:** coupon / gains on the treasuries are **freely usable** by the issuer and *may* be shared with payment-account holders. The residual yield on the ring-fence is owner earnings, not trapped principal.

**Art. 23:** a commercial bank that issues e-money must use **cash only** (no Selic book). Mercado Pago’s Brazil payments entity is listed by BCB open data as **Mercado Pago IP Ltda.** (CNPJ 10.573.521/0001-91), an *instituição de pagamento*, not a commercial bank. Art. 23’s cash-only constraint therefore does **not** apply. The $202mn securities line is legally available to an IP.

**Resolução BCB nº 494 (2025-09-05)** rewrote arts. 9–13 authorization clocks (including a May 2026 filing window for legacy unauthorized e-money issuers). It did **not** amend art. 22. Do not read 494 as a reserve-ratio change.

**Contrast, not the MELI rule:** BCB’s published *compulsório* table applies a **21%** rate to bank sight deposits after a R$500mn deductible (Resoluções BCB 189/2022 and later). Using 21% on Mercado Pago wallets would be a category error.

---

## 3. How the 10-Q sits on the statute

Source: [Q2 2026 10-Q](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000023/meli-20260630.htm) Note 3. Dollar map and 81.8% / 85.2% ratios are on PR #8; not repeated as new work.

**Brazil ring-fence (calculated):**

| | 2026-06-30 | 2025-12-31 | Δ H1 |
|---|---:|---:|---:|
| BCB mandatory-guarantee cash | 11,174 | 7,865 | +3,309 |
| BCB-restricted ST foreign-government debt | 202 | 786 | −584 |
| **Sum** | **11,376** | **8,651** | **+2,725** |
| Securities / sum | 1.8% | 9.1% | — |

H1 they **shifted the Brazil book from Selic-like securities into cash at BCB**. That is an asset-mix choice inside art. 22 §1, not a ratio change. A hypothetical BCB “cash-only” rewrite of art. 22 (the bank treatment in art. 23) would force the remaining $202mn into CCME — **3.0%** of management available cash $6,751mn. De minimis.

**What the 10-Q does not give:** Brazil-only funds payable. So I cannot compute `BCB ring-fence / Brazil e-money` and tick the 100% box from MELI’s own numbers. The statutory test is still 100%; the disclosure is group-level.

**Inference (not a legal opinion):** calling the cash line a “mandatory guarantee” is the US-GAAP label for the art. 22 / CCME pile. Calling the $202mn “foreign government debt securities … restricted due to the Central Bank of Brazil’s mandatory guarantee” is the US-parent label for Brazilian (or other) sovereigns pledged to that same rule. If some of the $202mn failed §6 (duration >540 days, or a non-Brazilian sovereign), MELI would have to hold *more* CCME cash to stay at 100%. That residual risk is small in dollars.

**Other-country leftovers (not read to a statute this run):**

| Regulator named in Note 3 | Restricted cash 6/30 | Share of restricted |
|---|---:|---:|
| CNBV (Mexico) | 892 | 6.8% |
| CMF (Chile) | 290 | 2.2% |
| BCRA (Argentina) | 360 | 2.7% |
| BCU (Uruguay, in investments) | 16 | n/a — off the cash line |

Mexico is the next legal read if #9 is reopened. It is not the concentrated pile.

---

## 4. What would actually move cash

| Scenario | Direction | Size (order of magnitude) | Status |
|---|---|---|---|
| Brazil prepaid wallets keep growing | More cash locked in CCME / Selic | Already +$2.7bn Brazil ring-fence in H1; +$3.3bn BCB *cash* | Live, in the print |
| BCB forces cash-only (art. 23 treatment) | Securities → CCME | $202mn | Not proposed |
| BCB adds a 10 ppt buffer above 100% | Extra lock-up from available cash | ~$1.1bn ≈ 17% of $6.75bn available cash, *if* applied to today’s $11.4bn base | Hypothetical; no sourced proposal |
| BCB cuts the ratio below 100% | Releases owner cash; worse user protection | Up to the released slice of $11.4bn | Hypothetical; politically hard |
| BCB reclassifies some currently unrestricted residual as e-money | Top-up from available cash | Unknown; the $2.9bn group residual is the ceiling, not the Brazil number | Unknown |
| CCME operational shortfall (STR timing, PIX window) | Intraday top-up from available cash | Not disclosed | Operational tail |

The path that is **already happening** is (1): wallet growth consumes cash. That is already in H1 adj. FCF ($158mn after a $2,023mn customer-fund / restriction add-back). The path that would *change the thesis* is a **new** ratio or a reclassification of the residual, not the discovery that the current ratio is 100%.

---

## 5. Investment implications

- **EV quality:** the 2026-08-16 reverse DCF’s refusal to treat $13.1bn restricted cash as excess cash is now statute-backed for the Brazil 85% of that pile. No DCF rebuild. Friday 2026-08-21 close $1,922.73 restates EV to **$103.90bn** (50,697,301 × $1,922.73 + $6.425bn net debt). +4.2% vs the $1,844.58 original; +0.04% vs the 2026-08-20 close used on PR #9. Still inside the “do not rebuild unless >10%” rule.
- **R6 / R7:** the concentrated payments-regulation risk is Brazil wallet growth and a possible future BCB rewrite, not “MELI is running a 20% reserve.” Probability on R6/R7 is **not** revised on a statute that has been in force since 2021.
- **Yield:** art. 22 §8 says treasury coupon is free. Shifting $584mn of securities into non-interest CCME cash in H1 is a small owner-earnings give-up for operational / PIX reasons. Not sized further; Selic is 14.00% as of 2026-08-05, but CCME cash yield is not disclosed.
- **Argentina is still not the float.** BCRA guarantee cash is $360mn. Argentina’s thesis weight remains direct contribution and credit (PR #9 expediente), not trapped wallets.

---

## 6. What is still unknown

1. Brazil-only funds payable / prepaid e-money stock, so the 100% test cannot be ticked from the 10-Q.
2. Whether every dollar of the $202mn satisfies art. 22 §6 (tenor, Brazilian federal issuer).
3. Intraday CCME vs STR / PIX window mechanics at Mercado Pago IP Ltda.
4. CNBV / CMF / BCRA / BCU statutory formulas (dollar amounts are on PR #8).
5. Any live BCB consultative document proposing a ratio *above* 100%. None found this run; absence is not proof.

**Falsifier for this memo’s 100% reading:** a later BCB circular that inserts a haircut, a <100% ratio, or an extra buffer, or a 10-Q that prints Brazil funds payable well above the $11.4bn ring-fence.

---

## 7. Sources

Primary: Resolução BCB nº 80 arts. 3, 22–23, 27 ([DOU](https://www.in.gov.br/en/web/dou/-/resolucao-bcb-n-80-de-25-de-marco-de-2021-310910168)); Resolução BCB nº 237 (CCME); Resolução BCB nº 494/2025 (authorization only); Q2 2026 10-Q Note 3; BCB open-data institution page for Mercado Pago IP Ltda. (CNPJ 10.573.521/0001-91).  
Contrast: BCB *compulsório* summary (21% bank sight deposits).  
Prior work: `customer-funds-2026-08-20.md` on PR #8; `reverse-dcf-2026-08-16.md`.  
Price: Yahoo / StockAnalysis 2026-08-21 close $1,922.73.
