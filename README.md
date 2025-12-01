# Nike-Product-Insights-Dashboard-SQL-Power-BI-

## Project Overview
This project analyzes Nike’s discounted product listings to understand pricing behavior, discount performance, and promotional strategy.
The goal is to help an e-commerce client optimize discounts, identify high-performing products, and improve promo campaigns using data-driven insights.

Tools used: MySQL for data analysis and Power BI for dashboard visualization.
## Dataset Description
The dataset is a JSON file containing product-level data from Nike’s sale page.

Key fields include:

title – Product name

subtitle – Product description

current_price

original_price

discount_percent

promo_message

product_type

created_at (timestamp)

image_url

product_url

The dataset contains pricing, discount, and promotion details for multiple products.

## Project Process
Collection of the dataset
Convert json to csv
import the dataset to mysql
Cleaan the dataset
Analyze the data
Import the analyze dataset into powerbi
Visualize the result
report 
## Database & ETL (MySQL)
## Key Questions
What is the average discount percentage across all products?
Which product has the highest discount?
How many products are discounted vs full price?
Which product categories appear most frequently?
What promo types are the most common?
Does promo type (e.g., BFRIDAY) affect discount %?
Which product groups show the highest price variability?
How many products have active promo messages?
What is the minimum, maximum, and average current price?
What is the price difference between original and discounted prices?

## SQL Queries
## Power BI Dashboard
## Key Insights

## Recommendations
## Tools Used
MySQL
Power BI
Python (if used)
Excel/Notepad for cleanup
GitHub for documentation
## How to Reproduce
Clone this repository
Import products.json into MySQL
Run the SQL scripts in /sql folder
Open dashboard.pbix in Power BI

