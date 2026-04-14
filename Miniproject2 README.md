📊 Superstore Sales Performance Dashboard
📌 Overview

This project focuses on analyzing Superstore sales data using SQL and Excel.
The main aim is to understand sales performance, profit distribution, and product demand across different regions and categories.

🛠️ Tools Used
SQL Server (SSMS)
Microsoft Excel
📂 Dataset Details

The dataset includes:

Region
Category & Sub-Category
Sales
Profit
Quantity
Segment

🧠 SQL Analysis
SQL queries are used to extract important insights such as:

Total Sales
Total Profit
Sales by Region
Profit by Category
Quantity by Sub-Category

Example query:

SELECT SUM(Sales) AS Total_Sales FROM dbo.SSDT;

SELECT Region, SUM(Sales) AS Total_Sales
FROM dbo.SSDT
GROUP BY Region;

📊 Dashboard Features

The Excel dashboard provides an interactive view with:

Filters:
Region
Category
Segment

Key Metrics:
Total Sales
Total Profit
Total Quantity

Visualizations:
Sales by Region (Bar Chart)  <img width="1920" height="826" alt="miniproject2exce dashboard" src="https://github.com/user-attachments/assets/26665dd0-56b3-43de-bbbf-8247e51409e4" />
<img width="1920" height="1031" alt="miniproject 2 sql queries" src="https://github.com/user-attachments/assets/5944480f-876e-4038-8cf2-32f738def5d3" />

Profit by Category (Bar Chart)
Quantity by Category
Category Distribution (Pie Chart)

📸 Screenshots
SQL Output
Excel Dashboard

🔍 Key Insights
West region shows the highest sales performance.
Office Supplies category has the highest profit.
Consumer segment contributes more to overall sales.
Sales and quantity vary across regions and categories.

🎯 Conclusion

This project shows how SQL and Excel can be used together to analyze data and create a simple interactive dashboard for business insights.
