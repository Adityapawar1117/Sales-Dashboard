# Sale's Data Analysis — Retail Sales Performance Dashboard

> An interactive Power BI dashboard built to analyze retail sales performance across categories, regions, segments, and shipping modes — tracking profit and sales trends from 2018 to 2021.


## Purpose

Retail businesses generate large volumes of transactional data across multiple product categories, customer segments, and geographies. This dashboard provides a consolidated view of sales performance — enabling analysts and sales managers to make data-driven decisions on inventory, shipping strategy, and regional marketing.


## Tech Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Main visualization platform |
| Power Query | Data cleaning & transformation |
| DAX | Calculated measures & KPIs |
| Data Modeling | Table relationships & aggregations |
| .pbix / .png | Development & preview formats |


## Data Source

**Kaggle — Superstore Sales Dataset**  
9,994 orders with fields covering order ID, product category, sub-category, ship mode, customer segment, region, sales, and profit — spanning 2018 to 2021.


## Key KPIs

| Metric | Value |
|--------|-------|
| Total Orders | 9,994 |
| Sum of Profit | 45,984.25K |
| Sum of Sales | 2,297.20K |
| Office Supplies Orders | 6.03K |
| Consumer Segment Share | 50.55% |
| West Region Share | 31.58% |


## Key Visuals

- **Orders by Category** — Column chart: Office Supplies (6.03K) > Furniture (2.12K) > Technology (1.85K)
- **Orders by Ship Mode** — Bar chart: Standard Class leads at 5.97K; Same Day lowest at 0.54K
- **Profit by Year** — Area chart: Peaks at 46M in 2020, then drops sharply in 2021
- **Sales by Segment** — Pie chart: Consumer (50.55%), Corporate (30.74%), Home Office (18.7%)
- **Sales by Region** — Donut chart: West (31.58%), East (29.55%), Central (21.82%), South (17.04%)
- **Orders by Sub-Category** — Horizontal bar: Binders (1,523), Paper (1,370), Furnishings (957)


## Business Impact & Insights

- **Inventory focus:** Office Supplies and Binders drive highest order volumes — prioritize stock consistency
- **Profit trend alert:** Sharp drop after 2020 warrants root cause analysis — pricing, costs, or demand shifts
- **Regional strategy:** West + East account for 61% of sales — prime targets for upselling campaigns
- **Shipping optimization:** Standard Class handles ~60% of orders — cost vs speed trade-off analysis can cut costs


## Dashboard Preview

Example:
![Sales Dashboard](https://github.com/Adityapawar1117/Sales-Dashboard/blob/main/Sales%20Dashboard%20Snapshot.png)
