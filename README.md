<div align="center">

# 🐟 Malaysian Fisheries Trade Analysis (2013–2023)

**An interactive Power BI dashboard analyzing a decade of Malaysia's fisheries import and export trade.**

`Power BI` · `DAX` · `Power Query` · `Data Visualization` · `Text Analytics`


</div>

---

## Executive Summary
 
Malaysia trades fisheries products with over 160 countries but has consistently imported more than it exports . Using fisheries export and import data acquired from Department of Fisheries' website, this dashboard analyses trade data from 2013-2023 by trade balance, trade partners and commodity type. A simple text mining is also done on 42 recent news article and research papers to see common themes shaping the sector.

Note: Trade deficit refers to higher import than exports, where trade surplus refers to higher export than imports.

![Trade overview page](assets/trade-overview.jpg)
---

##  Key Findings

- Malaysia has a **fisheries trade deficit every year from 2013–2023** (–RM2.56bn in 2023), increasing sharply after 2020.
- Trade is concentrated in **Asia** where China and ASEAN countries form the majority of both imports and exports. Singapore is the one major partner where Malaysia has a trade surplus.
- Malaysia tends to **import raw product (fresh/frozen fish) and export higher-value processed product** (prepared seafood, crustaceans).
- Industry research puts emphasis on **aquaculture and sustainability** as the sector's growth potential with disease and climate are identified as significant risks.

---

## 🖥️ Dashboard Pages

| Page | Description |
|---|---|
| **Trade Overview** | KPI cards, 2013–2023 trade value trend, yearly trade balance |
| **Trading Partners** | Top partner comparison, regional trends, partner map |
| **Commodities** | Trade balance by commodity, value trend, volume share |
| **Significant Themes** | Word cloud from 42 news/research sources on the sector |

![Trading partners](assets/trading-partners.jpg)
![Commodities](assets/commodities.jpg)
![Word cloud](assets/word-cloud.jpg)


---

## 🗂️ Data & Methodology

**Source(s):** ` Department of Fisheries Malaysia (DOF)'

**Preparation:** `data extracting from different source formats, standardizing data using Python (country name, currency, units of measurements), handling missing values and anomalies.

**Text analysis:** Frequency analysis across 42 news/research sources, highlight the top 150 terms with ≥12 repetitions each, using PowerBI's Word Cloud tool.

---

## 🚀 View It

- **Interactively:** (https://app.powerbi.com/view?r=eyJrIjoiZjE2NjY2ZjQtZjE5NS00ZTFlLTlmODUtYTQ4NDQ1ZjE0OWZjIiwidCI6IjI4YzZkZjUyLWIzMTItNDQ0Mi1hZjU5LTIwNzI1OGJmNjRhYiIsImMiOjEwfQ%3D%3D)'
- **As a PDF:** [`assets/ver_report.pdf`](assets/ver_report.pdf)

---

## 🛠️ Built With

- **Power BI Desktop** — data modeling, DAX measures, visualization
- **Power Query** and **Python** — data cleaning and transformation
- **Microsoft Excel** 

---

<div align="center">

</div>


