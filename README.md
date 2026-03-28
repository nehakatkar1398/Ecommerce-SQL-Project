# 📊 E-Commerce SQL Data Analysis Project

# 📌 Project Overview
This project focuses on analyzing an e-commerce dataset using SQL to extract meaningful business insights.
It demonstrates strong SQL skills including data modeling, querying, and analytical thinking.

# 🗂️ Dataset Description
The project is built using three relational tables:

# 👤 Customers
* customer_id (Primary Key)
* customer_name
* email
* city
* country
* loyalty_status

# 📦 Products
* product_id (Primary Key)
* product_name
* category
* price
* stock_quantity

# 🧾 Orders
* order_id (Primary Key)
* customer_id (Foreign Key)
* product_id (Foreign Key)
* order_date
* quantity
* total_amount
* payment_method
* order_status

# 🔗 Data Relationships
* One customer can place multiple orders
* One product can appear in multiple orders
* Orders table connects customers and products

# ⚙️ SQL Concepts Used
* ✅ Joins (INNER JOIN)
* ✅ Aggregations (SUM, COUNT, AVG)
* ✅ Group By & Order By
* ✅ Primary Key & Foreign Key
* ✅ Data Cleaning (handling encoding issues, column fixes)
* ✅ Window Functions (RANK)

# 📈 Key Analysis & Queries
* 🔹 Total Orders per Customer
* 🔹 Revenue by Product
* 🔹 Top Customers by Revenue
* 🔹 Monthly Sales Trend
* 🔹 Order Status Analysis
* 🔹 Payment Method Analysis
* 🔹 Revenue by Order Status
* 🔹 Top 3 Products by Revenue
* 🔹 Customer Ranking using Window Functions
* 🔹 Average Order Value

# 💡 Key Insights
* High-value customers contribute significantly to overall revenue
* A small number of products generate the majority of sales
* Monthly trends indicate fluctuations in sales performance
* Cancelled orders lead to revenue loss and impact business growth
* Payment method analysis shows customer preference patterns

# 📸 Project Screenshots
# 🔹 Table Structure (example - Customers table)
[![Table Structure](images/table_structure.png)](https://github.com/nehakatkar1398/Ecommerce-SQL-Project/blob/cc8de27a4b95ea43cd96c50458467fce168c0be7/Image/Custemers%20Table%20Structure.png)

# 🔹 Table Relationships (Joins)
[![Joins](images/joins.png)](https://github.com/nehakatkar1398/Ecommerce-SQL-Project/blob/4287f43286914ee52df15b99b7342713508d4dc5/Image/Inner%20Join%20.png)

# 🔹 Revenue by Product
[![Revenue by Product](images/revenue_by_product.png)](https://github.com/nehakatkar1398/Ecommerce-SQL-Project/blob/60781ef5458d0729e1c6e7e34e48be81bc1f8870/Image/Total%20Reveneu%20by%20each%20product.png)

# 🔹 Top Customers
[![Top Customers](images/top_customers.png)](https://github.com/nehakatkar1398/Ecommerce-SQL-Project/blob/e96446e4ca92cdeaee1db2d15f136edcef9f3f56/Image/Top%203%20products%20by%20revenue.png)

# 🔹 Monthly Sales Trend
[![Monthly Trend](images/monthly_trend.png)](https://github.com/nehakatkar1398/Ecommerce-SQL-Project/blob/e96446e4ca92cdeaee1db2d15f136edcef9f3f56/Image/Monthly%20Sales%20Trend.png)

# 🔹 Order Status Analysis
![Order Status](images/order_status.png)

# 🔹 Payment Method Analysis
![Payment Method](images/payment_method.png)


# ▶️ How to Run This Project
1. Import CSV files from the `dataset` folder into MySQL
2. Run table creation queries
3. Execute SQL queries from `queries.sql`
4. Analyze outputs to derive insights

# 🛠️ Tools Used
* MySQL
* MySQL Workbench

# 🚀 Project Highlights
* Designed a relational database schema
* Implemented primary and foreign key constraints
* Performed real-world business analysis using SQL
* Generated actionable insights from transactional data
  
# 📌 Conclusion
This project demonstrates practical SQL skills required for a Data Analyst role, including data modeling, querying, and insight generation.
It reflects the ability to work with structured data and solve real-world business problems.

# ⭐ Author
Neha Katkar

**Neha Katkar**
Aspiring Data Analyst
