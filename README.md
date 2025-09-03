📊 Power BI Project – Café Sales & Customer Insights


🔹 Project Overview
This project analyzes sales and customer transactions for a local café using Microsoft Power BI.
The goal was to design an interactive dashboard to monitor revenue, product performance, and customer trends.

🔹 Tools & Skills Used
Microsoft Power BI Desktop
DAX (Data Analysis Expressions) for KPIs
Data Modeling (flat table + star schema design concept)
Data Visualization (KPI Cards, Column & Line Charts, Donut Chart, Slicers)

🔹Dataset
The dataset contains café sales transactions with fields:
Date – transaction date
Product – item sold (Coffee, Sandwich, Pastry, etc.)
Category – product group (Beverages, Snacks, Pastries)
CustomerID – unique customer identifier
TotalPrice – sales amount per transaction
👉 The dataset was a single table, so no advanced relationships were required.

🔹 DAX Measures
-- Total Sales
Total Sales = SUM(cafe_sales_data[TotalPrice])

-- Total Customers
Total Customers = DISTINCTCOUNT(cafe_sales_data[CustomerID])

-- Average Bill
Average Bill = AVERAGE(cafe_sales_data[TotalPrice])

-- Sales per Customer
Sales per Customer = [Total Sales] / [Total Customers]

-- Data Range (Min & Max Date)
Min Date = MIN(cafe_sales_data[Date])
Max Date = MAX(cafe_sales_data[Date])

🔹 Dashboard Visuals
The dashboard was designed on one page for simplicity and storytelling:
KPI Cards: Total Sales, Total Customers, Average Bill
Column Chart: Sales by Product
Line Chart: Sales Trend over Time
Donut Chart: Sales by Category
Slicers: Date filter & Category filter

🔹 Key Insights

☕ Top Products – Coffee and Sandwiches generated the highest sales.

📊 Category Analysis – Beverages contributed the largest share of revenue.

👥 Customer Behavior – A significant number of repeat customers show loyalty.

📈 Sales Trend – Weekends recorded higher sales compared to weekdays.

🔹 Recommendations

Introduce combo deals (e.g., Coffee + Pastry) to boost cross-sales.
Run weekend promotions to maximize high footfall.
Expand beverage menu as it drives most revenue.
Implement a customer loyalty program for repeat buyers.

🔹 Project Files

📁 Cafe_Sales.pbix → Power BI Dashboard file

📸 Dashboard_Screenshots/ → Images of the dashboard

📝 README.md → Project documentation

🔹 Conclusion

This project demonstrates:
✅ Creating a Power BI dashboard from scratch
✅ Using DAX measures for dynamic KPIs
✅ Applying data visualization best practices
✅ Extracting actionable business insights

🔹 Connect with Me

📌 If you liked this project, feel free to connect with me on LinkedIn

📌 More projects available on GitHub
