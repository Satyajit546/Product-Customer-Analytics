# Product & Customer-Analytics(Python+Sql+Power BI)

# Project Overview

This project presents a comprehensive end-to-end analysis of sales data, focusing on Product Performance and Customer Segmentation. The goal is to transform raw transactional data into actionable business intelligence using a robust stack of data analysis tools, including SQL for foundational metrics, Python for advanced statistical modeling (RFM Clustering), and Power BI for dynamic data visualization.

# Key Objectives

* Product Performance Assessment: Identify top-selling products, measure regional sales distribution, and analyze key performance indicators (KPIs) like average order value and sales quantity.

* Customer Segmentation: Apply the RFM (Recency, Frequency, Monetary) methodology paired with K-Means clustering to segment the customer base into distinct, actionable groups (e.g., Champions, Loyal Customers, At Risk).

* Business Intelligence Reporting: Create an interactive dashboard to visualize trends, segment performance, and provide a single source of truth for business decision-makers.

Product Analysis SQL Queries.pdf

Documentation containing the core SQL scripts used for data extraction and initial aggregation.

Foundational Metrics & CLV. Queries cover product sales aggregation, regional performance, and the calculation of Customer Lifetime Value (CLV).

SQL

Product_Analytics.ipynb

A Jupyter Notebook detailing the advanced analytical modeling process.

Customer Segmentation (RFM & K-Means). This includes data cleaning, RFM feature engineering, scaling, determining the optimal number of clusters (Elbow Method), K-Means clustering, and final segment mapping (e.g., "Champions," "Loyal").

Python (Pandas, Scikit-learn, Matplotlib)

Product Analytics.pbix

The final interactive dashboard file.

Data Visualization & Reporting. The dashboard integrates the SQL-derived product metrics and the Python-derived customer segments into a visually compelling and interactive format for executive review.

Power BI


# Technology Stack

* Database: SQL (used for querying and pre-aggregation)

* Modeling & Analysis: Python

  *pandas: Data manipulation and cleaning

   *scikit-learn: K-Means Clustering for segmentation

  *matplotlib / seaborn: Data visualization for the notebook

  *Prophet: (Indicated in imports) For potential future time-series forecasting.

*Business Intelligence (BI): Power BI (for dashboard creation and visual reporting)

# Analysis Highlights

# Customer Segmentation

*The core of the customer analysis is built on RFM principles:

*Recency: How recently a customer made a purchase.

*Frequency: How often a customer purchases.

*Monetary: How much a customer has spent in total.

*K-Means clustering was applied to the scaled RFM scores to objectively group customers, resulting in segments that allow the marketing team to tailor strategies, from retention campaigns for "At Risk" customers to loyalty programs for "Champions."

# Product Insights

*The SQL analysis provides clear metrics on:

*Regional Performance: Identifying which product categories dominate sales in specific geographical regions.

*CLV: Calculating the estimated revenue a customer will generate over their relationship with the company, aiding in resource allocation.

*Top/Bottom Performers: Fast identification of the most and least profitable products and product categories.
