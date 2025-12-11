# Customer_Behavior_Analysis
Data analytics project showcasing customer behavior using python, mysql and power Bi

This project analyzes the shopping behavior of 3,900 customers to uncover insights about spending patterns, product preferences, customer segments, and subscription behavior.
The workflow includes Python-based EDA, data cleaning, SQL analysis, and building an interactive Power BI dashboard to present business insights.

Dataset

Rows: 3,900
Columns: 18

Key Features

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item purchased, Category, Price, Season, Size, Color

Behavioral Attributes: Discount applied, Promo code usage, Shipping type, Previous purchases

Review Rating: Contains 37 missing values (handled during cleaning)

Tools & Technologies

Python → pandas, numpy, matplotlib/seaborn

Jupyter Notebook

MySQL Server → SQL queries

Power BI → Dashboard & visualizations

GitHub → Version control

 Steps Performed
1. Data Loading & Initial Exploration (Python)

Loaded dataset using pandas

Checked data structure with df.info() and summary statistics with df.describe()

Identified missing values and inconsistencies

2. Data Cleaning

Filled missing review ratings using median rating per product category

Standardized column names to snake_case

Dropped redundant columns such as promo_code_used

Created new features:

age_group (binned ages)

purchase_frequency_days

3. SQL Analysis (MySQL)

Imported the cleaned dataset into MySQL for structured analysis.
Key queries performed:

Revenue contribution by gender

Top 5 products by average rating

Comparison of standard vs. express shipping revenue

Spending behavior of subscribers vs. non-subscribers

Customer segmentation: New, Returning, and Loyal

Product-wise discount dependency

Repeat buyer patterns and subscription conversion

4. Power BI Dashboard

Built an interactive dashboard showcasing:

Revenue by category, gender, and subscription

Customer segment distribution

Discount impact on sales

Top-rated and top-selling products

Shipping type comparison
The dashboard helps stakeholders make quick business decisions.
