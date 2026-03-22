# Russia-Ukraine-India-Trade-Analysis

🌍 Power BI dashboard analyzing India's bilateral trade with Russia & Ukraine across 6 fiscal years (2019-20 to 2024-25). Insights on $1,75,311 Mn+ imports from Russia, 216 trade records, war phase impact, commodity trends, and economic indicators. Interactive Power BI dashboard exploring geopolitical trade data — import/export flows, oil & wheat price shocks, INR/USD depreciation, sanctions severity, and India's profitability during the Russia-Ukraine conflict.

---

# Russia – Ukraine – India Trade Intelligence Dashboard

## 📊 Project Overview

This project presents a comprehensive analysis of **India's bilateral trade with Russia and Ukraine** using **Power BI**. The dashboard explores import/export volumes, commodity-wise trade flows, war phase impact, global price shocks, currency depreciation, and India's profitability across three distinct geopolitical phases — Pre-War, Active War, and Prolonged War.

---

## 🎯 Problem Statement

The Russia-Ukraine conflict (February 2022 onwards) fundamentally disrupted global trade. India, maintaining strategic neutrality, navigated a complex balancing act — capitalising on discounted Russian energy while absorbing agricultural supply shocks from Ukraine. This analysis aims to answer key questions about:

- How did India's import volumes from Russia and Ukraine shift across war phases?
- Which commodity categories (Energy, Agriculture, Industrial) were most impacted?
- How did global oil and wheat price shocks affect India's trade economics?
- What is the relationship between sanctions severity and INR/USD depreciation?
- Which products does India export to Russia and Ukraine, and how did profitability change?

---

## 📈 Dashboard Preview

[![Trade Overview - Page 1](ScreenShots/DashBoard_1.png)](ScreenShots/DashBoard_1.png)
*Page 1 — Trade Overview: Import trends, commodity share, trade balance, and war phase comparison*

[![Economic Impact - Page 2](ScreenShots/DashBoard_2.png)](ScreenShots/DashBoard_2.png)
*Page 2 — Economic Impact: Oil/wheat prices, INR/USD rate, sanctions score, profitability*

[![Products & Exports - Page 3](ScreenShots/DashBoard_3.png)](ScreenShots/DashBoard_3.png)
*Page 3 — Products & Exports: India's export basket, Russia's import products, profit by commodity*

[![Data Records - Page 4](ScreenShots/DashBoard_4.png)](ScreenShots/DashBoard_4.png)
*Page 4 — Data Records: Full filterable table with conditional formatting*

---

## 🔍 Key Business Questions Answered

1. **How much did India's imports from Russia surge during the Active War phase?**
2. **Which commodity category drove the maximum import growth — Energy, Agriculture, or Industrial?**
3. **Is there a clear correlation between sanctions severity and INR/USD depreciation?**
4. **What are the top products India exports to Russia and Ukraine?**
5. **How did global oil and wheat price shocks affect India's trade balance?**
6. **Did India's trade profitability improve or deteriorate during the war period?**
7. **Which fiscal year recorded the largest trade deficit?**

---

## 📊 Key Insights

### Overall Metrics

* **Total Trade Records**: 216
* **Total Import from Russia**: $1,75,311.8 Mn
* **Total Import from Ukraine**: $21,689.3 Mn
* **Total Export to Russia**: $70,713.8 Mn
* **Total Export to Ukraine**: $20,763.1 Mn
* **Total India Export Combined**: $92,400 Mn
* **Cumulative Trade Deficit**: ($1,05,524.2 Mn)
* **Average Profit % (India)**: 14.23%
* **Avg Monthly Trade Balance**: ($488.54 Mn)

---

### Top Import Products from Russia

