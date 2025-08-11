# Retail Sales EDA (SQL)

This project contain SQL scripts for performing Exploratory Data Analysis (EDA) on retail sales 
data stored in a data warehouse,
the goal is to generate insights on sales performance, product categories
and revenue distribution.

# 📊 Analysis Overview

The SQL queries in this project cover:

- Total Sales and Quantity Sold
- Average Selling Price
- Number of Orders, Products and Customers
- Customers by Country and Gender
- Products by Category
- Average Product Costs per Category
- Total Revenue by Category
- Total Revenue by Customer
- Sales distribution by Country
- Top 5 Best-Selling Product
- Top 5 Worst-Performing Products

# 🛠️ Technologies Used

- SQL (Structured Query Language)
- Data Warehouse Schema with:
    - fact_sale table
    - dim_customers table
    - dim_products table

# 📁 Dataset Structure

## Fact Table

- fact_sale: sales transaction containing products, customers and sales metrics.

## Dimension Table

- dim_customers: customers details such as country, gender and identity
- dim_products: products details including category, cost and identifiers

# 📈 Insight Example

## From this EDA, you can identify

- Top-performing product category
- Customer distribution by demographics and geography
- Revenue contribution by customer
- Product performance ranking

