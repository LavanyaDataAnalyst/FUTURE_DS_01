# 📊Business Sales Performance Analysis

## ℹ️ Description:
* Data Cleaning, Transformation, and Visualization project using Excel and Power BI to analyze sales, profit, and discount impact across regions and product categories.

## 📖 Table of Contents: 

>* Project Overview
>* Dataset Description
>* Tools & Technologies
>* Data Cleaning & Preparation
>* Exploratory Data Analysis (EDA)
>* Key Insights
>* Recommendations
>* How to Use


## 📘 Project Overview

* This project focuses on analyzing business sales data to understand overall performance across different categories, regions, and time periods.
* The analysis highlights key metrics such as sales, profit, and discount patterns to derive meaningful business insights.
* The dashboard provides a clear view of how different factors influence revenue and profitability.


## 📁 Dataset Description

The dataset contains 
>* customer details, product information, order details, sales, profit, and discount.
>* It was structured into three main tables: Customer_Dim, Product_Dim, and Orders_Fact.


## 🛠️ Tools & Technologies

**Excel**

> Data cleaning | Sorting and filtering | 

**Power Query**

> Data transformation | Data formatting |

**Power BI**

> Data modeling | Dashboard creation | Visualization |

**DAX (Data Analysis Expressions)**

> Creating measures | Calculations and aggregated metrics |
  
 
## 🧹 Data Cleaning & Preparation - Excel
* Data cleaning and transformation were performed in Excel to ensure data quality and consistency.
* Trimming and cleaning techniques were applied to remove unnecessary spaces and errors.
* The dataset was structured by splitting it into three tables: Customer_Dim, Product_Dim, and Orders_Fact to support efficient data modeling.
* Product names were standardized into shorter and more readable formats.
* Date formats were corrected for consistency, and Product ID was refined as a unique identifier to eliminate duplicates.
* Additionally, overall duplicate records were removed to maintain data accuracy.

## 📦 Data Modeling & Visualization - PowerBI
* Data modeling was implemented in Power BI by establishing relationships between the tables.
* A new column, Discount Status, was created in the Orders_Fact table to classify transactions as “No Discount” or “Discount Applied”.
* Multiple analytical tables were generated, including city-wise, state-wise, region-wise, segment-wise, and no-discount sales to enable detailed analysis.
* DAX measures were created to calculate key metrics, and interactive dashboards were developed using cards, charts, and slicers to provide dynamic and insightful visualizations.

## 📊 Exploratory Data Analysis (EDA)
* Sales and profit show variation across categories, with high sales not always resulting in high profit.
* Discounts are widely applied and have a noticeable negative impact on profitability.
* Technology category generates the highest revenue, while some sub-categories show low or negative profit.
* Sales performance varies across regions, states, and customer segments.
* Time-based analysis shows steady growth in sales, especially in later years.
* No-discount sales highlight the true performance of products without promotional impact.

![Dashboard](Dashboard - BSPA.png)

## 🔍 Key Insights

* Some categories generate high sales but lower profit, indicating margin issues.
* Higher discounts do not always increase profitability and may reduce profit.
* Sales show growth over time, while profit varies based on discount strategies.
* No-discount sales provide a clearer view of baseline performance.
  
## 💡 Recommendations

* Focus on high-profit categories to improve overall business performance.
* Control discount strategies to protect profit margins.
* Monitor categories with high sales but low profit for improvement.
* Use data-driven insights for better decision-making and business growth.


## ▶️ How to Use

* Open the Power BI file in Power BI Desktop.

* Use slicers to filter data by region, category, or segment.

* Explore different visuals such as bar charts, line charts, and funnel charts to analyze sales, profit, and discount impact.

* Interact with the dashboard to gain insights into business performance.

  
## 👩‍💻 Author
 > Lavanya Madhan Raj

