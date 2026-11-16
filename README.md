# Superstore Strategic Insights | Excel + Power BI

Sales and profit analysis of the Global Superstore dataset (2011–2014) using Excel for cleaning and pivots, and Power BI for dashboards.

## Project Summary
* **Goal:** Find where the business earns, where it loses money, and what to do next.
* **Data:** ~51K orders, 1,590 customers, 143 countries
* **Tools:** Excel (cleaning, formulas, pivot tables) and Power BI (dashboards)

## Key Numbers
| Total Sales | Total Profit | Profit Margin | Avg. Discount |
| :--- | :--- | :--- | :--- |
| 12.64M | 1.47M | 11.6% | 14% |

---

## 1. Data Cleaning (Excel)
* Kept a raw copy of the data
* Renamed columns to lowercase (`order_date`, `sales`, `profit`)
* Removed duplicates
* Fixed blank values
* Cleaned text with `TRIM` and `PROPER`
* Set correct data types (dates and numbers)
* Added `Month` and `Year` from `order_date`

## 2. Excel Analysis
* Total sales, total profit, average discount
* Top 5 products by sales
* Top 5 loss-making products
* **Pivot charts:** Sales by Region, Profit by Category, Sales by Segment, Monthly Sales Trend

*(Insert your Excel Analysis Pivot Charts screenshot here)*

## 3. Power BI Dashboards
* **Executive Overview** – KPIs, sales vs profit by year, shipping mode, country map
* **Sales Performances** – Trends, category, segment, market and region
* **Customer & Segments** – Top customers, top products, profit by sub-category

*(Insert your Power BI Dashboard screenshots here)*

## 4. Key Findings
* **Top Markets:** APAC is the top market (3.59M), followed by EU (2.94M) and US (2.30M).
* **Regional Performance:** Central is the top region (2.82M, ~22% of sales), while Canada and the Caribbean have the lowest sales.
* **Category Profitability:** Technology generates 45% of profit; Furniture brings in 32.5% of sales but only 19.5% of profit.
* **Customer Segments:** Consumer leads at 52% of sales, followed by Corporate (30%) and Home Office (18%).
* **Loss-Making Items:** Tables lose money overall, specifically driven by *Bevis Round Table*, *Cubify CubeX 3D printers*, and *Lexmark MX611dhe*.
* **Seasonality:** Sales grow year-over-year and consistently peak from September to December.

## 5. Recommendations
* **Cap Discounts:** Limit discounts to ~5% on Tables, 3D printers, and laser printers to protect margins.
* **Inventory Planning:** Prepare stock and delivery capacity ahead of the September–December peak.
* **Marketing Focus:** Prioritise marketing spend on high-margin Technology products.
* **Regional Growth:** Build targeted local strategies for underperforming markets like Canada and the Caribbean.
