# Argentina mora mix: Galperin posts vs Fernández / Pública

**As-of:** 2026-08-26.  
**Status:** Incremental memo. Does not replace the Argentina country dossier or the 2026-08-21 BA expediente memo on PR #9 (`argentina-consumer-defense-2026-08-21.md`).  
**Question:** Do the 2026-08-25 Galperin posts, and the Matías Fernández / Pública analysis he amplified, change what we can say about Mercado Pago’s Argentina credit risk?

---

## 1. What is new (timing vs last run)

The last successful scheduled run closed ~12:30 UTC on 2026-08-25 (PR #12: Brazil CFO card interview). Infobae timestamped Galperin’s posts **25 Aug 2026, 12:30 p.m. EST** (16:30 UTC) — after that cutoff. BAE’s stamp is 16:39 Argentina time the same afternoon.

This is the first **founder-attributable quantitative defense** of Mercado Pago’s Argentina mora mix. It is **not** an 8-K, not a 10-Q cut, and not a Mercado Pago descargo on the Buenos Aires consumer-defense expediente.

---

## 2. What Galperin said (founder claim via press)

Infobae, iProfesional, and BAE quote the same two X posts. X/MCP was down this run; the quotes below are journalism reprints, not a primary X pull.

1. Median mora of public banks is **ARS 1.4 million**; Mercado Libre’s is **ARS 0.1 million**. He framed critics as ignoring credits that *are* paid on time.
2. Mercado Libre is **less than 3%** of system mora *dollars*; Banco Nación and Banco Provincia together are **15%**.

**Epistemic status:** founder / Executive Chairman social-media claims (10-K title: Executive Chairman; several outlets still write “CEO”). Not a company filing. He chose the **dollar-share and median-ticket** cuts and did not quote the person-count cut from the same analysis.

---

## 3. What Fernández / Pública published (third-party, not independent)

The posts amplify a note by **Matías Fernández** (consultora Pública; former Macri production-ministry adviser) titled, in reprints, *“Todo lo que querías saber de la mora\* (pero tenías miedo de preguntar)”*. Method, as described by Infobae / BAE / La Nación: June 2026 **BCRA Central de Deudores** microdata crossed with the **ARCA** taxpayer register.

Numbers that appear in more than one outlet (Infobae carries the tightest Fernández quotes):

| Object | Print | Label |
|---|---|---|
| People with ≥1 debt in mora | **5.86 million** (June 2026) | Third-party estimate |
| Person-mora rate among debtors | **13.6%** (Oct 2024) → **27.8%** (June 2026) | Third-party estimate |
| MELI / Mercado Pago share of *people* in mora | **19.0%** | Third-party estimate |
| MELI / Mercado Pago share of *dollars* in mora | **2.9%** | Third-party estimate |
| MELI median debt in mora | **ARS 116,000** | Third-party estimate |
| People with some MELI financing | **>6.5 million** | Third-party estimate |
| Traditional banks’ share of mora *dollars* | ~**65%** (privates ~45%; Nación+Provincia ~15%) | Third-party estimate |
| Small-ticket block (fintech + quick loans + non-bank cards + recovery books) | **90.6%** of people / **26.2%** of dollars | Third-party estimate |
| Fernández’s verdict | “Mercado Pago es el mejor alumno, no el peor.” | Author interpretation |

Fernández, via Perfil’s reprint, says he is **not a mora specialist** and that the joins can contain errors.

**Independence:** La Nación (2026-08-25, *“El autor del tuit… trabaja para Mercado Libre”*) reported that Pública lists Mercado Libre / Mercado Pago among clients and that Fernández **told La Nación he still provides services to the company**. Treat the 19% / 2.9% pair as a **vendor-adjacent reconstruction**, not an independent audit. I could not retrieve the full La Nación HTML this run (paywall / 429); the attribution is from the indexed article and is consistent with BAE’s note that Leandro Renou had already said MELI is a Pública client.

---

## 4. Official BCRA prints that are *not* MELI

[Informe sobre Bancos, junio de 2026](https://www.bcra.gob.ar/publicaciones/informe-sobre-bancos-junio-de-2026/), published **2026-08-21** (after PR #9; not ingested on that branch):

| Object (June 2026, *banks*) | Official print |
|---|---|
| Private-sector irregularity | **7.6%** (−0.1 ppt m/m) |
| Household irregularity | **12.8%** (flat; first pause after a long rise) |
| Corporate irregularity | **3.5%** |
| Estimated PD on private-sector credit | **2.6%** |
| Provisions / irregular book | **86.6%** |
| Real peso private-sector credit | **+1.7% m/m / +2.6% YoY** |

This is the **bank** system. It is not Mercado Pago, not PNFC/fintech, and not Fernández’s Central-de-Deudores person-count universe. The last official *fintech* prior remains the BCRA PNFC report used on PR #9: Fintech irregularity **26.2%** as of **February 2026**. No newer PNFC print was found this run.

Do **not** write 7.6%, 12.8%, 19%, 2.9%, or 26.2% into MELI’s book.

---

## 5. Calculations (mine)

FX used: BAE’s Banco Nación **venta ARS 1,530 / USD** on 2026-08-25. Third-party screen, not a BCRA series extract.

| Object | Result | Formula / caveat |
|---|---|---|
| Fernández median mora in USD | **~$76** | 116,000 / 1,530 |
| Galperin’s rounded $0.1 million in USD | **~$65** | 100,000 / 1,530 |
| Public-bank median $1.4 million in USD | **~$915** | 1,400,000 / 1,530 |
| Provincia median $1.75 million in USD | **~$1,144** | 1,750,000 / 1,530 |
| Implied MELI people in mora | **~1.11 million** | 0.19 × 5.86 million — *only if both Fernández figures share a universe* |
| Implied person-mora among MELI financed users | **~17%** | 1.11 / 6.5 — stacked third-party; **not** a 90+ NPL |

Do not multiply the median by the headcount to recover a MELI mora book. Medians are not means, and Fernández does not publish MELI’s dollar book.

BA expediente cash cap from PR #9 is still de minimis: ARS 1,883 million / 1,530 ≈ **$1.23 million** vs Q2 Argentina DC $623 million.

---

## 6. What this does — and does not — resolve

**Progress vs open question #15 / the PR #9 leftover (“MP Argentina mora vs BCRA 26.2%”):**

- We now have a **founder-endorsed dollar-share claim** (<3% / 2.9%) and a **person-share claim** (19%) from the same non-independent reconstruction.
- Those two cuts can both be true: high inclusion, small tickets, many people late, little system-dollar risk.
- They still do **not** give a Mercado Pago Argentina 90+ NPL, vintage, or NIMAL. The 10-Q still has no country cut.

**How this sits next to other claims already in the file:**

| Claim | Source | Status |
|---|---|---|
| MP mora “in line with main private banks” | Management via Infobae 2026-08-14 | Still unverified. A *rate* claim, not a share claim. |
| Fintech irregularity 26.2% | BCRA PNFC, Feb 2026 | Industry prior. Not MELI. |
| Bank household irregularity 12.8% | BCRA Informe sobre Bancos, June 2026 | Official bank print. Not MELI. |
| Kicillof wallets 24.5% | Governor via press, 2026-08-20 | Political claim. Still not MELI. |
| Group 15–90 NPL 7.0% / 90–360 18.7% | Q2 10-Q Note 4 | Group, not Argentina. |

A ~17% person-mora among MELI financed users (calculation above) is **not** comparable to BCRA 12.8% or 26.2%. Different universe, different weighting, different delinquency definition.

**Legal / process leftovers (unchanged):**

- No Mercado Pago **descargo** on the BA expediente found as of 2026-08-26.
- No Juzgado N° 53 / Fiscalía N° 60 **collection-stay** order found. Diario de Cuyo (undated recap, retrieved 2026-08-26) still says the cautelar is only a request.

---

## 7. Investment transmission

Argentina remains **18% of Q2 revenue and ~40% of disclosed direct contribution**. That was already the thesis.

**If the 2.9% dollar-share is even directionally right**, Mercado Pago is not the system’s loss-dollar problem. Argentina credit would transmit to MELI through **provisions on a small-ticket book** and through **conduct remedies** (collection, CFT presentation, cooling-off), not through a bank-sized charge-off hole.

**If the 19% person-share is even directionally right**, the political and consumer-defense surface is large. That is the transmission that matters for the BA expediente, the Solano usury filing, and any future BCRA / Nación CFT rule. Galperin’s choice to quote only the dollar cut does not shrink that surface.

**Independence discount:** because Pública still works for MELI (La Nación, Fernández to LN), I would not raise the probability that “MP is the clean fintech” on this note alone.

**12-month paths for *this* node (subjective; not a 25/45/30 rewrite):**

| Path | Rough P | Why |
|---|---:|---|
| Political noise only; no book or product change | 50% | Fine still de minimis; no stay; Milei amplified the same note |
| Conduct / CFT / collection changes that slow AR originations or recoveries | 30% | 19% person-share keeps the file politically live |
| Court stay or national rate-cap | 15% | Would be a new event. Not in hand. |
| Next official print (PNFC or 10-Q AR cut) shows MP near private-bank 90+ | 5% | Would be the first *independent* confirmation |

---

## 8. What would change my mind

**Falsify “dollar risk is small”:** a 10-Q or letter that discloses Argentina consumer 90+ near the 26% fintech prior, or a charge-off / PDA print that is large vs the $623 million AR DC.

**Falsify “person-share is the live risk”:** a published descargo with a small complaint share, a withdrawn expediente, or a Juzgado rejection of the cautelar *and* a later BCRA print that shows fintech irregularity rolling over.

**Do not treat as proof of either:** Galperin’s <3%, Fernández’s 19.0/2.9, Kicillof’s 24.5%, or the group 7.0% 15–90 NPL.
