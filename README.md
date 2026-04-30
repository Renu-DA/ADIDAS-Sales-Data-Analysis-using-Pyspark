# ADIDAS-Sales-Data-Analysis-using-Pyspark

Project Title- Adidas Retail Sales Analytics Pipeline (Medallion Architecture)
----------------------------------------------------------------------------------------------------------------------------------------------------
Business Requirements -

•	Total Sales, Total Profit, Avg price per unit, Total units sold
•	total sales by month
•	total sales by state
•	total sales by region
•	total sales by product
•	total sales by retailer
•	units sold by product category and sales method
•	Top performing Cities by profit

-----------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ Tech Stack

Pyspark
Databricks 

------------------------------------------------------------------------------------------------------------------------------------------------------

🥉 Bronze Layer (Raw Ingestion)

Ingested raw CSV files from file store
Used Pyspark to ingest/read data
Stored data as-is (no transformation)


🥈 Silver Layer (Data Cleaning & Transformation)
🔹 Challenges faced:
Numbers stored with Commas such as "1,200"
Percentages like "50%"
Mixed date formats (1/1/2020, 21/01/2020)

🥇 Gold Layer (Business Aggregations)
•	Total Sales, Total Profit, Avg price per unit, Total units sold
•	total sales by month
•	total sales by state
•	total sales by region
•	total sales by product
•	total sales by retailer
•	units sold by product category and sales method
•	Top performing Cities by profit


🧠 Feature Engineering
Derived new columns from Invoice Date column such as month column


📊 Key Metrics & Analysis (PySpark)
•	Calculated Total Sales, Total Profit, Average Price per Unit, and Total Units Sold using aggregation functions 
•	Analyzed Total Sales by Month to identify seasonal trends and monthly performance patterns 
•	Computed Total Sales by State to evaluate geographic sales distribution 
•	Derived Total Sales by Region to compare regional business performance 
•	Aggregated Total Sales by Product to identify high-performing product categories 
•	Evaluated Total Sales by Retailer to measure retailer-wise contribution 
•	Analyzed Units Sold by Product Category and Sales Method (In-store vs Outlet) to understand customer buying behavior and channel performance 
•	Identified Top Performing Cities based on Operating Profit to highlight high-value markets


