# 📊 Vendor Performance Analysis
   ##Using Python,Sql
This repository contains a complete **Vendor Performance Analysis** project, designed to help businesses optimize vendor management, inventory decisions, and profitability. The analysis was conducted using **Python**, **Jupyter Notebook**, and **SQLite**, and targets key business stakeholders who need insights into underperforming brands, top vendors, inventory turnover, and purchasing strategies.

---

## 🚀 Project Overview

Retail and wholesale companies often face challenges such as:
- High inventory holding costs
- Vendor over-dependency
- Poor profit margins on certain products

This project analyzes vendor and product performance using sales, cost, and inventory data to answer key questions like:
- Which vendors are most and least profitable?
- Are bulk purchases reducing unit costs?
- Which products have high inventory but low turnover?
- Should certain brands be promoted or discounted?


## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **SQLite3** (via `sqlite3` module)
- **pandas**, **NumPy** – data wrangling & transformations
- **Matplotlib**, **Seaborn** – data visualization

---

## 📊 Business Questions Addressed

1. **Which brands should be targeted for promotions or price adjustment?**
2. **Which vendors contribute the most to sales and profit?**
3. **Does bulk purchasing reduce unit cost?**
4. **Which vendors have low inventory turnover?**
5. **Are high-margin vendors actually profitable?**

---

## 🔍 Key Insights from the Report

- **198 brands** have high margins but low sales — ideal for promotion or pricing strategy updates.
- **Top 10 vendors** contribute **66%** of total purchases, indicating high dependency risk.
- **Bulk purchases** can lower unit costs by **72%**, improving overall profit margins.
- **$2.71M** worth of unsold inventory identified from slow-moving vendors.
- **Statistical testing confirms** significant profit margin differences between high- and low-performing vendors.

---

## 📈 Methodology

1. **Data Import & Cleaning**
   - Load sales, cost, and inventory data from Excel/CSV
   - Handle missing values, remove invalid records
2. **Data Conversion to SQL**
   - Convert structured data into SQLite tables
   - Query and join relevant tables for KPIs
3. **Exploratory Data Analysis (EDA)**
   - Use pandas and SQL queries to explore performance metrics
   - Plot trends and outliers
4. **Statistical Testing**
   - Perform hypothesis testing to validate margin differences
   - Confidence interval estimation for top vs. low-performing vendors

---

