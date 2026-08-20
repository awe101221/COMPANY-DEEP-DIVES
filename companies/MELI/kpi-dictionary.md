# MELI KPI dictionary

**Last updated:** 2026-08-20 (customer-funds mapping). Definitions from Q2 2026 shareholder letter, Q2 2026 10-Q Note 3, and 2025 10-K unless noted.

| KPI | Official definition | Units | Known definition changes | Where disclosed |
|---|---|---|---|---|
| Net revenues and financial income | GAAP top line after 2023 presentation change that combines service/product revenue with financial income | $ mn | 2023 recast in 10-K | 10-K/10-Q income statement |
| GMV | USD sum of completed Marketplace transactions, **excluding Classifieds** | $ mn | **From Q2 2025:** includes food-delivery transactions | Shareholder letter; 10-K “Other Data” |
| Items sold | Items sold/purchased on Marketplace, excl. Classifieds | millions | **From Q2 2025:** includes food delivery | Same |
| Unique active buyers | Users with ≥1 Marketplace purchase in the period | millions | **From Q2 2025:** includes food delivery. Annual figure is YTD/unique-in-year; quarterly is in-quarter | Same |
| Fintech MAU | Payers and/or collectors who, in the **last month of the period**, did one of: debit/credit payment; QR; logged-in off-platform checkout/link; investment/savings; active insurance; outstanding loan current or NPL <90d; received a sale payment on or off marketplace | millions | Replaced “Unique Active Users” as of 1 Jan 2024. 10-K 2025 wording on insurance/loan slightly differs from Q2’26 letter (“has an active insurance policy” / “outstanding loan up to date or NPL below 90 days”) | Letter; 10-K fn (2) |
| TPV | USD sum of all Mercado Pago transactions, marketplace + non-marketplace, **excluding P2P** | $ mn | P2P excluded from 1 Jan 2024; 2023 recast | Letter; 10-K |
| TPN / total payment transactions | Count of Mercado Pago transactions excl. P2P | millions | P2P excluded from 1 Jan 2024 | Letter |
| Acquiring TPV | Settled volume via Mercado Pago processing: (1) POS, (2) Marketplace commerce, (3) checkout/link, (4) QR | $ mn | Replaced “Total volume of payment on marketplace” as of 1 Jan 2024 | Letter; 10-K |
| NIMAL | (Credit revenues − PDA − funding costs) / average portfolio, **excluding loan-sale results**. 10-K: annualized. Letter: “usually expressed as % of average portfolio” | % | Watch mix (cards vs consumer/merchant) | Letter; 10-K fn (9) |
| 15–90 NPL | Share of loan portfolio 15–90 days past due (letter). 10-Q aging allows reconstruction | % | Not a 90+ NPL. Write-off at 360 days | Letter; 10-Q Note 4 |
| FX-neutral / local-currency growth | Apply **prior-year monthly average FX** to current-year months. Excludes intercompany allocations. **Does not** adjust for local inflation or inflation-offset pricing | % | For 2026: uses 2025 monthly rates | Letter; 10-K |
| Operating margin | Income from operations / net revenues & financial income | % | GAAP | Letter |
| Net income margin | NI / net revenues & financial income | % | GAAP | Letter |
| Adjusted EBITDA | NI + D&A − interest income + interest expense + FX losses + tax (10-K also + equity in affiliate) | $ mn | Non-GAAP | Letter / 10-K |
| Net debt | Loans payable + operating leases − (unrestricted cash + eligible ST/LT investments). Excludes restricted cash, guarantee securities, VIE securitization investments, equity at cost | $ mn | Non-GAAP; **includes leases** | Letter |
| Adjusted FCF | CFO − customer-fund/restricted-cash build − capex − Δ loans receivable + net fintech funding. From Q2 2025 also adjusts management-restricted cash and digital assets | $ mn | Definition widened Q2 2025 | Letter |
| Available cash, investments and digital assets | Unrestricted cash + eligible investments + digital assets (from Q2 2025). 10-Q net-debt recon: GAAP cash **minus** cash restricted by management policies, plus eligible ST/LT investments (excludes guarantee securities, VIE securitization investments, equity at cost) | $ mn | Non-GAAP | Letter; 10-Q recon |
| Funds payable to customers | Liability for Mercado Pago wallet / payment balances owed to users | $ mn | Not the same as restricted cash | 10-Q BS |
| Restricted cash and cash equivalents | Cash ring-fenced as regulator mandatory guarantees, SPE collateral, or Meli Dólar holdings. Note 3 prints the regulator. **Not 1:1** with funds payable (81.8% coverage at 2026-06-30) | $ mn | Brazil BCB guarantee is 85.2% of the 6/30 pile | 10-Q Note 3 |
| Amounts payable due to credit and debit card transactions | Settlement liability to card networks / issuers. Different object from funds payable | $ mn | Sit against credit-card receivables, not wallet cash | 10-Q BS |
| Commerce (revenue) | Marketplace fees, shipping, 1P, ads, classifieds, membership, ancillary | $ | Segment/letter classification, not a GAAP segment | Letter |
| Advertising / Mercado Ads | Letter: “ad sales” inside Commerce. 10-K: advertising sales fees inside Commerce services (Product Ads, Brands Ads, Display, Video; Display/Video also off-platform). **Not a GAAP line after aggregation** | $ and % of GMV | Company printed ads **as % of GMV** through Q4 2024 (last print 2.1%). From 2025 letters: **USD and FXN growth only**, plus qualitative share/margin comments. Food-delivery GMV inclusion from Q2 2025 slightly dilutes ads/GMV vs a merchandise-only base | Letters; 2025 10-K; reconstruction in `ads-revenue-reconstruction-2026-08-17.md` |
| Fintech (revenue) | Off-platform fees, financing, credit interest, Mpago investment income net of BR pass-through, MPOS sales | $ | Same | Letter |
| Ecosystemic users | Users engaging **both** marketplace and Mercado Pago | n/a | Management metric; not in 10-Q | Q2’26 letter |
| MELI+ subscribers | Loyalty program subscribers | n/a | +72% YoY Q2’26 (mgmt); absolute not disclosed | Letter |
| AUM | Mercado Pago assets under management | $ bn | $23bn Q2’26; AUM/user $264 (mgmt) | Letter |
| Credit portfolio | Management’s $16.4bn Q2 figure matches 10-Q **gross** loans receivable $16,375mn | $ | Always state gross vs net | Letter vs 10-Q Note 4 |

## Reconciliation notes

- **GMV is not revenue.** Q2 2026 GMV $21.9bn vs revenue $10.2bn. Commerce take-rate including 1P/shipping/ads is not a clean 3P take-rate.
- **TPV >> GMV** because of off-platform acquiring, bills, wallet, cards.
- **CFO >> owner earnings** because of funds payable to customers and credit-related working capital. Restricted cash is **not** excess cash; funds payable is **not** ordinary net debt. See `customer-funds-2026-08-20.md`.
- **15–90 NPL ≠ 90+ NPL.** See credit deep-dive.
- **Ads $ ≠ a GAAP line.** After Q4 2024 the company stopped printing ads/GMV. Dollar figures in `ads-revenue-reconstruction-2026-08-17.md` are calculations, not reported actuals.
