### Target Sales Analysis
This repository contains the analysis and insights generated from a dataset related to sales transactions, customers, and products at a retail store (Target). The project focuses on understanding customer behavior, sales trends, and financial performance using SQL, Python, and data visualization libraries like Matplotlib and Seaborn.

### Table of Contents
Project Overview
Installation
Data Files
Project Workflow
Analysis Highlights
Results and Visualizations
Technologies Used
Contributors

### Project Overview
The purpose of this project is to perform an in-depth analysis of sales data from a retail store. By leveraging SQL queries and Python, we analyzed customer purchase patterns, product categories' performance, and the overall revenue generated. 

### The key objectives include:
Identifying top product categories and sellers.
Analyzing customer purchasing behavior.
Calculating sales metrics like year-over-year growth, retention rates, and monthly sales trends.

The project includes several CSV files related to customers, orders, payments, products, and geolocation:

- **customers.csv**: Customer details
-**orders.csv**: Order transaction details
-**order_items.csv**: Information about items in each order
-**products.csv**: Product category and details
-**sellers.csv**: Information about sellers
-**geolocation.csv**: Geographical details of orders
-**payments.csv**: Payment details for each order

These CSV files were imported into a MySQL database for running SQL queries.

## Project Workflow
-**Data Ingestion**: Loading CSV files into the MySQL database and preparing them for analysis.
-**SQL Queries**: Writing and executing SQL queries to explore and analyze various aspects of sales and customer behavior.
-**Data Visualization**: Visualizing the results using Seaborn and Matplotlib to gain insights into the dataset.

-**Analysis Highlights**
### Here are some of the key insights obtained from the analysis:
-**Top Product Categories by Sales**: Categories like "Bed, Table, Bath" and "Furniture & Decoration" generate the highest revenue.
-**Year-over-Year Growth**: Sales growth over the years shows a significant increase in 2017.
-**Customer Retention**: The percentage of customers making repeat purchases within 6 months is computed.
-**Monthly Sales in 2018**: A detailed breakdown of monthly sales in 2018.
-**Customer State Distribution**: A visualization of where most customers are located.

### Results and Visualizations
Top 3 Customers by Year: Identified the top-spending customers for each year.
![image](https://github.com/user-attachments/assets/3e6def03-7237-4137-bfe6-4fb777608352)


Revenue by Seller: Sellers ranked by total revenue generated.
![image](https://github.com/user-attachments/assets/503a58eb-8b2d-44d5-a7e6-fdbc30ce3a48)

Example visualization:

### Technologies Used
**Languages**: SQL, Python
-**Database**: MySQL
-**Libraries**: Pandas, Matplotlib, Seaborn, MySQL Connector
-**Environment**: Anaconda

### Contributors
Seshi Reddy Syamala – Data Analyst
