# Brazil-only funds payable — Mercado Pago IP Ltda COSIF

**Question:** What is Brazil prepaid e-money / funds payable, and does it clear the Resolução BCB nº 80 art. 22 100% test from Mercado Pago’s own regulatory books?  
**Status:** Leftover of open question #9 after the 2026-08-20 dollar map (PR #8), the 2026-08-22 BCB ratio memo (PR #10), and the 2026-08-27 MX/CL/AR statutes (PR #14). This memo does **not** redo those.  
**As-of:** 2026-08-28. Latest public COSIF date-base is **2026-03**. April–June 2026 balancetes publish **2026-08-31** (BCB Comunicado 44.132/2025).

Epistemic labels are marked. USD conversions are **my calculation** on official PTAX venda. Arithmetic is mine.

---

## 1. Bottom line

The 10-Q still does not print Brazil-only funds payable. Banco Central do Brasil **does**, monthly, in Mercado Pago IP Ltda.’s COSIF 4010 balancete (CNPJ 10.573.521/0001-91).

As of **2026-03-31** (latest public file):

| Object | R$ bn | USD $ mn at PTAX venda 5.2194 | Label |
|---|---:|---:|---|
| Conta de pagamento pré-paga (41930000) | 51.058 | **9,782** | Reported — COSIF |
| Same, STR-close control (30966000) | 50.414 | 9,659 | Reported — COSIF; art. 22 measurement base |
| BCB depósitos de moeda eletrônica / CCME (14202000) | 50.422 | 9,660 | Reported — COSIF |
| Títulos vinculados a saldos em conta pré-paga (13625000) | 1.011 | **194** | Reported — COSIF; **equals** Q1 10-Q BCB-restricted securities |
| Eligible (CCME + títulos) | 51.433 | 9,854 | Calculated |
| Cover of STR-close stock | **102.0%** | — | Calculated |
| Consolidated funds payable (10-Q) | — | 14,145 | Reported — group, not Brazil-only |
| Brazil prepaid / group funds payable | — | **69.2%** | Calculated |

Art. 22 is tested against the **STR-close** prepaid stock, not the slightly larger 41930000 liability. Eligible assets cover that stock with a ~2 ppt buffer. The YE 2025 tesouro line converts at official PTAX to **$786mn**, which is the exact 10-Q footnote. The Q1 2026 tesouro line converts to **$194mn**, again the exact 10-Q footnote. Those two matches are the reason I trust the COSIF-to-10-Q map.

This does **not** change the $6.425bn net-debt plug. It replaces the prior “Brazil is ~71% of group funds payable, inferred from the ring-fence” statement with a **Brazil-entity liability**.

**Thesis: no change.** Confidence that restricted cash is a regulatory ring-fence, not hidden owner cash, rises. The live ALM fact is still wallet *growth* into CCME.

**Working confidence:** **80%** that 41930000 / 30966000 are the Brazil prepaid-wallet stock that art. 22 cares about. **90%** that 13625000 is the 10-Q “foreign government debt securities … Central Bank of Brazil mandatory guarantee.” **60%** that 41930000 is a clean subset of US-GAAP “funds payable to customers” (the residual $4.4bn is other-country wallets plus any non-e-money customer claims; I cannot split that residual from COSIF).

---

## 2. What was missing, and what this file is

PR #8 mapped group funds payable $16,035mn vs restricted cash $13,114mn as of 2026-06-30. PR #10 showed art. 22 is a 100% safeguard and that the Brazil ring-fence was $11,376mn — **70.9%** of group funds payable — but could not tick the statutory test because the 10-Q does not isolate Brazil e-money. PR #14 closed the MX/CL/AR *statutes*. The leftover named on those branches was **Brazil-only funds payable**.

BCB publishes individualized COSIF 4010 files at:

`https://www4.bcb.gov.br/fis/cosif/cont/balan/individualizados/{AAAAMM}/4010/{AAAAMM}-4010-10573521.ZIP`

April / May / June 2026 files return 404 as of 2026-08-28. Comunicado 44.132/2025 puts those three date-bases on **31 August**. That is the next refresh, not a hole in this memo.

