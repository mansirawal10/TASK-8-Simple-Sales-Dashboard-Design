# Simple Sales Dashboard – TASK 8

## Overview
This project demonstrates a **basic interactive sales dashboard** using **Power BI**.  
The dashboard visualizes **sales performance by product category, region, and month** to help business users quickly understand trends and key insights.

## Tools Used
- **Power BI Desktop** – Dashboard creation and visualization  
- **Python + Pandas** – Data cleaning and preprocessing  

## Dataset
- File: `Superstore_Sales.csv`  
- Columns: `Order Date`, `Region`, `Category`, `Sales`, `Profit`  
- Dataset was cleaned using Python to remove duplicates, handle missing values, and create a `Month-Year` column.

## Dashboard Visuals
- **Line Chart:** Sales trend over months (`Month-Year` vs `Sales`)  
- **Bar Chart:** Sales by region  
- **Donut Chart:** Sales by product category  
- **Slicer:** Filter by region or category  
- **Insight Button:** key takeaways  

## Key Insights
1. West region had the highest sales in Q3, driven mostly by Technology products.  
2. Furniture category sales dipped in February but rebounded strongly in April.  
3. Technology category consistently outperformed others across all months.  
4. March saw the highest monthly revenue overall, mainly due to increased Technology sales.  
5. East region had steady sales throughout the year, but growth was slower compared to West.  
6. Furniture category contributes less than 20% of total revenue, indicating potential for growth.  

## Deliverables
- **Power BI Dashboard File** (`.pbix`)
- **Raw Dataset** (`Superstore.csv`) 
- **Cleaned Dataset** (`Superstore_Sales_Clean.csv`)  
- **PDF/Screenshot** of the final dashboard  
- **Python Script for Data Cleaning** (`Data_Cleaning.py`)  

## Outcome
- Learn how to **clean data using Python**  
- Build a **clean, interactive Power BI dashboard**  
- Extract **key business insights visually** for decision-making
