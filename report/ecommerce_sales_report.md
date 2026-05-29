# E-Commerce Sales Analysis Report

## Objective

The objective of this project is to analyze e-commerce sales data and identify key business insights related to revenue, profit, customer behavior, product performance, and payment preferences.

---

## Dataset Overview

The project uses two datasets:

### Orders Dataset

Contains customer and location information.

Columns:

* Order ID
* Order Date
* CustomerName
* State
* City

### Details Dataset

Contains transaction details.

Columns:

* Order ID
* Amount
* Profit
* Quantity
* Category
* Sub-Category
* PaymentMode

---

## Data Preparation

Steps performed:

1. Loaded both datasets using Pandas.
2. Inspected column names and data types.
3. Verified dataset dimensions.
4. Merged both datasets using Order ID.
5. Created a consolidated dataset for analysis.

---

## Analysis Performed

### Revenue Analysis

* Total Revenue: ₹437,771
* Electronics generated the highest revenue.

### Profit Analysis

* Total Profit: ₹36,963
* Clothing generated the highest profit.

### Product Analysis

* Saree was the highest-selling sub-category by quantity.

### Customer Analysis

* Harivansh generated the highest revenue.
* Madan Mohan generated the highest profit.

### State Analysis

* Maharashtra generated the highest revenue.
* Madhya Pradesh generated the highest profit.

### Payment Analysis

* COD was the most frequently used payment mode.

---

## Visualizations Created

1. Revenue by Category
2. Profit by Category
3. Top 5 States by Revenue
4. Payment Mode Distribution

---

## Key Business Insights

* Electronics drives the largest share of revenue.
* Clothing contributes the highest profit.
* Cash on Delivery remains the most preferred payment method.
* Revenue and profit leaders differ, indicating variations in product margins.
* Maharashtra is the strongest revenue-generating state.
* Madhya Pradesh contributes the highest overall profit.

---

## Conclusion

This project demonstrates the use of Python, Pandas, and Matplotlib for data analysis and visualization. Business insights were extracted through data aggregation, filtering, grouping, and visualization techniques commonly used in real-world data analytics projects.