1. **LNG** — 39,360 Mn (13.60%) — Energy dominant
2. **Natural Gas** — 32,800 Mn (11.33%) — Surged Active War
3. **Crude Oil** — 31,220 Mn (10.79%) — Massive post-2022 surge
4. **Potash** — 27,650 Mn (9.55%) — Agriculture input
5. **Fertilizers** — 26,610 Mn (9.20%) — Price spike period
6. **Petroleum Products** — 25,300 Mn (8.74%) — Rising
7. **Coal** — 21,820 Mn (7.54%) — Increasing
8. **Nitrogen Fertilizer** — 20,290 Mn (7.01%) — Stable
9. **Natural Gas (Piped)** — 19,570 Mn (6.76%) — Growing
10. **Steel** — 17,390 Mn (6.01%) — Industrial
11. **Aluminum** — 16,500 Mn (5.70%) — Industrial

---

### Top Export Products from India

1. **Chemicals** — Highest volume, Russia dominant destination
2. **Pharmaceuticals** — Strong across all phases
3. **IT Services** — Consistent growth to Russia
4. **Machinery Parts** — Rising in Active War phase
5. **Rice** — Pre-War Ukraine peak
6. **Engineering Goods** — Both countries
7. **Sugar** — Ukraine focused, declining post-war
8. **Textiles** — Stable Russia exports
9. **Tea** — Pre-War Russia focus

---

### War Phase Impact

* **Pre-War (2019-20 to 2021-22)**: Balanced trade — Russia imports ~$300–700 Mn/month, Ukraine ~$200–350 Mn/month
* **Active War (2022-23 to 2023-24)**: Russia energy imports surge 400%+, Ukraine imports collapse to $5–80 Mn/month
* **Prolonged War (2024-25)**: Peak Russian imports exceeding $4,000 Mn/month in Energy

---

### Key Findings

1. **Import Concentration Risk**: Energy imports (LNG + Gas + Oil + Coal) account for ~48% of Russia import value
2. **Ukraine Collapse**: Ukrainian imports fell from $200–350 Mn/month (Pre-War) to $5–50 Mn/month (Active War) — a 90%+ drop
3. **Profitability Paradox**: India's average profit % improved during war phases due to discounted Russian crude oil pricing
4. **Currency-Sanctions Link**: Strong correlation between rising Sanctions Score (0→9/10) and INR depreciation (₹70→₹85)
5. **Export Opportunity**: Pharmaceuticals and Chemicals filled the market gap left by Western supplier withdrawal from Russia

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop** — Dashboard creation and data visualization
* **DAX (Data Analysis Expressions)** — Custom measures and calculated columns
* **Power Query Editor** — Data transformation, column types, Month Number sort
* **Microsoft Excel (.xlsx)** — Dataset — 216 rows × 26 columns
* **Python (pandas + openpyxl)** — Dataset generation and Excel formatting
* **Data Modeling** — War phase-based filtering and relationships
* **Conditional Formatting** — Phase colours, Trade Balance, Profit % tiers, Sanctions heat scale

---

## 📁 Project Structure

```
Russia-Ukraine-India-Trade-Analysis/
│
├── 📂 dashboards/
│   └── Russia_Ukraine_India_Trade_Dashboard.pbix
│
├── 📂 data/
│   └── russia_ukraine_india_trade_enriched.xlsx
│
├── 📂 documentation/
│   └── Russia_Ukraine_India_Trade_Report.docx
│
├── 📂 screenshots/
│   ├── page1_trade_overview.png
│   ├── page2_economic_impact.png
│   ├── page3_products_exports.png
│   └── page4_data_records.png
│
└── README.md
```

---

## 💡 Key Features

* **4-Page Interactive Dashboard** — Trade Overview, Economic Impact, Products & Exports, Data Records
* **Global War Phase Filters** — Header buttons update all 4 pages simultaneously
* **Commodity Slicer** — Energy / Agriculture / Industrial drill-down
* **5 KPI Cards per Page** — Dynamic headline metrics that respond to filters
* **Conditional Formatting** — War Phase row colours, Trade Balance red/green, Profit % tiers, Sanctions gradient
* **Drill-Through Navigation** — Click any phase cell on Page 4 → jump to Page 1 filtered
* **Cross-Filtering** — Every visual filters every other visual on the page
* **Dual-Axis Combo Chart** — INR/USD Exchange Rate (bar) vs Sanctions Score (line) overlay
* **Totals Row** — Grand totals at the bottom of the Data Records table

