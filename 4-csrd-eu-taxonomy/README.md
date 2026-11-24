# Project 04 — CSRD & EU Taxonomy Compliance Dashboard

![Dashboard Preview](dashboard_preview.png)

## Overview
Interactive Power BI dashboard analysing European countries' compliance readiness with the **Corporate Sustainability Reporting Directive (CSRD)** and the **EU Taxonomy Regulation** — the two cornerstones of the EU's sustainable finance framework mandatory for large companies from 2024 onwards.

This project targets sustainability analysts, ESG consultants and financial institutions operating in **Ireland, Denmark, Luxembourg, Switzerland and Germany** who need data-driven insights to assess CSRD compliance gaps and green finance opportunities.

## Business Questions Answered
- Which European countries are on track to meet the EU 2030 renewable energy target of 42.5%?
- How have GHG emissions evolved since 2016 across focus markets?
- Where is green bond issuance concentrated and what growth trends exist?
- How does each country score on a composite CSRD Readiness Index?

## Data Sources
| Dataset | Source | Coverage |
|---|---|---|
| GHG Emissions by country and sector | Eurostat ENV_AIR_GGE | 2015–2023 |
| Renewable Energy share | Eurostat NRG_IND_REN | 2016–2024 |
| Green Bond Issuances | BIS / Kapsarc | 2022–2024 |
| Sovereign ESG Indicators | World Bank ESG Data | 2010–2023 |

## Key Findings
- **Denmark leads** renewable energy share among focus markets at ~41% of gross final energy consumption (2022), still below the EU 2030 target of 42.5%
- **France and Germany dominate** green bond issuances, concentrating over 50% of EU green debt securities — highlighting a financing gap for smaller economies
- **Ireland** shows strong growth in green bond issuances (2022–2024) despite relatively moderate renewable energy share, reflecting its role as a European financial hub
- **Luxembourg** scores highest on green finance metrics relative to its GDP, consistent with its position as Europe's leading sustainable investment fund centre
- The **CSRD Readiness Score** composite index reveals that no single country excels across all three pillars simultaneously — renewable energy, GHG reduction and green finance — indicating systemic gaps in the EU's sustainability transition

## Dashboard Pages
| Page | Content |
|---|---|
| CSRD Overview | KPI cards, GHG trend by country, renewable energy share ranking |
| Green Finance | Green bond issuances by country, growth 2022–2024, detail table |
| Country Benchmarking | Side-by-side comparison of focus markets across all ESG KPIs |

## Technical Stack
- **Power BI Desktop** — data modelling, DAX measures, dashboard design
- **Power Query** — data cleaning and transformation (UI only)
- **Star schema** — Calendar dimension table connected to 4 fact tables
- **DAX measures** — CSRD Readiness Score, YoY GHG Change, GHG Reduction vs 2016 baseline

## Files
| File | Description |
|---|---|
| `CSRD_EU_Taxonomy_Dashboard.pbix` | Power BI source file |
| `CSRD_EU_Taxonomy_Dashboard.pdf` | Exported dashboard (all pages) |
| `dashboard_preview.png` | Dashboard screenshot |

## Relevance for Target Markets
This dashboard directly addresses reporting requirements under **CSRD Article 29** and the **EU Taxonomy Climate Delegated Act**, which apply to companies operating in Ireland, Denmark, Luxembourg and other EU member states. Swiss companies with significant EU operations face equivalent reporting pressure under the upcoming **Swiss Climate Scores** framework.
