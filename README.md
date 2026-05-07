# BMW-sales-Dashboard
 Project Overview
This project involves a comprehensive analysis of BMW sales data to track market performance, pricing strategies, and inventory turnover. The dashboard transforms raw automotive data into actionable insights for dealership management and stakeholders.

Objective: To analyze sales trends across different BMW models (Series, SUVs, M-Performance) and optimize pricing strategies based on vehicle age and mileage.

Key Question: Which vehicle features (Fuel Type, Transmission, Engine Size) have the highest impact on resale value and sales velocity?

 Key Insights & KPIs
Total Sales Revenue: Aggregated revenue across all models and regions.

Average Selling Price (ASP): Monitoring price fluctuations across different series (e.g., 3 Series vs. X5).

Depreciation Analysis: Visualizing the correlation between Mileage/Age and Sale Price.

Inventory Mix: Breakdown of sales by Fuel Type (Petrol, Diesel, Hybrid, Electric) and Transmission.

Top Performing Models: Identifying the "Volume Drivers" vs. "High-Margin" vehicles.

 Tech Stack
Data Visualization: Power BI / Tableau

Data Engineering: SQL (for data extraction and joining vehicle specifications), Power Query.

Statistical Analysis: Excel (Descriptive statistics for price distribution).

Advanced Analytics: Integration of Regression Insights to show predicted vs. actual sales prices.

 Data Transformation & Modeling
Data Cleaning: Addressed missing values in engine displacement and standardized model naming conventions.

Feature Engineering: Created a "Vehicle Age" column from the year of manufacture and categorized "Mileage Brackets" (e.g., Low, Mid, High).

DAX / Calculations:

Total Revenue = SUM(Sales[Price])

Average Discount % = DIVIDE([Discount_Amount], [MSRP])

Data Model: Implemented a Star Schema with a central Sales Fact table connected to Dimension tables for Date, Model Specs, and Geography.

 Dashboard Preview
(Replace the link below with your actual image path after uploading to GitHub)

 Business Recommendations
Stock Optimization: Focus inventory procurement on Hybrid/Electric models if the trend shows a 15% MoM increase in demand.

Pricing Strategy: Adjust prices for vehicles older than 5 years as the data shows a steep decline in valuation beyond this threshold.

Regional Allocation: Shift high-performance 'M' models to regions with higher average transaction values.
