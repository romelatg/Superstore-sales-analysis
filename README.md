# Superstore Sales Analysis

Data analysis project using Python, SQL Server, and Power BI.

**Dataset:** [Superstore Sales Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## Project Pipeline

`Raw CSV → Python/pandas → SQL Server → Power BI`

---

## Dashboard Preview

![Dashboard](Final/images/PowerBISC.png)

---

## Python / pandas

- Standardized column names
- Split flat table into a star schema:
  - `fact_sales`
  - `dim_customer`
  - `dim_product`

**Column standardization:**

![Standardized Table](Final/images/Pandas-SQL-FIX.png)

---

## SQL Server

- Loaded all 3 tables into `SuperstoreDB`
- Built star schema relationships

**Star Schema Model:**

![Star Schema](Final/images/star%20schema.png)

---

## SQL Business Questions

### 1. Total revenue by region
![Question 1](Final/images/Question%201.png)

### 2. Top 10 products by sales
![Question 2](Final/images/Question%202.png)

### 3. Monthly revenue trend
![Question 3](Final/images/Question%203.png)

### 4. Customers with more than 5 orders
![Question 4](Final/images/Question%204.png)

### 5. Which category has the highest average order value
![Question 5](Final/images/Question%205.png)

---

## Power BI

- Connected directly to SQL Server
- Built star schema relationships in Model View
- Created interactive dashboard with year slicer

[Download Dashboard PDF](Final/power%20bi/DashBoard.pdf)

---

## Notes

> The Power BI file connects to a local SQL Server instance (`SuperstoreDB`).
> To use it locally, import the CSV files from the `/data` folder into your own
> SQL Server instance, or connect Power BI directly to the CSV files.
