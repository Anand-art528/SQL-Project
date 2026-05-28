# ☕ Coffee Shop Sales Analysis using SQL

## 📌 Project Overview

This project focuses on analyzing coffee shop sales data using SQL to generate meaningful business insights related to sales performance, customer behavior, product demand, city-wise market potential, and business expansion opportunities.

The project demonstrates database creation, relational database management, data importing, advanced SQL querying, and business analysis using real-world datasets.

---

# 🛠 Tools & Technologies Used

* SQL Server
* T-SQL
* Relational Database Management
* SQL Joins
* CTEs (Common Table Expressions)
* Window Functions
* Aggregate Functions
* Business Data Analysis

---

# 📂 Dataset Used

The project contains the following datasets:

* `city.csv`
* `products.csv`
* `customers.csv`
* `sales.csv`

---

# 🗂 Database Schema

The following schema represents the relational database structure used in this project.

![Database Schema](image\(13\).png)

---

# 🗄 Database Tables

## 1. City

Contains:

* city_id
* city_name
* population
* estimated_rent
* city_rank

---

## 2. Products

Contains:

* product_id
* product_name
* price

---

## 3. Customers

Contains:

* customer_id
* customer_name
* city_id

---

## 4. Sales

Contains:

* sale_id
* sale_date
* product_id
* customer_id
* total
* rating

---

# 🔑 Key SQL Concepts Used

* Database Creation
* Table Creation
* Primary Keys
* Foreign Keys
* BULK INSERT
* INNER JOIN
* GROUP BY
* Aggregate Functions
* CTE (Common Table Expressions)
* Window Functions
* DENSE_RANK()
* LAG()
* Date Functions
* Revenue Analysis
* Sales Growth Analysis

---

# 📊 Business Problems Solved

## 1. Estimated Coffee Consumers by City

Estimated coffee consumers based on city population.

## 2. Revenue Analysis

Calculated total revenue generated during Q4 of 2023.

## 3. Product Performance Analysis

Identified the most sold coffee products.

## 4. Customer Spending Analysis

Calculated average sales amount per customer in each city.

## 5. Market Size Analysis

Compared population size with actual customer count.

## 6. Top Selling Products by City

Identified top 3 products in each city using ranking functions.

## 7. Unique Customer Analysis

Measured customer reach across cities.

## 8. Revenue vs Rent Analysis

Compared customer revenue with estimated city rent.

## 9. Monthly Sales Growth Analysis

Calculated month-over-month sales growth using window functions.

## 10. Business Expansion Recommendation

Identified the best cities for business expansion based on:

* Revenue
* Customer count
* Rent efficiency
* Market size

---

# 📈 Key Insights

* Pune generated the highest overall revenue.
* Chennai showed balanced revenue and operational cost.
* Jaipur had strong customer efficiency with lower rent.
* Bangalore showed high rent risk despite strong sales potential.
* Delhi had a large market size but lower customer spending efficiency.

---

# ✅ Final Business Recommendations

## 🔥 Recommended Cities for Expansion

### 1. Pune

* Highest revenue
* Strong customer spending
* Good customer base
* Moderate operational cost

### 2. Chennai

* Balanced earning vs cost
* Strong customer demand
* Stable growth opportunity

### 3. Jaipur

* Low rent per customer
* Efficient business economics
* High customer engagement

---

# 🚀 Project Outcome

This project helped in:

* Understanding real-world SQL business analysis
* Improving SQL querying skills
* Working with relational databases
* Applying analytical thinking to solve business problems
* Practicing advanced SQL concepts on structured datasets

---

# 📁 Project Structure

```bash
Coffee-Shop-SQL-Project/
│
├── Coffee_Shop_SQL_Project.sql
├── README.md
├── city.csv
├── products.csv
├── customers.csv
├── sales.csv
└── image(13).png
```

---

# 👨‍💻 Author

Anand Yadav

MBA (Finance & Operations Analytics)
Aspiring Data Analyst | SQL | Power BI | Python | Excel
