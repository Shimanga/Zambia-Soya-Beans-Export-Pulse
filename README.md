# Zambia Soya Bean Export Analysis (2021-2022)

## A Data-Driven Investigation into Export Viability vs. Local Market Returns

**Research question:** *Does exporting soya beans generate systematically better returns for Zambian farmers and agribusinesses than selling locally, once price premiums, volume trade-offs, and logistical constraints are considered?*

This project is a structured, empirical inquiry into Zambia’s soya bean export performance. It combines export trade statistics, provincial production data, local Food Reserve Agency (FRA) prices, and regional competitor benchmarks to evaluate whether the observed export price premium translates into a reliable profitability advantage. The analysis is designed to inform both academic research on agricultural market integration and policy evaluation for landlocked commodity-exporting countries.

**Key analytical output:** A reproducible framework for comparing local vs. export returns under different volume and logistics cost scenarios.

---

## Analytical Methodology

| Tool | Application |
|------|-------------|
| **Python (Pandas, Matplotlib, Seaborn)** | Data cleaning, statistical comparison of price distributions, volatility analysis |
| **Tableau** | Interactive dashboards for export destination trends and year-on-year price shifts |
| **Excel** | Scenario modeling: how changes in exchange rates or freight costs alter the export vs. local decision |

---

## Core Evidence & Findings

### 1. Export price premium (conditional)
Average export prices exceeded local FRA prices by 15-25% across 2021-2022. However, this premium is not automatic. It depends on destination market selection and achieved scale.

### 2. Volume‑price trade‑off by destination
- **India**: higher unit price, lower volume  
- **Tanzania / Zimbabwe**: lower unit price, higher volume  
- **Implication**: No single "best" market exists; optimal choice depends on a supplier’s ability to aggregate or split shipments.

### 3. Concentration risk
60% of exports went to South Africa and Tanzania. Total export value fell from ~USD 21.5M (2021) to ~USD 12.3M (2022), revealing vulnerability to regional demand shocks.

### 4. Production–logistics link
Central and Eastern provinces dominate output. Export feasibility is therefore as much about aggregation and transport cost control as about farm-gate price.

### 5. Competitive positioning
Zambia exports at higher prices than Mozambique but competitively with Tanzania and South Africa, occupying a middle ground that requires careful logistics strategy.

📊 **Interactive dashboard:** [Tableau Public - Export Unit Prices & Quantities by Destination](https://public.tableau.com/app/profile/shimanga.mubitana/viz/Book1_17648309333440/Dashboard1)

---

## Visual Summaries

| Figure | Description |
|--------|-------------|
| ![Production Data](Images/production_data.png) | **Figure 1:** Provincial production concentration (Central & Eastern provinces dominant) |
| ![Export Trend analysis](Images/Export_data.png) | **Figure 2:** Export unit prices (USD/kg) by destination, 2021-2022 (blank = no exports) |
| ![Local price analysis](Images/Local_price_analysis_per_kg.png) | **Figure 3:** Local FRA prices (ZMW/kg) – baseline for comparison |
| ![Competitor price analysis](Images/Competitor_analysis.png) | **Figure 4:** Zambia vs. regional export competitors |

---

## Key Insights for Future Research & Policy

**For academic inquiry:**
- The volume‑price trade‑off across destinations offers a natural experiment for studying optimal market selection under transaction costs.
- Provincial production concentration provides a basis for spatial equilibrium modeling of agricultural exports from landlocked regions.

**For policy evaluation:**
- Price premiums exist but are eroded by logistics costs unless farmers coordinate. This suggests that export promotion policies should prioritize aggregation infrastructure before trade agreements.
- Scenario modeling shows that small changes in exchange rates or freight costs can flip the export‑vs‑local decision ie future work should integrate real‑time cost data.

**For practitioners:**
- Export potential is real but conditional on scale and destination matching.
- Market concentration is a risk-diversification is not just a slogan but a quantified necessity.

---

## Next Steps (Extended Research Agenda)

- [ ] Build a cost‑insight margin model (from farm‑gate to port) to quantify break-even logistics costs.
- [ ] Apply time‑series forecasting to regional soybean prices to identify optimal export windows.
- [ ] Cross‑country comparison: Zambia vs. other landlocked agricultural exporters (Malawi, Burkina Faso) to isolate logistics vs. price effects.
- [ ] Maintain updated trade and production data for continuous scenario analysis.

---


## Data Sources

| Data type | Source |
|-----------|--------|
| Export flows | FAO |
| Regional competitor prices | World Bank |
| Provincial production | Zamstats (Zambia Statistics Agency) |
| Local FRA prices | PMRC Zambia & Parliament of Zambia |

**Key figures (2021–2022):**
- 2021 exports: ~USD 21.5 million
- 2022 exports: ~USD 12.3 million

---

## Conclusion

Exporting soya beans from Zambia can be economically attractive, offering a price premium over local FRA prices. However, success is not automatic. It depends on achieving scale, controlling logistics costs, and targeting the right destination markets. This repository provides the data, code, and scenario framework to support those evidence-based decisions.

---

*Analysis by Shimanga Mubitana*  
**Detailed Article:** [Zambia’s Soya Beans Export Pulse (2021–2022 Data)](https://agricultureinzambia.com/zambias-soya-beans-export-pulse-2021-2022-data/)
