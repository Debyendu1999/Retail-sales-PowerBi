# Retail Sales Analysis – Power BI
Retail sales data analysis using Power Bi
## Project Overview

This project analyzes retail sales data using Microsoft Power BI.

The goal of this project is to clean and transform raw retail transaction data, create meaningful business metrics, and build an interactive dashboard to help understand sales performance, customers, products, and revenue trends.

---

## Business Questions

The analysis focuses on questions such as:

* Which products generate the highest revenue?
* Which customers generate the highest revenue?
* Which countries contribute the most to sales?
* How does revenue change over time?
* What are the key sales trends and patterns?

---

## Tools & Technologies

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Visualization

---

## Data Cleaning

The raw dataset contained several data-quality issues.

The following cleaning steps were performed using Power Query:

* Corrected data types
* Removed duplicate records
* Removed transactions with Quantity below 1
* Removed records with invalid Unit Price values
* Created a Revenue column
* Split Date and Time
* Extracted Month and Year
* Handled missing CustomerID values
* Prepared the dataset for analysis

---

## Data Transformation

Power Query was used to transform the raw transaction data into an analysis-ready dataset.

### Main transformations

```text
Raw Data
   ↓
Data Type Correction
   ↓
Duplicate Removal
   ↓
Invalid Quantity Removal
   ↓
Invalid Unit Price Removal
   ↓
Revenue Calculation
   ↓
Date & Time Transformation
   ↓
Month & Year Extraction
   ↓
Analysis-Ready Data
```

---

## Key Metric

Revenue was calculated using:

```text
Revenue = Quantity × Unit Price
```

## Key Insights

The dashboard is used to identify:

* Highest-revenue customers
* Highest-revenue products
* Top-performing countries
* Monthly revenue trends
* Overall sales performance

Detailed business insights are presented in the Power BI dashboard.

## Skills Demonstrated

This project demonstrates practical experience with:

* Power Query
* Data Cleaning
* Data Transformation
* Data Quality Handling
* DAX
* Business Analysis
* Data Visualization
* Power BI Dashboard Development

---

## Conclusion

This project demonstrates the complete process of transforming raw retail transaction data into an analysis-ready dataset and presenting business insights through an interactive Power BI dashboard.
