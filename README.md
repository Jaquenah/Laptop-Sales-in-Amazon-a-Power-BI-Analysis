# Laptop Sales Analysis Dashboard — Amazon

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## Overview

An interactive Power BI sales dashboard built to analyze Amazon laptop
sales performance across products, categories, payment modes, and time
periods. Features a collapsible filter panel for a clean user experience
and a data storytelling summary page.

## Dashboard Features

- **Collapsible filter panel** — toggle sidebar with bookmarks for a
  clean, distraction-free view
- **KPI cards** — Total Sales (123.89K), Total Quantity (110),
  Total Profit (11K)
- **Sales & Profit by Month** — clustered bar chart showing monthly trends
- **Daily Sales trend** — line chart for day-level granularity
- **Sales by Payment Mode** — donut chart (Cash vs Online)
- **Sales by Product** — horizontal bar chart, top 8 products
- **Sales by Type** — donut chart breakdown
- **Sales by Category** — treemap showing Category02 as top (36.40K)
- **Data storytelling page** — narrative summary with key insights

## Key Insights

| Metric | Value |
|--------|-------|
| Total Sales | 123.89K |
| Total Quantity | 110 units |
| Total Profit | 11K |
| Best Month | November (15K) |
| Worst Month | August (7K) |
| Top Product | Plastic Mat (9.8K) |
| Top Category | Category02 (36.40K) |
| Profit Margin | ~8.9% |

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard creation & visualization |
| Microsoft Excel | Data source preparation |
| DAX | Calculated measures & KPIs |
| Power Query | Data transformation |

## How to Open

1. Download and install
   [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repo or download the `.pbix` file
3. Open `LAPTOP_SALES_ANALYSIS_ON_AMAZON.pbix` in Power BI Desktop
4. Use the **☰ button** on the dashboard to toggle the filter panel
5. Use Year and Month slicers to filter the view

## File Structure

```
laptop-sales-amazon-powerbi/
│
├── LAPTOP_SALES_ANALYSIS_ON_AMAZON.pbix   # Main Power BI file
├── dashboard_screenshot.png               # Dashboard preview image
├── README.md                              # This file
├── data/
│   └── laptop_sales_data.xlsx             # Source data
└── assets/
    └── panel_open.png                     # Additional screenshots
```

## Dashboard Pages

**Page 1 — Main Dashboard**
Interactive overview with all KPIs, charts, and the collapsible filter
panel. Supports filtering by Year, Month, and Payment Mode.

**Page 2 — Data Story**
A narrative summary page highlighting key findings, seasonal trends,
and actionable recommendations for the business.

## What I Learned

- Building interactive dashboards with Power BI bookmarks
- Using the Selection pane to control visual visibility
- Creating collapsible navigation panels without any coding
- Designing DAX measures for KPI calculations
- Data storytelling techniques in Power BI

## Connect With Me

- LinkedIn: [www.linkedin.com/in/jaqueline-tandu]
- GitHub: [Jaquenah]

## License

This project is licensed under the MIT License.
Data used is for educational and portfolio purposes only.
    
