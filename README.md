# Capstone_3
Tasked to analyze four years of sales performance for EmporiUm (a growing "virtual student bookstore" that blends in-store and online sales), I created an interactive Power BI report to highlight key insights and trends. 
This project was specifically designed to be presented to the West region's sales team, including the regional director, territory managers, and individual store managers.

## Key Features & Techniques Used

* Data Transformation: Cleaned, shaped, and combined raw sales data and product dimensions using Power Query Editor to prepare it for analysis.
* Data Modeling: Designed a robust relational data model connecting sales (fact) tables to lookup (dimension) tables, including a custom-built Date table for time intelligence.
* DAX Calculations: Created explicit DAX measures (like Total Sales) to aggregate sales across both online and in-store transactions.
* Row Level Security (RLS): Implemented an RLS role using DAX filtering to ensure the data strictly reflects the assigned "West" region, dynamically restricting national online sales to relevant states.

Please find the link below where I do a 10-minute walk through the data model and key business insights:

https://drive.google.com/file/d/1T-htm9zveKxlSpGHwPCkKiwSUu6FWlNy/view?usp=sharing
