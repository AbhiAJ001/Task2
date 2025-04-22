# Task2

# Sales Data Analysis

## 1. Data Collection
Source: Internal sales transactions from 2022 and 2023.
Format: Excel file with columns for customer segment, country, product, pricing, sales, discounts, COGS, profit, and date details.

## 2. Data Cleaning & Preparation
Steps performed:
Checked for missing values and inconsistencies.
Parsed Date field to extract:
Year, Month Name, and Day Name
Converted numeric fields to appropriate types for aggregation:
Sales, COGS, Profit, etc.

## 3. Data Enrichment
Added calculated fields:
Gross Sales = Units Sold × Sale Price
Profit = Sales - COGS
Sales Ratio categorized into Low / Average / High bands.

## 4. Visual Analytics (in Power BI / Charting Tools)
Built the following visuals:

### Monthly Sales Trend
Shows seasonality and peak periods (Q4 highs).
Highest sales in October, followed by December and September.
Indicates a strong Q4 performance, possibly due to seasonal trends or promotions.


### Sales by Segment
Pie chart reveals dominance of Small Business segment.
Small Business: 45.02%
Enterprise: 32.71%
Government: 18.71%
Midmarket: 1.85%

### Sales vs COGS by Country
Bar chart for geographic profitability analysis.
Top contributors by country:
Germany
Canada
France
USA
Mexico
Indicates geographically diverse revenue sources.

### Top Product Sales
Bar chart ranks products like Paseo, VTT, Montana, etc.

### Discount Band Distribution
Donut chart showing how sales vary by discount level.
Low Discount band drives the majority (58.42%) of the sales.
High Discounts account for only 8.07%—suggesting profitability is not heavily dependent on aggressive discounts.


### Sales by Day of Week
Heatmap or bar chart highlights Saturday/Friday as peak sales days.
Saturday and Friday show highest sales.
Suggests weekend demand spike—maybe B2C driven.

## 5. Summary Key Highlights
Calculated and highlighted:
Total Sales: $49.11M
Total Profit: $8.63M
Total Orders (COGS entries): 292

