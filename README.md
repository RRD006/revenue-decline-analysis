# Revenue Decline Analysis

## Project Overview
This project performs an end-to-end analysis of retail transaction data to understand revenue behavior over time and identify category-level factors influencing revenue fluctuations. The goal is to evaluate whether a revenue decline exists and, if not, to uncover meaningful business insights from sales volume and pricing efficiency.
The analysis is conducted using Python in a Jupyter Notebook, following a structured data analysis workflow similar to real-world business and consulting scenarios.

## Dataset
The dataset contains transaction-level retail sales data with the following key fields:
Transaction ID
Date
Product Category
Quantity Sold
Price per Unit
Total Amount
Time Range: 2023 – early 2024
(Note: Incomplete data for January 2024 was excluded from trend analysis.)

## Tools Used
Python,
Pandas,
Matplotlib,
Jupyter Notebook.

## Analysis Workflow
1. Data Cleaning & Preprocessing
Standardized column names
Converted date fields to datetime format
Created monthly time periods for trend analysis
Checked for missing values and handled partial months
2. Exploratory Data Analysis (EDA)
Monthly revenue aggregation
3-month rolling average to smooth short-term fluctuations
Category-wise revenue and quantity analysis
Revenue-per-unit calculation to assess pricing efficiency
3. Visualization
Monthly revenue trends
Category-wise revenue comparison
Quantity sold by category
Rolling average trend plots

## Key Insights
No consistent long-term revenue decline is observed after applying a 3-month rolling average.
Clothing generates the highest sales volume but has the lowest average revenue per unit.
Beauty products yield the highest revenue per unit despite lower sales volume, indicating premium pricing.
Electronics shows balanced performance across both sales volume and revenue efficiency.
Revenue volatility appears to be driven by category mix and seasonal effects rather than structural decline.

## Business Implications
Improving margins in high-volume categories such as Clothing could significantly impact overall revenue.
High-margin categories like Beauty can be scaled through targeted promotions.
Electronics provides a stable revenue base and can be leveraged for predictable performance.

## Conclusion
This project demonstrates an end-to-end retail revenue analysis using real-world transaction data.
Although no sustained revenue decline was identified, the analysis highlights important trade-offs between sales volume and pricing efficiency across product categories and provides actionable business insights.
