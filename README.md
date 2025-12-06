# Retail Sales Analysis Project

## 📌 Project Overview
This project performs end-to-end retail sales analysis using:

- Python for data cleaning, EDA, and Market Basket Analysis
- SQL for analytical queries and business insights
- Power BI for an interactive dashboard
- Apriori Algorithm for association rule mining

The goal is to understand customer behavior, product performance, and sales trends from an online retail dataset.

---

## 📂 Dataset Description
The dataset used is the Online Retail Dataset, containing real sales transactions from a UK-based gift retailer.

### Key Columns
- invoice_no – Unique order ID  
- stock_code – Item code  
- description – Product name  
- quantity – Total quantity purchased  
- invoice_date – Date & time of transaction  
- unit_price – Price per product  
- customer_id – Customer identifier  
- country – Customer country  
- total_price – (quantity × unit_price) *(created)*  
- Month – Extracted month *(created)*  

---

## 🐍 Python Part

### ✔ Data Cleaning
- Removed missing values  
- Removed canceled invoices  
- Removed negative quantities  
- Converted invoice_date to datetime  
- Created new columns: total_price, Month  
- Exported cleaned file: cleaned_retail.csv  

### ✔ Exploratory Data Analysis (EDA)
- Monthly revenue trend  
- Country-wise revenue visualization  
- Product performance  
- Quantity distribution  

### ✔ Apriori Market Basket Analysis
Steps:
1. Created basket matrix for top 50 products  
2. Converted quantity values to True/False  
3. Generated frequent itemsets using Apriori  
4. Generated association rules  
5. Identified combinations of products bought together  

---

## 🧮 SQL Part (8 Key Analyses)

### 1. Most Active Customers
Identified customers with the highest purchase frequency.

### 2. Monthly Sales Trend
Calculated revenue month-wise to understand seasonal patterns.

### 3. Most Common Products per Invoice
Counted how many products appear together in a single invoice.

### 4. Top 10 Best-Selling Products
Ranked products based on total quantity sold.

### 5. Top Countries by Customer Count
Found countries with the highest number of customers.

### 6. Invoices With More Than 10 Items
Detected bulk purchases / large orders.

### 7. Products Sold in the Most Countries
Identified globally popular or widely sold items.

### 8. Daily Sales Count
Counted daily invoices to analyze sales traffic patterns.

---

## 📊 Power BI Dashboard

### ⭐ KPIs
- Total Revenue  
- Total Quantity Sold  
- Total Customers  
- Total Invoices  

### ⭐ Charts (5)
1. Monthly Trend Line Chart
2. Revenue by Country  
3. Top 10 Productsy  
4. Quantity by Month    

### ⭐ Filters (Slicers)
- Month  
- Country  
- StockCode  
- CustomerID  

---

## 📌 Business Insights
- Sales peak in November–December.  
- UK is the largest market.  
- Few products contribute majority of revenue (Pareto 80/20 rule).  
- Many invoices contain 2–6 items → strong cross-selling opportunity.  
- Apriori rules show product pairings for combo offers.  
- Some countries have high AOV—good for targeted campaigns.

---

## 🚀 Tools Used
- Python: Pandas, Matplotlib, Mlxtend  
- SQL: MySQL / SQL Server  
- Power BI Desktop  

---

## 📁 Project Deliverables
- cleaned_retail.csv (clean dataset)  
- Python notebook (data cleaning + EDA + Apriori)  
- SQL queries  
- Power BI dashboard (.pbix)  
- Final report  
- README.md  

---

## 🙌 Author
Project prepared by **Aakash**  
Complete analytics pipeline: Python → SQL → Power BI.