---

## 3. Reported COSIF stock (R$)

Source: BCB individualized balancetes, Mercado Pago IP Ltda., documento 4010. Semicolon CSV, Latin-1, saldo in reais with two decimals.

| COSIF | Name | 2025-12 | 2026-01 | 2026-02 | 2026-03 |
|---|---|---:|---:|---:|---:|
| 41930000 | Conta de pagamento pré-paga | 49.476bn | 47.769bn | 48.352bn | **51.058bn** |
| 30966000 | Conta pré-paga no fechamento do STR | 47.490bn | 46.352bn | 47.330bn | **50.414bn** |
| 30969000 | Conta pré-paga — saldo médio | 32.634bn | 34.861bn | 37.070bn | 38.426bn |
| 14202000 | BCB — depósitos de moeda eletrônica | 44.240bn | 45.177bn | 47.288bn | **50.422bn** |
| 13625000 | Títulos vinculados a saldos em conta pré-paga | 4.322bn | 2.113bn | 0.999bn | **1.011bn** |
| 14206000 | BCB — conta de pagamento instantâneo (PIX) | 2.779bn | 2.608bn | 1.561bn | 1.071bn |

H1 they **shifted the Brazil book from Selic-like títulos into CCME cash**, the same mix shift the 10-Q already showed ($786mn → $202mn of BCB-restricted securities from YE to June; Q1 is the midpoint at $194mn). That is an art. 22 §1 asset-mix choice, not a ratio change.

**Do not add** 14206000 (PIX Conta PI) into the art. 22 pile. It is operational SPI liquidity, not the e-money safeguard.

**Do not treat** 49901000 (obrigações por transações de pagamento, R$6.890bn at March) or 44160000 (relações interfinanceiras — transações de pagamento, R$11.441bn) as prepaid wallets. Instrução Normativa BCB nº 687 (in force for date-bases from February 2026) sends *payment-transaction* payables to 4.9.9 and keeps prepaid-account payables in the 4.1.9 / 41930000 family. Those two lines are acquiring / scheme settlement, closer to the 10-Q “amounts payable due to credit and debit card transactions” object.

---

## 4. USD conversion and 10-Q reconciliation

Official PTAX venda (BCB Olinda):

