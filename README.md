# Superstore-sales-analysis

Data analysis project using Python, SQL Server, and Power BI

Dataset
Source: Kaggle — Superstore Sales Dataset
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

Project Pipeline
Raw CSV → Python/pandas → SQL Server → Power BI

Python / pandas:
  -Standardized columns
  -Split flat table into a star schema:
    Fact_sales
    Dim_customer
    Dim_Product

SQL Server:
  -Loaded all 3 tables into SuperstoreDB
  -Wrote 5 business queries

Power BI:
  -Connected directly to SQL Server
  -Built star schema relationships in Model View
  -Created interactive dashboard with year slicer
  
