# Superstore Sales & Profitability Dashboard (Power BI)

## Overview
Interactive Power BI dashboard analyzing Superstore sales, profit, returns, and loss-making orders. Built as part of the Advanced Data Analysis course at NTI.

## Business Questions
1. How has sales performance changed over the years?
2. How does monthly sales performance compare with the previous month?
3. Which product categories contribute most to sales and profit?
4. Which customer segment generates the highest profit?
5. What percentage of sales is associated with returned orders?
6. Which sub-categories have the highest number of negative-profit orders?

## Data Preparation (Power Query)
- Fixed data types
- Handled errors in the data

## Data Modeling
- Built relationships between the three tables
- Created a Date table for time-based analysis

## DAX Measures
- Total Sales, Total Profit, Profit Margin
- Negative Profit Orders, Sales 2018
- Previous Month Sales, Previous Year Sales

## Dashboard Features
- Title and KPI cards: Total Sales (1.10M), Profit Margin, Negative Profit Orders (905), Total Profit (132.52K), Sales 2018 (312.73K)
- Slicers: Region, Category
- Charts: sales vs. previous month and previous year, profit and sales by category, profit by segment, sales by return status, negative profit orders by sub-category, profit by discount
- Navigation button between pages

## Tools
Power BI, Power Query, DAX

## Dashboard Preview


![Dashboard Page 1](images/5.png)




![Dashboard Page 2](images/5.1.png)



## Presentation
[View the full presentation (PDF)](dashboard/superstore_presentation.pdf)

## Key Findings & Recommendations

**Q1. Sales over the years**
Sales increased steadily over the analyzed years, with the strongest growth between 2017 and 2018.
*Recommendation:* Investigate the factors behind the strong growth and replicate successful strategies in future years.

**Q2. Monthly sales vs. previous month**
Monthly sales fluctuate throughout the year, with several months showing significant increases or decreases.
*Recommendation:* Analyze seasonal patterns and the reasons behind big monthly changes to improve forecasting and planning.

**Q3. Categories by sales and profit**
Technology is the most profitable category, while Furniture generates significantly lower profit than Technology and Office Supplies.
*Recommendation:* Keep investing in Technology, and investigate pricing, costs, and discount strategies affecting Furniture.

**Q4. Most profitable customer segment**
The Consumer segment is the most profitable, contributing about 50.57% of total profit.
*Recommendation:* Maintain strong engagement with Consumers, and develop targeted strategies to raise profitability in Corporate and Home Office.

**Q5. Returned orders**
About 5.41% of sales are associated with returned orders, while 94.59% are not returned.
*Recommendation:* Investigate the main reasons for returns and find products or categories with unusually high return rates.

**Q6. Negative-profit orders by sub-category**
Binders have the highest number of negative-profit orders, followed by Chairs and Tables (905 loss-making orders in total).
*Recommendation:* Review pricing, costs, and discount levels for Binders, Chairs, and Tables to reduce loss-making orders.
