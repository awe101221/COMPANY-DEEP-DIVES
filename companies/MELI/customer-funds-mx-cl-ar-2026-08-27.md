# Customer-fund statutes: Mexico, Chile, Argentina — 2026-08-27

**Question:** After the Brazil BCB 100% e-money safeguard (PR #10, not on `main`), what is the statutory lock-up in Mexico, Chile, and Argentina?  
**Status:** First completed read of the three leftover formulas. Not a new dollar map.  
**As-of:** 2026-08-27. Balance-sheet dollars remain Q2 2026 10-Q (period ended 2026-06-30).

Epistemic labels are marked. This memo is **reported statute** plus **inference** about MELI’s licensed entities. It does **not** produce a country-level funds-payable split.

---

## 1. Why this leftover still mattered

The Q2 2026 10-Q already classifies customer funds as float, not excess cash (this branch: `reverse-dcf-2026-08-16.md`). Consolidated figures used here:

| Item | Amount | Label |
|---|---:|---|
| Funds payable to customers | $16.035bn | Reported — 10-Q |
| Restricted cash | $13.114bn | Reported — 10-Q |
| Restricted cash / funds payable | 81.8% | Calculated |
| Available cash, investments and digital assets | $6.751bn | Non-GAAP — 10-Q recon |
| Net debt (mgmt, incl. leases) | $6.425bn | Non-GAAP |

Open incremental work on PRs #8 and #10 (not merged into `main`) maps **$11,174mn** of restricted cash as a Banco Central do Brasil mandatory guarantee and a Brazil ring-fence of **$11,376mn**. This run does **not** re-audit those dollars. The leftover was the **other-country statutes**.

Mercado Pago operates in eight countries (2025 10-K / company dossier). Brazil, Mexico, and Argentina are the P&L-relevant three. Chile is the next licensed wallet. Colombia, Peru, Uruguay, and Ecuador remain unread this run.

---

## 2. Country-by-country statutes

### Mexico — 100% segregation by end of day; sight-deposit cap

**License (reported fact):** Diario Oficial de la Federación, 2022-05-11, authorized **MercadoLibre, S.A. de C.V., Institución de Fondos de Pago Electrónico** under LRITF arts. 11, 22, and 35 ([DOF oficio](https://dof.gob.mx/nota_detalle.php?codigo=5651692&fecha=11/05/2022)).

**Lock-up (reported statute):** *Ley para Regular las Instituciones de Tecnología Financiera* art. 46 ([Cámara de Diputados text](https://www.diputados.gob.mx/LeyesBiblio/pdf/LRITF.pdf)):

1. Own funds must be **segregated** from client funds; client funds must be identified by client.
2. While the ITF still holds the money, it must, **by the end of the receipt day**, place it in one of:
   - sight-deposit accounts in an authorized Mexican financial entity, **distinct** from the ITF’s own-funds accounts; or
   - one-day renewable *reportos* in Federal Government or Banco de México securities with credit institutions; or
   - an administration trust that only does those *reportos*.
3. For IFPEs specifically, the amount that may sit in sight-deposit accounts **cannot exceed** the greater of **1 million UDIS** or **2× the highest 24-hour redemption** in the last 365 days. Excess must therefore sit in the repo/trust sleeve.

**What this is not:** a 21% bank reserve. It is a **same-day 100% client-money lock-up** with a cap on uninvested cash. Banxico–CNBV *reglas conjuntas* of 2021-01-28 (DOF) are operational/security rules under arts. 48, 54, and 56; they do **not** replace art. 46.

**IPAB / deposit insurance:** IFPE client balances are not bank deposits. Protection is segregation plus eligible assets, not a deposit-insurance wrap. Company blog restates this; the statute is the source.

### Argentina — 100% in local-bank sight accounts; no SEDESA on the CVU

**Entity (reported, dated):** BCRA Comunicación “C” 89162 annex, register of PSPCP as of **2020-12-31**, lists **Mercadolibre S.R.L.** ([C89162](https://www.bcra.gob.ar/archivos/Pdfs/comytexord/C89162.pdf)). The 2025 10-K still lists Argentina as a Mercado Pago country. A 2026 live SEFyC certificate number was **not** retrieved this run.

**Lock-up (reported statute):** BCRA *Texto ordenado* — Proveedores de servicios de pago que ofrecen cuentas de pago, points 4.1.1–4.2.2 ([TO](https://www.bcra.gob.ar/archivos/Pdfs/Texord/t-snp-psp.pdf)), originating in Comunicación “A” 6859:

- 4.1.1: client funds in payment accounts must be available immediately and identifiable by client.
- **4.1.2: 100% of client funds must be on deposit, at all times, in peso sight accounts at financial entities in Argentina.**
- Optional, on the client’s express request: transfer out of the payment account into a local money-market fund, shown separately.
- 4.1.3: the PSP’s own operating account must be a **different** sight account.
- **4.2.2: balances in payment accounts are not bank deposits and do not have the deposit-insurance guarantees those deposits enjoy.**

**What this is not:** SEDESA coverage on the CVU itself. The pesos sit at a bank, so the *bank* book may have SEDESA; the client’s legal claim is on the PSP, not a bank deposit. Comunicación “A” 8407’s 2026 SEDESA ceiling increase (third-party press: $25mn → $50mn per person per bank from 2026-04-01) does **not** convert wallet balances into insured deposits.

Com. “A” 8432 (2026-05-06) updates PSP registration and adds “PSPCP as a service.” It does **not** change the 100% sight-account rule in 4.1.2.

### Chile — segregation plus a *net-of-flows* liquidity reserve

**License (reported fact):** Mercado Pago Emisora S.A. is a CMF-supervised special corporation; CMF Resolución N° 6.312 (2021-11-05) authorized it as a non-bank issuer of prepaid cards with funds provision (company [2023 memoria](https://http2.mlstatic.com/storage/cx-support-fcm-api/fcm-pub-os-prod/cx-support-mario-frontend/alcamacho/memoria_mercado_pago_emisora_chile_2023.pdf)). Mercado Pago Operador holds a separate operator license (La Tercera; company claim).

**Two different rules (reported statute):**

1. **Segregation of prepaid funds.** BCCH *Capítulo III.J.1.3*, Título II.B.vii: prepaid funds must be recorded and held **segregated** from the issuer’s other operations, in cash or Annex 2 instruments ([BCCH chapter](https://www.bcentral.cl/documents/33528/115568/CapIIIJ13.pdf)). Título II.B.v and Título I.3: the issuer is liable for captured balances and must reimburse on demand; CPF balances are in local currency and **do not accrue interest or indexation**.
2. **Liquidity reserve, not a second 100%.** Same chapter, Título II.B.v, as restated by CMF *Norma de Carácter General N° 541* (2025-07-23) numeral 2.2.2 ([NCG 541](https://www.cmfchile.cl/normativa/ncg_541_2025.pdf)):

\[
RL = \max(0.10 \times C_m,\ ALp - Pp - Frp)
\]

where \(C_m\) is the month-end minimum-capital requirement, \(ALp\) is liquid assets / CPF stock (item 2100.1), \(Pp\) is average merchant/other outflows in the rolling quarter, and \(Frp\) is average reimbursements to holders. Intra-issuer CPF transfers are excluded. Eligible reserve assets: Chilean bank current-account cash, ≤90-day local-bank CDs, or serial BCCH / Tesorería debt, unencumbered.

Minimum capital itself is \(\max(25{,}000\ \text{UF},\ 0.01\cdot PNR + 0.08\cdot RPILP + 0.03\cdot RPICP)\).

**Inference:** Chile is **not** a Brazil-style 100% cash-or-Tesouro test. Segregation exists, but the *reserve ratio* can collapse toward the 10%-of-capital floor when quarterly outflows are large relative to end-period CPF stock. Other-country revenue is ~5% of Q2 2026, so even a looser Chile sleeve is unlikely to move group EV. The dollar amount of Chilean CPF is **not disclosed**.

Annex 2 eligible-instrument list was not extracted in full this run.

---

## 3. Comparison with Brazil (already done elsewhere)

| Country | Entity | Statutory test | Eligible assets | Deposit insurance on the wallet? |
|---|---|---|---|---|
| Brazil | Mercado Pago IP Ltda. (PR #10) | Res. BCB 80 art. 22: **100%** of prepaid e-money | CCME cash or Tesouro ≤540 days | No FGC on the prepaid balance |
| Mexico | MercadoLibre, S.A. de C.V., IFPE | LRITF art. 46: **100%** by end of day; sight-deposit cap | Distinct sight accounts, 1-day govt/Banxico *reporto*, or admin trust | No IPAB on IFPE balances |
| Argentina | Mercadolibre S.R.L. (PSPCP) | BCRA TO 4.1.2: **100%** at all times | Peso sight accounts at local banks (optional money-market fund if client opts in) | No SEDESA on the CVU |
| Chile | Mercado Pago Emisora S.A. | Segregation (II.B.vii) **plus** \(RL=\max(0.1C_m, ALp-Pp-Frp)\) | Cash / Annex 2 for segregated funds; bank cash, ≤90-day CDs, BCCH/Tesorería for RL | Not a bank deposit |

Do **not** apply the 21% Brazilian bank *compulsório* to any of these. Do **not** apply Chile’s net-of-flows formula to Brazil, Mexico, or Argentina.

---

## 4. Investment arithmetic

**Reported / already on this branch:** restricted cash covers 81.8% of funds payable. The $6.425bn net-debt plug already excludes restricted cash. That classification is unchanged.

**Inference, not a new 10-Q fact:**

- Mexico and Argentina are **100%-style lock-ups**. Their wallet float should not be treated as excess cash any more than Brazil’s.
- Residual restricted cash outside the Brazil figure on PR #8/#10 (~$1.94bn if those dollars hold) is the natural MX + AR + CL + other + SPE bucket. This run **cannot** split it. A 10-Q that published Brazil-only funds payable, or MX/AR restricted cash, would close the leftover.
- Chile’s looser *reserve* formula is a documentation fact, not an EV plug. Other-country revenue is too small, and CPF dollars are unpublished.
- None of this changes the $6.425bn net-debt number or rebuilds the reverse DCF.

**Falsifier for this memo:** a later 10-Q/10-K that (a) shows Mexico or Argentina client funds held outside the art. 46 / 4.1.2 sleeves, or (b) prints a country funds-payable split that makes the residual restricted-cash bucket inconsistent with 100% MX/AR coverage.

---

## 5. What remains unread

- Brazil-only funds payable (leftover of PR #10).
- Country-level restricted-cash / funds-payable dollars.
- Colombia, Peru, Uruguay, Ecuador statutes.
- Chile Annex 2 instrument list; Mercado Pago Emisora’s latest CMF C75 / capital filing.
- 2026 live BCRA SEFyC certificate number for Mercadolibre S.R.L.
- Whether any Mexican IFPE cash sits in the 1-million-UDI sight-deposit sleeve vs *reporto*.
