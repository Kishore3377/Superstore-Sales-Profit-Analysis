# Superstore Sales & Profit Analysis

## Project Overview

This project analyzes a Superstore sales dataset to understand sales performance, profitability, discount impact, product performance, category performance, and regional performance.

The analysis was performed using **Python, Pandas, NumPy, Matplotlib, and MySQL**.

## Dataset

* **Rows:** 10,194
* **Columns:** 21
* **Key fields:** Order Date, Customer, Region, Category, Product, Sales, Quantity, Discount, and Profit.

## Business Questions

The analysis focuses on questions such as:

* How much revenue was generated?
* How much profit was generated?
* What is the overall profit margin?
* Which categories generate the most revenue?
* Which categories generate the most profit?
* Which products are highly profitable?
* Which products generate losses?
* How does discounting affect profitability?
* Which regions contribute most to revenue and profit?
* How can the cleaned dataset be prepared for SQL analysis?

## Key Results

| Metric        |        Result |
| ------------- | ------------: |
| Total Revenue | $2,326,534.35 |
| Total Profit  |   $292,296.81 |
| Profit Margin |        12.56% |

The analysis found differences between revenue performance and profitability across categories. Technology generated approximately **$839.9K revenue and $146.5K profit**, while Furniture generated approximately **$754.7K revenue but only $19.7K profit**.

Discount analysis also showed that several higher-discount levels were associated with negative profit. For example, the 30%, 40%, 50%, 60%, 70%, and 80% discount groups generated negative total profit in this dataset.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* MySQL
* Jupyter Notebook

## Analysis Workflow

1. Load the dataset
2. Understand the dataset structure
3. Check data types
4. Check missing values
5. Check duplicate records
6. Convert date columns
7. Calculate business KPIs
8. Analyze categories
9. Analyze products
10. Identify loss-making products
11. Analyze regional performance
12. Analyze discounts and profitability
13. Create visualizations
14. Export cleaned data
15. Load data into MySQL
16. Validate Python and MySQL totals
17. Create relational tables for customers, orders, products, and order items

The dataset was successfully loaded into MySQL, with **10,194 rows inserted and validated**.

## Project Outcome

This project was built as a practical Data Analyst exercise, with emphasis on moving from **raw data → exploration → business metrics → analysis → visualization → database integration → business insights**.

It is part of my ongoing Data Analyst portfolio development.
