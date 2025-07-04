# RETAIL-DATA-ANALYSIS
📁 Project: cs_retail
This project focuses on data preparation and business analysis using SQL on a retail dataset containing customer details, product categories, and transaction history.

📌 Objective
To perform data cleaning, exploration, and analysis to extract actionable insights from the retail data.

🧱 Dataset Structure
The project uses three core tables:

Customer: Contains customer demographics (age, gender, city, DOB).

prod_cat_info: Maps product categories and subcategories.

Transactions: Records purchase details like quantity, store type, and amount.

🧹 Section 1: Data Preparation & Understanding
Total number of rows in each table.

Identify return transactions (Qty < 0).

Convert tran_date and DOB into standard date formats.

Calculate time range covered in the transaction data.

Map product category from subcategory name.

📈 Section 2: Data Analysis
Key business questions answered:

Which store type has the most transactions?

Count of customers by gender.

City with the maximum number of customers.

Count of subcategories in 'Books'.

Maximum quantity sold in a transaction.

Revenue generation by product categories (Electronics, Books, etc.).

Customers with more than 10 purchases.

Revenue from Electronics and Clothing via Flagship stores.

Subcategory-level revenue from male customers for electronics.

Top 5 selling subcategories with their return rate percentage.

Revenue from customers aged 25-35 in the last 30 days.

Product categories with highest recent returns.

Best performing store type by revenue and quantity sold.

Product categories with above-average revenue.

Top subcategories by revenue from top 5 most sold categories.

🛠️ Tech Stack
SQL Server / MySQL / PostgreSQL
