# Sales-Analytics-Dashboard-
Project Overview  This project focuses on analyzing sales data to understand product performance, regional trends, and customer behavior. The dashboard provides insights into total sales, profit, and quantity distribution across different dimensions.
Business Objective

<img width="1055" height="708" alt="image" src="https://github.com/user-attachments/assets/f588fd23-8555-4169-89ac-04340c7d4f56" />


Businesses need to track sales performance and identify high-performing products, regions, and customer segments. This project helps in analyzing sales trends and supports data-driven decision-making.

Data Cleaning & Preparation
Verified and cleaned dataset for missing values
Standardized column names
Ensured correct data types (numeric, date)
Created calculated fields like Total Sales and Profit

Tools & Technologies
Microsoft Excel (Pivot Tables & Charts)
Power BI (Dashboard & Visualization

)SQL (Data Analysis & Queries)

Dashboard Features
Region-wise product distribution
Product-wise sales and profit analysis
Customer segmentation (Consumer vs Corporate)
Sales and profit trends
Quantity distribution analysis

Key Insights
Mobile and Laptop generate the highest sales revenue
Corporate customers contribute higher profit compared to consumers
South region has highest quantity sold
West region shows lower sales performance compared to others
Files Included
Sales Dataset (Excel)
Pivot Table Analysis
Power BI Dashboard (.pbix)
Dashboard Screenshots
Project Workflow
Data Collection
Data Cleaning
Data Analysis using Excel Pivot Tables
Data Visualization in Power BI
Insights Generation

Sample SQL Queries

-- Total Sales by Product
SELECT product, SUM(total_sales) AS total_sales
FROM sales
GROUP BY product;

-- Profit by Customer Type
SELECT customer_type, SUM(profit) AS total_profit
FROM sales
GROUP BY customer_type;

-- Region-wise Sales
SELECT region, SUM(total_sales) AS total_sales
FROM sales
GROUP BY region;
🚀 Future Improvements
Add time-based trend analysis (monthly/yearly)
Build predictive sales model
Add dynamic filters and drill-through in Power BI
👤 Author

Sree Biswas
Aspiring Data Analyst | SQL | Excel | Power BI

sales-dashboard/
│
├── data/
│   └── sales_data.xlsx
│
├── dashboard/
│   └── sales_dashboard.pbix
│
├── images/
│   └── dashboard_screenshot.png
│
├── sql/
│   └── queries.sql
│
└── README.md
