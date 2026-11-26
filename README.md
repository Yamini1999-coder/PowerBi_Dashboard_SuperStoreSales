# Super Store Sales Dashboard (Power BI)

An interactive Power BI sales analytics dashboard built to track revenue, profitability, customer segments, product categories, and regional performance across **Central, East, South, and West** regions.

## Key KPIs & DAX Measures
- **Total Sales:** `SUM('Sheet1'[Sales])`
- **Total Profit:** `SUM('Sheet1'[Profit])`
- **Profit Margin %:** `DIVIDE([Total Profit], [Total Sales], 0)`
- **Total Quantity:** `SUM('Sheet1'[Quantity])`

## Dashboard Highlights
- **Interactive Region Filtering:** Slice across Central, East, South, and West regions to compare regional sales trends and state-level contribution.
- **Category & Sub-Category Analysis:** Evaluate performance across Furniture, Office Supplies, and Technology, along with top sub-categories and products.
- **Customer Segment Breakdown:** Track sales distribution across Consumer, Corporate, and Home Office segments.
- **Time-Series Trend:** Monitor sales movement across 2019 and 2020.

## Screenshots
- **Overall / Regional Views:** 

## Tools Used
- Microsoft Power BI Desktop, DAX, Data Visualization
