
[Financial Sample.xlsx](https://github.com/user-attachments/files/28615870/Financial.Sample.xlsx)
<img width="1920" height="1030" alt="dashboard_preview" src="https://github.com/user-attachments/assets/8901ddbd-5447-4485-972d-2068aa7bdcb8" />

# 📊 Power BI Sales Performance Dashboard

## Project Overview
An end-to-end Power BI dashboard analyzing sales and profit
performance across products, segments, and countries using
Microsoft's Financial Sample dataset (2013–2014).

## Dataset
- **Source:** Microsoft Financial Sample (Excel)
- **Rows:** 700 transactions
- **Columns:** 16 fields including Segment, Country, Product, Sales, COGS, and Profit

## Dashboard Pages
**Page 1 — Executive Overview**
- 4 KPI Cards: Total Profit, Total Sales, Profit Margin %, Units Sold
- Line Chart: Monthly profit trend by year (seasonality view)
- Map: Geographic profit distribution across 5 countries
- Clustered Bar: Profit by country and customer segment
- Clustered Column: Profit margin % by product
- Treemap: Profit distribution by product

**Page 2 — Segment & Product Deep Dive**
- Stacked Bar: Segment profit contribution per product
- Bar Chart: Average profit margin % by segment
- Matrix Table: Profit summary — Product × Segment heatmap

## Key Insights
- Government segment is the top profit contributor across all countries
- October and November show consistent profit spikes (seasonality)
- Channel Partners segment shows the lowest and sometimes negative margins
- Paseo drives the highest total profit volume across all segments

## Tools Used
- Power BI Desktop (Visuals, DAX, Power Query)
- Microsoft Excel (Source dataset)
- DAX Measures: Total Profit, Total Sales, Profit Margin %, Total Units Sold
- Power Query: Data cleaning, type formatting, null replacement

## How to Use This Project
1. Download `Financial_Sample.xlsx` and `Sales_Performance_Dashboard.pbix`
2. Open the `.pbix` file in Power BI Desktop
3. If prompted to refresh data, point it to the downloaded `.xlsx` file
4. Use the Year, Segment, and Product slicers to explore the data interactively

## Author
**Tochukwu Stephen**
Early Career Researcher | Data Analyst | Power BI • SQL • Excel
📍 Lagos, Nigeria
