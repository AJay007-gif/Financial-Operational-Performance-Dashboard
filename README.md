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

### Executive Summary

Provides a high-level overview of organizational performance.

### Sales Performance Analysis

Compares actual financial performance against planned budget.

### Profitability and Margin Analysis

Evaluates profit contribution across products and regions.

### Operational Performance Analysis

Identifies revenue and profit trends over time.

## Dashboard Preview

(Add screenshots here after uploading them.)

## Key Insights

* Revenue performance varied across regions.
* Profitability was influenced by discount levels.
* Several categories exceeded budget expectations.

## Recommendations

* Review high-discount segments impacting margins.
* Focus investment on top-performing regions.
* Monitor budget variance regularly to improve forecasting accuracy.

## Skills Demonstrated

* Financial Analysis
* KPI Development
* Data Visualization
* Dashboard Design
* Power Query Data Transformation
* DAX Measure Development
* Business Intelligence Reporting
