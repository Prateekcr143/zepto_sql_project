# zepto_sql_project

 Zepto Inventory Analysis (SQL Project)

This project analyzes inventory and stock data from a grocery delivery company (like Zepto).
The analysis highlights low-stock issues, out-of-stock products, and category-level shortages to support better inventory planning and decision-making.

 Analysis Highlights

Dataset Size: 1 CSV file (zepto_v2.csv)

Key Fields: Category, Product Name, MRP, Discounts, Available Quantity, Stock Status

Business Focus:

Identify low-stock products (≤ 2 units available)

Detect fully out-of-stock items

Compare shortages across categories

Key Findings

Low Stock Products: Multiple items with critically low quantities.

Out-of-Stock Products: Several items completely unavailable, risking customer dissatisfaction.

Category Impact: Fruits & Vegetables are the most understocked compared to packaged food items.

# Strategic Insights

Improve Demand Forecasting: Adjust inventory based on sales trends and seasonality.

Prioritize Restocking: Focus on high-demand categories (e.g., Fruits & Vegetables).

Set Automated Alerts: Trigger notifications when availableQuantity ≤ 2.

Enhance Transparency: Show real-time stock levels to customers to reduce frustration.

🛠 Tools & Technologies

Database: MySQL

Dataset: CSV (zepto_v2.csv)

SQL Queries: MySQL Workbench

Version Control: Git & GitHub

