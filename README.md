# Financial & Operational Performance Dashboard

## Project Overview

This project delivers an end-to-end Business Intelligence solution built on a financial dataset. The report transforms transactional sales data into an interactive, multi-page Power BI dashboard that enables stakeholders to monitor performance across sales, profitability, and operations; all filterable by Year, Country, Segment, and Product.

## Business Problem

Organizations operating multi-segment, multi-country sales operations often lack real-time visibility into the metrics that drive strategic decisions. Without a unified analytics solution, leadership teams struggle to answer critical questions such as:

* Revenue & Profitability:  Which markets and customer segments generate the most revenue and the highest profit margins?
* Discount Impact:  Are current discounting strategies helping or hurting overall profitability?
* Product Performance: Which products deliver the strongest margins, and which are underperforming?
* Sales Trends: How are sales and unit volumes trending month-over-month, and what seasonal patterns exist?
* Resource Allocation: Where should leadership prioritize pricing strategy, sales effort, and resource investment?

Finance and operations teams are often left relying on disconnected spreadsheets, delayed reporting cycles, and manual calculations thus, slowing decision-making and obscuring strategic opportunities that could drive growth.
This project addresses that gap by building an interactive Power BI dashboard that consolidates financial and operational data into a single, real-time analytical view, enabling data-driven decisions across sales, profitability, and operations.

## Dataset Overview

Source File: Financial_Sample.xlsx
Record Volume: ~700 rows of transactional sales data
Time Period: September 2013 — December 2014 (16 months)

The dataset contains financial information including:

## Dataset Description

| Field | Description |
|---------|---------|
| Segment | Customer segment (Government, Small Business, Enterprise, Midmarket, Channel Partners) |
| Country | USA, Canada, France, Germany, Mexico |
| Product | Paseo, VTT, Velo, Amarilla, Montana, Carretera |
| Units Sold | Quantity of units sold per transaction |
| Manufacturing Price | Cost to manufacture each unit |
| Sale Price | Revenue generated per unit sold |
| Gross Sales | Total revenue before discounts |
| Discounts | Discount amount applied to sales |
| Sales | Net sales after discounts |
| COGS | Cost of Goods Sold |
| Profit | Net profit per transaction |
| Date / Month / Year | Time dimensions used for trend analysis |

Data Quality: Clean, structured dataset suitable for financial modelling and BI development without significant transformation requirements.

## Tools Used

* Power BI
* Power Query
* DAX
* Excel

## Key KPIs

* Total Revenue
* Total Expenses
* Total Profit
* Profit Margin %

## Dashboard Summary

The report is organized into four pages, each addressing a distinct analytical domain:

### Page 1 — Executive Summary (Overview)
This provides a high-level overview of organizational performance presenting the most critical KPIs at a glance:
* Total Sales: $118.73M
* Total Profit: $16.89M
* Profit Margin: 14.23%
* Total Units Sold: 1M

Visuals include a Sales Performance Trend line chart (monthly), Revenue by Business Segment bar chart, Regional Profitability Analysis (horizontal bar), and a Total Profit by Country map — giving executives a complete strategic snapshot in one view.

### Page 2 — Sales Performance Analysis
Drills into revenue distribution with four focused visuals:
* Revenue by Country (horizontal bar) — ranked from highest (USA: $25.03M) to lowest (Mexico: $20.95M)
* Revenue by Segment (treemap) — Government and Small Business dominate revenue share
* Total Sales by Product (vertical bar) — Paseo is the clear top-selling product
* Monthly Sales Trend (line chart) — reveals seasonality and peak sales periods

### Page 3 — Profitability & Margin Analysis
Examines the relationship between sales, discounts, and profit:
* Total Profit by Product (bar chart) — Paseo leads profit generation
* Profit Margin % by Product (column chart) — all products maintain margins in the 10–20% range; Amarilla and VTT lead
* Sales vs. Profit Analysis (scatter chart) — positive correlation between sales volume and profit, with VTT as a standout
* Discount Impact on Profitability (scatter chart) — illustrates how discount levels relate to profit outcomes by product

