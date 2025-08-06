Retail Sales Analysis SQL Project
Beginner-friendly SQL project to explore, clean, and analyze retail sales data. It involves database setup, EDA, and answering business questions using real-world SQL queries—ideal for aspiring data analysts.

OBJECTIVE
Retail Sales Analysis SQL Project
Set up a retail sales database, clean missing data, perform exploratory analysis, and answer key business questions using SQL. A beginner-friendly project to build strong SQL and data analysis skills.

Project Structure
- Database Creation: The project starts by creating a database named p1_retail_db.
- Table Creation: A table named retail_sales is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.
 CREATE DATABASE p1_retail_db;

CREATE TABLE retail_sales
(
    transactions_id INT PRIMARY KEY,
    sale_date DATE,	
    sale_time TIME,
    customer_id INT,	
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,	
    cogs FLOAT,
    total_sale FLOAT
);
