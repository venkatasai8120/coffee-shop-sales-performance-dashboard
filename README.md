# Coffee Shop Sales Performance Dashboard


##  Project Overview

This project analyzes coffee shop sales data to understand business performance across different time periods, product categories, and store locations. An interactive Power BI dashboard was developed to track key metrics and uncover actionable insights for improving sales and operations.


##  Business Problem

The coffee shop business lacks clear visibility into:

* Sales trends across days, months, and hours
* High-performing and low-performing products
* Peak business hours and customer demand patterns
* Month-over-month changes in sales, orders, and quantity

Due to limited insights, decision-making is not fully data-driven, leading to missed opportunities in revenue growth and operational efficiency.


##  Objectives

* Analyze sales, orders, and quantity trends over time
* Identify top-performing products and categories
* Understand customer demand patterns by day and hour
* Track key KPIs and monitor business performance
* Enable data-driven decision making through visualization


## Key KPIs

* Total Sales
* Total Orders
* Total Quantity Sold
* Month-over-Month Growth (%)
* Daily Average Sales

##  Dashboard Features

*  Monthly filter with calendar view
*  Sales trend analysis with average line
*  Sales by product category and product type
*  Top 10 products by sales
*  Sales analysis by day and hour (heatmap)
*  Store location performance comparison
*  Weekday vs Weekend sales comparison


##  Key Insights

* Sales show clear patterns based on time and day
* Certain hours of the day generate significantly higher revenue
* A small number of products contribute to a large portion of sales
* Weekdays generate more consistent revenue compared to weekends
* Store performance varies, indicating opportunities for optimization


##  Recommendations

* Optimize staffing during peak hours to improve efficiency
* Focus on promoting high-performing products
* Improve marketing strategies for low-performing items
* Adjust inventory based on demand patterns
* Use time-based insights for better operational planning


## Tools & Technologies

* Power BI
* SQL (MySQL)
* Data Visualization
* Data Analysis
* DAX (Data Analysis Expressions)


## SQL Analysis

SQL was used to perform data cleaning, transformation, and KPI calculations to support the dashboard development.

### Data Preparation

* Converted transaction date and time into proper formats
* Cleaned and standardized dataset columns
* Verified and corrected data types


###  KPI Calculations

* Total Sales → `SUM(unit_price * transaction_qty)`
* Total Orders → `COUNT(transaction_id)`
* Total Quantity Sold → `SUM(transaction_qty)`


###  Advanced Analysis

* Month-over-Month growth using `LAG()` window function
* Daily sales trend and average comparison
* Weekday vs Weekend sales segmentation
* Sales by store location and product category
* Top 10 products by revenue
* Sales by day and hour for peak time analysis


### SQL Concepts Used

* Aggregations (SUM, COUNT, AVG)
* Window Functions (LAG)
* Date Functions (MONTH, DAY, DAYOFWEEK)
* Conditional Logic (CASE WHEN)
* Grouping & Sorting (GROUP BY, ORDER BY)


## Dataset

* Coffee Shop Sales Dataset (Excel / CSV format)
* Includes data on orders, products, sales, and timestamps


## Dashboard Preview

<img width="1196" height="799" alt="Screenshot 2026-03-25 220907" src="https://github.com/user-attachments/assets/b89a0236-739d-4c43-92f9-1df8c50edd0f" />



## How to Use

1. Download the `.pbix` file from the repository
2. Open it in Power BI Desktop
3. Explore interactive filters and visuals
4. Analyze insights across different dimensions

## Conclusion

This dashboard provides a comprehensive view of coffee shop sales performance, enabling business stakeholders to identify trends, optimize operations, and make informed decisions to drive growth.

