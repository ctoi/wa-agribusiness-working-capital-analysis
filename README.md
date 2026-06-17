# WA Agribusiness Working Capital Stress Analysis
## Wheatbelt Agronomy Supplies Ltd | Commercial Analyst Portfolio Project | May 2026

> **Disclaimer:** Wheatbelt Agronomy Supplies Ltd (WAS Ltd) is a fictional entity created for illustrative purposes. All financial inputs are derived from publicly available data sources as cited. This analysis does not constitute financial or investment advice.

---

## Research Question

Under simultaneous input cost inflation and debtor payment extension, at what point does WAS Ltd's working capital position become unsustainable - and which variable poses the greatest individual threat to solvency?

---

## Project Purpose

This project models the working capital stress faced by a fictional WA agribusiness distributor under simultaneous gross margin compression and debtor payment extension. 

It is structured as a CFO-facing working capital stress framework and is designed to demonstrate:
- commercial working capital analysis using verified public and industry data
- translation of input cost inflation and debtor deterioration into full-year earnings and liquidity pressure
- scenario analysis across base, stress, and recovery cases
- sensitivity analysis across pass-through rate and debtor days
- a CFO-facing commercial memorandum supported by a fully auditable Excel model

---

## Key Findings

- A verified 51.3% blended urea cost increase (World Bank Pink Sheet, May 2026), absorbed at 30% by WAS Ltd, compresses gross margin from 11.5% to 6.73% - insufficient to cover an A$3.45 million operating cost base, producing an operating loss of A$424,295 before financing costs.
- DSO deterioration from 45 to 80 days adds A$4.75 million to net working capital requirements, generating A$499,330 in additional overdraft interest at the RBA F5 rate of 10.51% (April 2026) - compounding an already critical margin position.
- Combined stress impact: net profit swings from A$1.72 million (base) to −A$924k (stress) - a A$2.65 million earnings deterioration. Gross margin compression drives 81% of the swing; working capital overdraft cost drives 19%.
- Three operational recovery levers (early payment discount, inventory drawdown, supplier term extension) recover approximately 46% of the stress loss - improving net profit from −A$924k to −A$503k - but the business remains loss-making because gross margin compression is structural and cannot be addressed operationally mid-season.
- Sensitivity analysis confirms the solvency boundary lies between 70% and 80% pass-through rate. At pass-through rates below 80%, WAS Ltd is loss-making at every DSO level - working capital management alone cannot restore profitability. Pricing recovery is the critical lever.

---

## The Entity

| Parameter | Detail |
|---|---|
| Entity | Wheatbelt Agronomy Supplies Ltd (fictional) |
| Status | Unlisted private company |
| Established | 1998 |
| Headquarters | Merredin, Western Australia |
| Regional Hubs | Geraldton, Northam, Katanning, Esperance |
| Annual Revenue | AUD $45,000,000 |
| FTE Staff | 24 |
| Core Products | Bulk urea, crop protection chemicals, seed, diesel |
| Advisory Services | Soil testing, variable rate mapping, agronomy |
| Key Customers | 450+ broadacre farming enterprises, WA grain belt |
| Key Suppliers | Incitec Pivot, Nufarm, Syngenta, Ampol, BP Wholesale |

---

## Model Summary

| Metric | Base Case | Stress Case | Recovery Case |
|---|---|---|---|
| Gross Margin | 11.5% | 6.73% | 6.73% |
| Net Profit | $1,723,400 | ($923,625) | ($502,870) |
| Net Margin | 3.83% | (2.05%) | (1.12%) |
| CCC | 80 days | 117 days | 82 days |
| Net Working Capital | $9.37m | $14.12m | $9.93m |
| Overdraft Interest | $0 | $499,330 | $45,287 |

---

## Data Sources

| Source | Data Used | Publisher | Date |
|---|---|---|---|
| World Bank Pink Sheet | Urea prices 2024–2026 | World Bank Group | May 2026 |
| RBA Table F5 | Small business overdraft rate 10.51% | Reserve Bank of Australia | April 2026 |
| Elders FY2025 Investor Presentation | Retail products gross margin 12.5% | Elders Limited (ASX: ELD) | FY2025 |
| Nutrien 2025 Annual Report | Retail segment margins, receivables allowance | Nutrien Ltd (NTR) | FY2025 |
| Atradius AU 2024 & 2025 | B2B payment terms, agri-food DSO deterioration | Atradius | 2024, 2025 |
| ABARES Farm Survey | Fertiliser as % of farm cash costs | ABARES | 2024–25 |
| AIP Terminal Gate Prices | Perth wholesale diesel 197.1 cpl | Australian Institute of Petroleum | May 2026 |
| ATO Superannuation Rates | SG rate 12% FY2025-26 | Australian Taxation Office | FY2025-26 |
| The Conversation / UWA | WA winter crop seeding April–June | Prof. Marit Kragt, UWA | April 2026 |
| DPIRD WA Crop Sowing Guide | WA crop calendar and variety timing | DPIRD | 2026 |
| Freight Lines Group | Perth–Esperance/Geraldton freight corridors | Freight Lines Group | 2026 |
| Indeed AU / ERI SalaryExpert | Agronomist salary WA $83,929–$107,488 | Indeed AU / ERI | 2026 |
| Indeed AU / Industry guide | Truck driver / warehouse salary WA $71–80k | Indeed AU | 2026 |
| ABS Average Weekly Earnings | Transport sector median $1,470/week | ABS | August 2025 |
| ScaleSuite / CreditorWatch | SME debtor days 45–65 days benchmark | ScaleSuite | 2026 |

Full source register with URLs, tier ratings and adjustment notes: 
[/data/data_sources_and_assumptions.md](data/data_sources_and_assumptions.md) 

---

## Repository Structure
```
## Repository Structure
wa-agribusiness-working-capital-analysis/
├── /data
│   └── data_sources_and_assumptions.md 
├── /model
│   └── WAS-WC-Analysis.xlsx
├── /memo
│    └── WAS_CFO_Memo.pdf
└── README.md
```

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Financial modelling |
| GitHub | Version control and portfolio presentation |
| Microsoft Word -> PDF | CFO-facing commercial memo |

---

## Methodology Note

All working capital metrics are derived from first-principles operational reasoning supported by publicly available sources. A real corporate engagement would replace these estimates with actual ledger data extracted from the company's accounting system. Sensitivity analysis has been constructed to reflect the range of outcomes consistent with reasonable parameter uncertainty. The fictional entity is calibrated against publicly disclosed financials of listed Australian agribusinesses including Elders Limited and Nutrien Ltd.

---

## Author

**Shin Tran**   | University of Western Australia (2026) | Perth, Western Australia
