# Supermarket Sales Data Analysis

## Project Overview
This project analyses supermarket sales data using Microsoft Excel. The purpose of this project is to explore sales performance by city and product category, clean the dataset, calculate descriptive statistics, and identify useful business insights.

## Dataset Description
The dataset contains supermarket transaction records. The main variables include:

- sale_id
- branch
- city
- customer_type
- product_name
- product_category
- quantity
- total_price

After data cleaning, the dataset contained 239 valid records.

## Data Cleaning
The dataset was cleaned before analysis to improve data quality.

The cleaning process included:

- Checking for missing values
- Removing rows with missing information
- Checking for duplicate rows
- Preparing the dataset for Pivot Table analysis

Missing values were found in some columns, so the incomplete rows were removed. Duplicate rows were checked using Excel's Remove Duplicates function, and no duplicate values were found.

## Descriptive Statistics

Descriptive statistics were used to understand the general characteristics of the dataset.

For quantity, the average number of items sold per transaction was approximately 10.78 items. The minimum quantity was 1 item, while the maximum quantity was 20 items.

For total_price, the average transaction value was approximately 127.04. The minimum transaction value was 2.18, while the maximum transaction value was 427.14.

## Visualisations

### Total Sales by Product Category

![Total Sales by Product Category](https://raw.githubusercontent.com/USERNAME/REPOSITORY/main/Total%20sale%20by%20Product%20Category.png)

### Total Sales by City

![Total Sales by City](https://raw.githubusercontent.com/USERNAME/REPOSITORY/main/Total%20Sales%20by%20City.png)

## Key Insights

### Insight 1: Sales by Product Category
Fruits generated the highest total sales among all product categories, with total sales of 7,450.12. This shows that fruit products had strong customer demand and contributed significantly to supermarket revenue.

Personal Care recorded the lowest total sales, with total sales of 4,509.59. This suggests that the supermarket may need to improve promotion or product placement for this category.

### Insight 2: Sales by City
Chicago recorded the highest total sales, with total sales of 10,813.94. This indicates that Chicago was the strongest-performing city in the dataset.

Los Angeles generated the lowest total sales, with total sales of 8,935.31. This may suggest an opportunity to improve sales strategies and customer engagement in this location.

## Tools Used
- Microsoft Excel
- Data Analysis ToolPak
- Pivot Tables
- Excel Charts

## Conclusion
This analysis helped identify important sales patterns in the supermarket dataset. The results show that Fruits was the best-performing product category, while Chicago was the strongest-performing city. These findings can support better business decisions related to inventory planning, marketing, and sales strategy.