### Page 4 — Operational Performance Analysis
Evaluates product-level operational efficiency:
* Sum of Units Sold by Product (bar chart) — Paseo leads unit volume significantly
* Sum of Manufacturing Price and Sum of Profit by Product (scatter) — identifies cost-efficiency outliers
* Sum of Sales and Sum of Profit by Product (scatter) — maps revenue-to-profit efficiency across the portfolio
* Units Sold Trend Over Time (line chart) — monthly unit volume fluctuations throughout 2013–2014

## Dashboard Preview

(Add screenshots here after uploading them.)

## Key Insights

### Revenue & Market Performance
* The USA leads revenue at $25.03M, closely followed by Canada ($24.89M) and France ($24.35M). All five markets are within a $4M revenue band, suggesting relatively balanced geographic distribution — but the USA holds a slight competitive edge.
* Government is the largest revenue segment, generating $52.5M — more than Small Business ($42.4M) and nearly 3x Enterprise ($19.6M). Channel Partners ($1.8M) and Midmarket ($2.4M) represent minimal contribution and may warrant strategic review.
* Paseo is the dominant product — it generates the highest total sales (~$28M+) and the highest total units sold (~0.35M), making it the cornerstone of the product portfolio.

### Profitability
* Total profit margin of 14.23% is a healthy baseline for a multi-country, multi-segment operation. However, at $16.89M profit on $118.73M revenue, there is meaningful room for margin expansion through pricing and discount optimization.
* Amarilla has the highest profit margin % among all products, while Carretera and Montana show lower margins despite decent sales volumes — suggesting possible pricing or cost structure inefficiencies in those lines.
* VTT punches above its weight: it generates high profit relative to its sales volume, indicating strong unit economics and pricing power.

### Discount & Cost Analysis
* Discount levels vary significantly by product. The Discount Impact scatter reveals that some products receive heavy discounts (up to $2.5M–$3M in aggregate discounts) without proportionally higher profits — indicating potential over-discounting practices that erode margin.
* Manufacturing cost vs. profit analysis shows Paseo and VTT achieve the most favorable profit-to-manufacturing-cost ratios, while other products show tighter spreads.

### Trends & Seasonality
* Sales trend shows significant seasonality — clear peaks are visible in mid-2014 and November 2014, with troughs in early 2014. This pattern has direct implications for inventory planning, staffing, and cash flow forecasting.
* Units Sold trend mirrors the revenue trend, confirming volume (not just price) is a primary driver of the revenue peaks — particularly relevant for supply chain and demand planning teams.

## Recommendations

* Double Down on Government Segment At $52.5M in revenue, Government is the highest-value segment. Sales and account management resources should prioritize Government contract renewals and expansions. Develop tailored product bundles and competitive pricing frameworks for Government procurement cycles.
* Investigate Midmarket and Channel Partners Underperformance Combined, these two segments generate only $4.2M (3.5% of total revenue). Leadership should evaluate whether to invest in growing these segments or strategically deprioritize them in favour of higher-return channels.
* Optimize Discount Strategy The Discount Impact analysis reveals products receiving heavy discounts that do not generate proportionally higher profits. Implement tiered discount governance — especially for Paseo and Carretera — with approval thresholds tied to deal profitability, not just deal size.
* Protect and Expand Paseo Paseo is the highest-revenue and highest-volume product. Ensure supply chain capacity supports this demand, review its pricing strategy for potential upward adjustment in premium markets (USA, Canada), and explore adjacent product line extensions.
* Investigate Carretera and Montana Margin Gaps These two products show the lowest profit margins. Conduct a cost review to determine whether manufacturing inefficiencies, discount practices, or pricing misalignment is the root cause. Set a margin floor and build a corrective action plan.
* Leverage Seasonality for Planning The November 2014 sales peak should inform Q4 inventory build-up, promotional calendar planning, and sales team capacity. Consider launching targeted campaigns in slow months (Q1) to smooth revenue distribution and reduce over-dependence on year-end peaks.
* Prioritize VTT for Margin Expansion VTT demonstrates strong profit-to-sales efficiency. Evaluate whether VTT can capture additional market share through targeted marketing investment, particularly in France and Germany where revenue levels are strong.

## Skills Demonstrated

* Financial Analysis
* KPI Development
* Data Visualization
* Dashboard Design
* Power Query Data Transformation
* DAX Measure Development
* Business Intelligence Reporting