| Date | PTAX venda | Source |
|---|---:|---|
| 2025-12-31 | **5.5024** | [CotacaoDolarDia](https://olinda.bcb.gov.br/olinda/servico/PTAX/versao/v1/odata/CotacaoDolarDia(dataCotacao=@dataCotacao)?%40dataCotacao='12-31-2025'&%24format=json) |
| 2026-03-31 | **5.2194** | Same API, `03-31-2026` |

| | 2025-12-31 | 2026-03-31 |
|---|---:|---:|
| Brazil prepaid (41930000) at PTAX | **$8,992mn** | **$9,782mn** |
| STR-close stock at PTAX | $8,631mn | $9,659mn |
| CCME at PTAX | $8,040mn | $9,660mn |
| Títulos at PTAX | **$786mn** | **$194mn** |
| 10-Q BCB-restricted securities | $786mn | $194mn |
| 10-Q BCB mandatory-guarantee *cash* | $7,865mn | $9,465mn |
| Group funds payable | $13,029mn | $14,145mn |
| Brazil prepaid / group FP | **69.0%** | **69.2%** |
| Residual group FP | $4,037mn | $4,363mn |
| Art. 22 cover of STR-close | 102.3% | 102.0% |

**Tesouro match (reported fact + calculation):** 4,322,423,267 / 5.5024 = 785.6 → **$786mn**. 1,011,255,057 / 5.2194 = 193.7 → **$194mn**. Those are the 10-Q Note 3 footnotes on the Q2 and Q1 filings.

**CCME vs 10-Q BCB cash:** PTAX-converted CCME sits **~2.1–2.2%** above the 10-Q cash line at both dates ($8,040 vs $7,865; $9,660 vs $9,465). I do **not** invent a MELI translation rate to close that gap. Two clean explanations, both unproven: (1) MELI’s period-end BRL rate is not PTAX venda; (2) a small slice of COSIF 14202000 is classified elsewhere in US-GAAP. The gap is too stable to be noise and too small to change the 100% / 69% conclusions.

**June 2026 (not in COSIF yet):** PR #10’s Brazil ring-fence $11,376mn / group FP $16,035mn = 70.9%. That is still an *asset-side* inference. If the 69% liability share held through Q2, Brazil prepaid would be ~$11.1bn — inside a few hundred million of the $11.4bn ring-fence. Wait for the 2026-08-31 COSIF file before writing that as a fact.

---

## 5. What this does *not* say

- It does **not** give Mexico / Argentina / Chile funds payable. Those remain the residual ~$4.4bn plus any group-level items that are not prepaid e-money.
- It does **not** prove unused-commitment economics. COSIF 33410000 (“compromissos de crédito … não canceláveis”) is R$42.481bn at March (~$8.1bn at PTAX). The Q2 10-Q unused *card* lines are $14.0bn at the group. Different object, different date. Do not splice.
- It does **not** size owner yield on the ring-fence beyond the already-known art. 22 §8 point. COSIF 81198000 (despesas de remuneração de conta pré-paga) is a YTD expense, not a clean yield.
- Pillar 3 4Q 2025 exists ([MP IP PDF](https://http2.mlstatic.com/storage/cx-support-fcm-api/fcm-pub-os-prod/content-hub/mdanze/pilar%203%20-%204t2025.pdf)). It is a prudential-conglomerate capital report, not a prepaid-wallet stock. 1Q/2Q 2026 Pillar 3 was not retrieved this run.

---

## 6. Investment implications

- **EV quality:** Brazil, ~69% of group funds payable at Q1, is a 100% cash-or-Tesouro lock-up on the entity’s own books. The reverse DCF’s refusal to treat restricted cash as excess cash is now ticked at the Brazil *liability*, not only at the asset footnote.
- **Concentration:** a BCB rewrite of art. 22, or a reclassification of the residual $4.4bn into e-money, is still the payments-regulation risk that matters. MX/AR statutes (PR #14) already said those piles are 100% too; they are just smaller.
- **FCF:** wallet growth continues to consume cash (CCME +R$6.2bn in three months). That is already in H1 adj. FCF. This memo does not add a new cash drain; it names the drain’s Brazil-entity size.
- **No DCF rebuild.** 2026-08-27 close $1,930.75 is +4.7% vs the $1,844.58 print. Trigger remains $2,029.

---

## 7. Falsifiers and next file

1. 2026-06 COSIF (due 2026-08-31) prints 41930000 well above the $11,376mn June ring-fence after a reasonable FX conversion — that would break the 100% reading or the COSIF-to-10-Q map.
2. A later 10-Q that prints Brazil funds payable far from ~69% of the group line.
3. A BCB circular that inserts a haircut, a <100% ratio, or an extra buffer (same falsifier as PR #10).

**Next research:** pull `202606-4010-10573521.ZIP` on or after 2026-08-31 and repeat the table. Do not redo MX/CL/AR statutes or the dollar map unless the 10-Q changes.

---

## 8. Sources

Primary: BCB individualized COSIF 4010 for CNPJ 10573521, date-bases 202512–202603; BCB PTAX Olinda; [Q1 2026 10-Q](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000017/) Note 3 ($9,465mn BCB cash; $194mn BCB securities; $14,145mn funds payable); [Q2 2026 10-Q](https://www.sec.gov/Archives/edgar/data/1099590/000109959026000023/meli-20260630.htm) Note 3; Resolução BCB nº 80 art. 22 (already sourced on PR #10); BCB Comunicado 44.132/2025 (balancete calendar); IN BCB nº 687/2025 (4.9.9 vs prepaid).  
Prior work: `customer-funds-2026-08-20.md` (PR #8); `bcb-reserve-ratio-2026-08-22.md` (PR #10); `customer-funds-mx-cl-ar-2026-08-27.md` (PR #14).