---

## 📐 DAX Measures
  see the .pbix file
---


## 📌 Business Recommendations

Based on the analysis:

1. **For Trade Policy Makers**

   * Diversify energy imports — reduce concentration risk on Russian sources
   * Negotiate agricultural supply agreements with Brazil, Argentina & Australia to replace Ukraine
   * Establish rupee-ruble settlement mechanisms to hedge against SWIFT disruption

2. **For Indian Exporters**

   * Scale up pharmaceutical and chemical exports — market vacated by Western suppliers in Russia
   * Lock in long-term IT Services and Engineering Goods contracts during the prolonged war window
   * Target both countries for post-conflict trade normalisation planning

3. **For Investors & Risk Analysts**

   * Monitor INR/USD rate as a leading indicator of import cost inflation
   * Track Sanctions Score monthly — direct correlation with rupee depreciation
   * Energy commodity category shows highest trade profitability — margins improved during war

4. **For Risk Management**

   * Agricultural supply chain vulnerability is the highest residual risk from the Ukraine collapse
   * Secondary sanctions pressure from Western economies is the key downside risk to monitor
   * Strategic petroleum reserves need strengthening given 48% energy concentration in Russia imports

---

## 📚 Dataset Summary

| Attribute | Value |
|-----------|-------|
| File | `russia_ukraine_india_trade_enriched.xlsx` |
| Total Rows | 216 |
| Total Columns | 26 |
| Fiscal Years | 2019-20 to 2024-25 (6 years) |
| Months per Year | 12 (April – March) |
| Commodity Categories | Energy · Agriculture · Industrial |
| War Phases | Pre-War · Active War · Prolonged War |
| Bonus Sheet | KPI Summary — aggregated benchmarks by war phase |

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

* Power BI multi-page dashboard design and development
* DAX measure creation — SUM, AVERAGE, CALCULATE, DIVIDE, SWITCH
* Calculated columns — sort columns, category labels, performance tiers
* Data modeling and phase-based cross-filtering
* Conditional formatting — background rules, font colour rules, gradient scales
* Interactive visualization techniques — cross-filtering, drill-through, tooltips
* Business intelligence applied to geopolitical trade data
* Data storytelling — translating raw trade records into actionable policy insights

---

## 📧 Contact

For any questions or feedback regarding this project, please feel free to reach out!

- GitHub: [@lileshwar-mahajan](https://github.com/lileshwar-mahajan)
- LinkedIn: [www.linkedin.com/in/lileshwar-mahajan-b81137255](www.linkedin.com/in/lileshwar-mahajan-b81137255)
- Email: mahajanlileshwar@gmail.com

---

## ⭐ Acknowledgments

* Trade data references from public bilateral trade databases and economic research
* Power BI community for visualization best practices and DAX inspiration
* Geopolitical context from open economic analysis and conflict impact research

---

**If you find this project helpful, please consider giving it a ⭐ and sharing it with others!**

---

## 🔗 Related Projects

Check out my other data analysis projects:

* [Spotify Data Analysis](https://github.com/lileshwar-mahajan/Spotify-Data-Analysis)
* [FNP Sales Analysis](https://github.com/lileshwar-mahajan/FNP-Sales-Analysis)
* [Instagram-Analytics-Dashboard](https://github.com/lileshwar-mahajan/Instagram-Analytics-Dashboard)
* 

---

*Built with Power BI Desktop · Dataset: 216 records · 26 columns · 6 fiscal years · 3 commodity categories · 3 war phases · FY 2019-20 to 2024-25*
