# 📊 CRM Analytics: Unlocking Customer Insights with Data

## Overview
This notebook provides a comprehensive analysis of customer purchasing behavior using CRM Analytics. 
By leveraging Exploratory Data Analysis (EDA), RFM segmentation, Cohort analysis, Customer Lifetime Value (CLV) estimation, and visualization techniques, we uncover valuable insights to optimize business strategies.

## Dataset: E-Commerce Transactions
We utilize real-world e-commerce transaction data sourced from the UCI Machine Learning Repository. 
This dataset includes actual transactions from a UK-based online retailer between December 2010 and December 2011, primarily selling unique gift items.

### Dataset Features

- **InvoiceNo:** Unique transaction identifier (cancellations marked with 'C').
- **StockCode:** Unique product identifier.
- **Description:** Name of the product.
- **Quantity:** Number of items purchased per transaction.
- **InvoiceDate:** Timestamp of the transaction.
- **UnitPrice:** Price per unit of the product.
- **CustomerID:** Unique customer identifier.
- **Country:** Country of the customer.

## What This Notebook Analyzes
This notebook provides a deep-dive analysis of customer behavior through multiple analytical techniques:

### 1️⃣ Exploratory Data Analysis (EDA)
- Detecting missing values and data inconsistencies
- Understanding sales trends and distributions
- Analyzing top-selling products and revenue drivers

### 2️⃣ RFM Analysis (Recency, Frequency, Monetary Value)
- Segmenting customers based on their purchasing behavior
- Identifying high-value and at-risk customers
- Visualizing customer groups using treemaps and bar plots

 ### 3️⃣ Cohort Analysis for Customer Retention
- Tracking user retention trends over time
- Understanding customer lifecycle and repeat purchase patterns
  
### 4️⃣ Customer Segmentation & Visualization
- Segmenting customers based on purchasing habits
- Visualizing distribution using histograms, box plots, and treemaps

### 5️⃣ Customer Lifetime Value (CLV) Estimation
- Predicting future revenue per customer
- Estimating CLV using the Beta Geometric / Negative Binomial Distribution (BG/NBD) model

## Visualization Techniques Used
We use various data visualization techniques to enhance our insights:
- **Treemaps:** For hierarchical customer segmentation.
- **Bar Plots:** To analyze purchase frequency and revenue distribution.
- **Histograms:** To understand spending behavior.
- **Box Plots:** To detect outliers in purchasing trends.

## Why This Analysis Matters
Understanding customer behavior is critical for business growth. By leveraging CRM analytics, businesses can:
- **Improve marketing strategies** by targeting the right customers.
- **Enhance customer retention** through personalized engagement.
- **Maximize revenue** by focusing on high-value customers.

## Data Source & Acknowledgements

This dataset was provided by Dr. Daqing Chen, Director of Public Analytics Group at London South Bank University via the UCI Machine Learning Repository. 
Special thanks to the contributors for making real-world transaction data available for analysis.
