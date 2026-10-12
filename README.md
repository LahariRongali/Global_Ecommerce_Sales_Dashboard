# Global_Ecommerce_Sales_Dashboard  & Profit Dashboard



Interactive Power BI dashboard analyzing 51,000+ order records (2011-2014) across 147 countries to track sales, profit, quantity, and shipping cost.

## Objective
Understand where a global e-commerce business makes and loses money, by market, category, sub-category, country, and city.

## Dataset
- **File:** `data/ECOMM_DATA.xlsx`
- **Sheets:** Orders (51,289 rows, 24 columns), Returns (1,173 rows), People (13 rows)
- **Period:** January 2011 - December 2014
- **Coverage:** 147 countries, 1,590 customers, 25,035 orders
- **Key fields:** Order Date, Market, Country, City, Category, Sub-Category, Sales, Quantity, Discount, Profit, Shipping Cost
- Based on the Global Superstore sample dataset.

## Tools Used
Power BI, Microsoft Excel, DAX

## Dashboard Features
- KPI cards: Sales (12.64M), Profit (1.47M), Quantity (178K), Shipping Cost (1.35M)
- Donut chart: profit by market
- Decomposition tree: profit by category and sub-category
- Pie chart: sales by category
- Funnel chart: sales by country
- Bar chart: sales by city
- Date table marked for time-based analysis

## Key Insights
- **APAC** (Asia-Pacific) is the top profit market at about 436K (29.7%), followed by **EU** at about 373K (25.4%).
- **Canada** and **EMEA** contribute the least profit.
- **Technology** is the most profitable category (about 663K), with Copiers as the top sub-category.
- Furniture sales (4.11M) are close to Technology (4.74M), but Furniture profit (285K) is much lower than Technology (663K).
- About 24% of order lines have a negative profit.
