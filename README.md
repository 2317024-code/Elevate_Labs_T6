# 📊 Sales Trend Analysis Using MySQL

## Project Overview
This project demonstrates how to perform **Sales Trend Analysis** on an e-commerce dataset using **MySQL**.  
The dataset consists of the following attributes (CSV file):
- Order details
- Transaction dates
- Sales amounts
- Product IDs
- Product Names  

The main goal is to analyze **monthly revenue** and **order volume trends**.

## Objectives
- Import sales data from a **CSV file** into MySQL.
- Use SQL queries to:
  - Calculate **monthly revenue**.
  - Count **monthly order volumes**.
  - Identify **sales trends over time**.
- Enable optional filters for specific periods (e.g: last 12 months).

## Tools & Technologies
- **MySQL 8.0**
- **MySQL Workbench**
- **CSV Dataset**

## Dataset
The dataset `online_sales.csv` contains the following columns:

Column Name - Description   

order_id - Unique ID for each order           

order_date - Date of the order (YYYY-MM-DD)     

amount - Total transaction amount (USD)     

product_id - Product identifier (e.g., P001)    

product_name - Human-readable product name        

## MySQL Setup

- Create Database and Table
- Import CSV File
- Move the online_sales.csv file into MySQL’s secure_file_priv folder and load the dataset

## Sales Trend Analysis Queries
- Monthly Revenue & Order Volume
- Last 12 Months Only

## Key Learnings
- How to import CSV data into MySQL using LOAD DATA INFILE.
- How to use aggregations (SUM, COUNT) with GROUP BY.
- How to analyze time-based sales trends.
- Filtering results using WHERE and sorting with ORDER BY.
