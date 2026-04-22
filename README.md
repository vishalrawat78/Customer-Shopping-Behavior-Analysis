# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using Python, SQL, and Power BI. The goal is to clean and explore retail customer data, answer business questions using SQL, and build an interactive dashboard for insights and decision-making.

## Objectives
- Perform data cleaning and transformation using Python
- Load the prepared data into a SQL database
- Write SQL queries to answer business questions
- Build a Power BI dashboard for visual analysis
- Present insights in report and presentation format

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- SQL
- Power BI
- CSV Dataset

## Dataset
The dataset used in this project contains customer shopping behavior information such as:
- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Payment Method
- Frequency of Purchases

File: `customer_shopping_behavior.csv`

## Project Workflow

### 1. Data Analysis with Python
The notebook `Customer_Shopping_Behavior_Analysis.ipynb` is used for:
- Loading the dataset
- Exploring the data
- Handling missing values
- Renaming columns
- Creating new derived columns such as `age_group`
- Transforming purchase frequency into days
- Preparing the data for SQL and dashboard analysis

### 2. SQL Analysis
The file `customer_behavior_sql_queries.sql` contains business queries such as:
- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Average purchase amount by shipping type
- Revenue comparison by subscription status
- Discount usage by product
- Customer segmentation by previous purchases
- Top products by category
- Repeat buyer subscription behavior
- Revenue contribution by age group

### 3. Dashboard in Power BI
The file `customer_behavior_dashboard.pbix` contains the Power BI dashboard built from the processed dataset / SQL outputs. It helps visualize:
- Customer demographics
- Purchase behavior
- Revenue trends
- Product and category performance
- Subscription and discount patterns

## Repository Files
- `Customer_Shopping_Behavior_Analysis.ipynb` – Python notebook for data cleaning and preparation
- `customer_shopping_behavior.csv` – Raw dataset
- `customer_behavior_sql_queries.sql` – SQL queries for business analysis
- `customer_behavior_dashboard.pbix` – Power BI dashboard
- `Customer Shopping Behavior Analysis.pdf` – Project report / documentation
- `Business Problem  Document.pdf` – Business problem statement
- `Customer-Shopping-Behavior-Analysis.pptx` – Project presentation

## How to Use

### Python Notebook
1. Open `Customer_Shopping_Behavior_Analysis.ipynb`
2. Run the notebook step by step
3. Clean and transform the dataset
4. Export or load the processed data into your SQL database

### SQL
1. Create a database in PostgreSQL, MySQL, or SQL Server
2. Load the cleaned dataset into a table named `customer`
3. Run the queries from `customer_behavior_sql_queries.sql`

### Power BI
1. Open `customer_behavior_dashboard.pbix`
2. Connect it to the prepared dataset or SQL database
3. Refresh the visuals if needed

## Key Insights Covered
- Customer spending patterns by gender and age group
- Impact of discounts on purchasing behavior
- Product performance based on review ratings
- Subscription effect on average spend and revenue
- Category-level and product-level buying trends
- Repeat purchase behavior and loyalty patterns

## Business Value
This project demonstrates an end-to-end analytics workflow that can help businesses:
- Understand customer segments better
- Improve product and category strategy
- Analyze the effect of discounts and subscriptions
- Support data-driven marketing and sales decisions

## License
This project is licensed under the MIT License.

## Author
Vishal Rawat

If you like this project, feel free to star the repository and use it as part of your data analytics portfolio.
