
📌 Project Overview

This project demonstrates a complete data analytics workflow, starting from raw customer transaction data to business-ready insights and interactive visualization. The objective is to analyze customer shopping behavior, spending patterns, product performance, and subscription trends using industry-standard tools.

The project integrates Python (Pandas) for data cleaning and feature engineering, PostgreSQL (SQL) for analytical querying, and Power BI for dashboarding and insight communication.

🧾 Dataset Summary

Records: 3,900 customers

Features: 18 columns

Domain: Retail / Customer Behavior Analytics

Includes customer demographics, purchase details, discounts, reviews, subscriptions, and purchase frequency.

🧹 Data Cleaning & Feature Engineering (Python)

Data inspection using head(), info(), and describe()

Handled missing values in review ratings using category-wise median imputation

Standardized column names to snake_case

Removed redundant columns after data validation

Engineered new features:

age_group (Young Adult, Adult, Middle-Aged, Senior)

purchase_frequency_of_days (mapped from categorical frequency)

Final dataset validated with zero missing values

Loaded cleaned data into PostgreSQL using SQLAlchemy

🗄️ SQL Analysis (PostgreSQL)

Answered key business questions using SQL:

Revenue contribution by gender

High-spending customers despite discounts

Top-rated and most-purchased products

Discount effectiveness across products

Customer segmentation (New, Returning, Loyal)

Subscription behavior of repeat buyers

Revenue and sales analysis by age group and category

Used aggregations, subqueries, CTEs, CASE statements, and window functions for analysis.

📈 Power BI Dashboard

Built an interactive Customer Behavior Dashboard featuring:

KPI cards (Total Customers, Avg Rating, Avg Purchase Amount)

Revenue & sales by category

Revenue & sales by age group

Subscription distribution

Slicers for gender, category, shipping type, and subscription status

The dashboard enables dynamic, data-driven decision-making.

🔍 Key Insights

Clothing is the highest revenue-generating category

Loyal customers form the majority of the customer base

Certain products are highly discount-driven

Subscribers and non-subscribers show similar average spending

Younger age groups contribute the most to revenue

🛠️ Tools & Technologies

Python: Pandas

Database: PostgreSQL

Visualization: Power BI

Libraries: SQLAlchemy, psycopg2
