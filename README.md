# SWYNEX - Exploratory Data Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a cleaned Cafe Sales dataset.

The analysis was performed using Microsoft Excel to identify key sales trends, product performance, customer transaction patterns, and potential anomalies.

## Objectives

- Analyze overall sales performance
- Identify top-performing products
- Analyze monthly sales trends
- Analyze payment method and location performance
- Calculate important statistical measures
- Identify potential anomalies
- Generate meaningful business insights

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Excel Formulas
- Data Cleaning
- Statistical Analysis
- Data Visualization

## Dataset

The cleaned dataset was prepared as part of Task 1 of the SWYNEX internship.

Dataset: `cleaned_cafe_sales.csv`

The dataset contains transaction-level cafe sales information including:

- Transaction ID
- Item
- Quantity
- Price per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

## Analysis Performed

### 1. KPI Analysis

Key metrics calculated:

- Total Sales: ₹88,952
- Total Transactions: 10,000
- Total Quantity Sold: 28,834
- Average Transaction Value: ₹8.93
- Average Unit Price: ₹2.95
- Maximum Transaction Value: ₹25
- Minimum Transaction Value: ₹1
- Number of Products: 8

### 2. Product Analysis

Product-level analysis was performed to compare:

- Total Sales
- Quantity Sold
- Product performance

Salad generated the highest revenue, while Juice had the highest quantity sold.

### 3. Monthly Sales Analysis

Monthly sales were analyzed for 2023 to identify sales trends and fluctuations.

June recorded the highest monthly sales at ₹7,350, while February recorded the lowest at ₹6,633.50.

### 4. Payment Method Analysis

Transaction counts were analyzed across available payment methods to understand customer payment preferences.

### 5. Location Analysis

Sales performance was compared between In-store and Takeaway transactions.

### 6. Anomaly Analysis

An IQR-based method was used to identify potential high-value transaction anomalies.

No potential high-value anomalies were identified using the selected IQR threshold.

## Key Insights

1. Salad was the highest revenue-generating product with sales of ₹17,320.
2. Juice had the highest quantity sold with 3,373 units.
3. Monthly sales remained relatively stable throughout 2023.
4. June recorded the highest monthly sales.
5. In-store and Takeaway sales showed relatively similar performance.
6. The average transaction value was approximately ₹8.93.
7. No potential high-value anomalies were identified using the IQR-based method.

## Business Recommendations

- Focus on high-revenue products such as Salad.
- Investigate the difference between product sales volume and revenue.
- Continue supporting popular digital payment methods.
- Improve the collection of missing customer transaction information.
- Monitor monthly sales trends for future growth opportunities.

## Project Files

- `Data/cleaned_cafe_sales.csv` - Cleaned dataset
- `Analysis/SWYNEX-Cafe-Sales-EDA.xlsx` - Excel EDA analysis
- `Screenshots/` - KPI, Charts and Insights screenshots

## Conclusion

The analysis provided useful insights into cafe sales performance, product demand, monthly trends, payment methods, location performance, and potential anomalies.

The project demonstrates practical skills in Excel-based data analysis, PivotTables, data visualization, statistical analysis, and business insight generation.
