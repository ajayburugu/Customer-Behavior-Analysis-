
🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior.
The goal is to simulate a real-world, end-to-end data analytics workflow and deliver actionable business insights using Python, SQL, and Power BI.

📊 Total Records: 3,900 purchases
📁 Domain: Retail / E-commerce Analytics

🎯 Objectives

Understand customer demographics and purchasing behavior

Identify high-value customers and loyal segments

Analyze the impact of discounts and subscriptions on revenue

Highlight top-performing products and categories

Present insights through an interactive Power BI dashboard

🗂️ Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer Info: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Amount, Season, Size, Color

Behavioral Data: Discounts, Promo Codes, Previous Purchases, Purchase Frequency

Feedback & Logistics: Review Rating, Shipping Type

🔍 Data Quality:

37 missing values in the review_rating column, handled during preprocessing

🧰 Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn

SQL: PostgreSQL (business analysis queries)

BI Tool: Power BI

Database: PostgreSQL

Version Control: Git & GitHub

🔍 Exploratory Data Analysis (Python)

Key steps performed:

Data loading and inspection (info(), describe())

Missing value treatment using median imputation by product category

Column standardization (snake_case naming)

Feature engineering:

age_group

purchase_frequency_days

Removed redundant columns after validation

Loaded cleaned data into PostgreSQL for SQL analysis

🧮 Data Analysis (SQL)

Business questions answered using SQL:

Revenue comparison by gender

High-spending customers using discounts

Top 5 highest-rated products

Average spend by shipping type

Subscriber vs non-subscriber revenue analysis

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Relationship between repeat purchases and subscriptions

Revenue contribution by age group

📊 Power BI Dashboard

An interactive dashboard was created to visualize:

Revenue trends

Customer segments

Product performance

Subscription impact

Shipping and discount behavior

📌 Outcome: Enables stakeholders to make data-driven marketing and product decisions.

💡 Business Recommendations

Introduce stronger subscription incentives

Implement customer loyalty programs

Optimize discount strategies to protect margins

Promote top-rated and best-selling products

Target marketing campaigns toward high-revenue age groups

📁 Project Structure
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer Shopping Behavior Analysis.pdf
├── README.md


👤 Author

Ajay Burugu
Aspiring Data Analyst | Python • SQL • Power BI

📌 This project is part of my data analytics portfolio.
