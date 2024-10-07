# E-Commerce-Data-Analysis

## Overview
This project showcases a comprehensive data analysis on an e-commerce dataset sourced from Kaggle, containing transactional records from 2010 and 2011 for a UK-based online retail company. Key objectives include identifying sales trends, understanding customer behavior, and providing actionable insights to optimize revenue generation.

#### Key Features
- Data Cleaning: Efficient handling of missing values, duplicates, and negative quantities.
- Feature Engineering: New columns for enriched analysis.
- Insightful Visualizations: Clear, meaningful charts to highlight key findings.
- Practical Recommendations: Actionable steps to optimize business performance.
  
#### Data Source
The dataset is available on [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

## Project Workflow

### 1. Data Preparation
Handling Missing Values: Dropped rows with missing descriptions, imputed placeholder CustomerID for missing IDs.
Feature Engineering: Created new columns such as TotalPrice (Quantity * UnitPrice) and TransactionType (accounting for returns).

### 2. Exploratory Data Analysis (EDA)
- **Sales Analysis:** Identified top products and trends, with peak sales in November.
- **Customer Analysis:** Identified top customers by spend and frequency.
- **Geographic Analysis:** UK accounted for 90% of sales; notable sales in the Netherlands, EIRE, Germany, France, and Australia.
- **Return Analysis:** High returns on Paper Craft, Little Birdie despite high sales.

### 3. Key Insights
- **Top-selling Products:** Dotcom Postage, Regency Cakestand 3 Tier, Paper Craft, Little Birdie.
- **Sales Trends:** Increasing monthly, with a peak in November.
- **Customer Spend:** Top spenders: 14646, 18102, 17450.
- **Product Returns:** Paper Craft and Little Birdie have the highest returns.
- **Net Revenue:** **£9.7M** after returns.

### 4. Reccommendations
- **Optimize for Holiday Season:** Prepare for peak seasons to maximize revenue.
- **Customer Retention:** Loyalty programs or offer personalized discounts.
- **Expand Global Sales:** Target regions with growing sales outside the UK.
- ***For full insights and visualizations, check out the EDA section in the project!***

## Project Structure
- `Data_Preparation.ipynb`: Data cleaning and feature engineering.
- `Exploratory_Data_Analysis.ipynb`: EDA and visualizations.
- `Insights_and_Recommendations.md`: Summary of insights and recommendations.
- `README.md`: This file.

## Tools Used
- **Pandas:** Data manipulation.
- **Matplotlib:** Visualization.
- **Jupyter Notebook:** Code execution and analysis.

## Future Work
- Implement more advanced techniques such as predictive analytics to forecast future sales.
- Deepen the customer segmentation with RFM analysis for more targeted marketing strategies.
- Explore potential clustering techniques for product grouping based on sales behavior.




