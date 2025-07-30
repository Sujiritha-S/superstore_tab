# Super Store Sales Dashboard 

## Project Overview
The Super Store Sales Dashboard is an interactive Tableau visualization designed to analyze sales performance across product categories, regions, and customer segments in the U.S. and Canada. It provides a comprehensive view of key metrics like total orders, profit, and return rate, enabling users to monitor trends, identify high-performing areas, and uncover improvement opportunities within the business.

## Files Included
- `Superstore.xls` – Primary dataset for analysis
   - Orders table
   - Product_table
   - People table
   - Returns table
- `super_store_DB.twbx` – Tableau packaged workbook
- `dashboard-preview.png` – Dashboard screenshot

## Features / Highlights
- **KPI Summary**: Total Orders, Sales, Profit, Quantity, and Return Rate
- **Geo Map**: Sales distribution across U.S. and Canadian states/provinces
- **Bar Chart**: Most returned products by order count
- **Pareto Chart**: Cumulative sales by sub-category
- **Trend Analysis**: Monthly sales and profit trends over time
- **Segment Heatmap**: Order distribution by customer segment and region
- **Time Series Line**: Order trends over time
- **Interactive Filters**: Category, Country, Region, Sub-category, Return status, and Date range

## Tools & Technologies Used
- Tableau Public Desktop Edition Version 2.0
- Data source: Publicly available sample dataset 

## Calculated Field / Functions 
- Return Rate = (count of Returns / count of Orders) × 100
- Running Total of Sales using Table Calculation
- Segment-level aggregation by Region using COUNTD

## Key Insights / Observations
- Chairs, Phones, and Storage sub-categories contribute the most to overall sales.
- Return Rate is relatively low at 2.8%, with a few products returned more frequently.
- Western region shows higher order concentration for Consumer segment.
- Order volumes and profits increase significantly over the years, especially post-2023.
- Strong seasonality visible in the monthly order trends.

## Dashboard Preview
<img width="1787" height="883" alt="dashbaord-preview" src="https://github.com/user-attachments/assets/250998c8-c7b7-4ad9-a036-574e0c100d5c" />

## Future Enhancements
- Add Year-over-Year (YoY) comparison metrics for sales and orders
- Introduce dynamic parameter-based KPIs for deeper interactivity
- Segment customer analysis by profit contribution


