# ShopNest Power BI Project

This repository contains the dataset and problem statements for the ShopNest (Nexusgoods) analytics project.  
The objective is to build a complete Power BI dashboard that provides insights into sales, customer behavior, product performance, and order delivery patterns.

The dataset consists of nine CSV files covering customers, orders, products, payments, sellers, reviews, and geolocation details.  
These datasets will later be cleaned, transformed, and modeled inside Power BI

## 📊 Dataset Description

The dataset used in this project is stored in the `raw_data/` folder and is derived from the Nexusgoods (ShopNest) ecommerce store.

It contains the following CSV files:

- **orders_dataset.csv** – Order-level details including purchase date, approved date, delivery dates, and order status.
- **order_items_dataset.csv** – Items within each order, including product IDs, seller IDs, shipping cost, and item price.
- **order_payments_dataset.csv** – Payment methods and payment installment information.
- **order_reviews_dataset.csv** – Customer reviews, ratings, and review timestamps.
- **customers_dataset.csv** – Customer locations and unique customer IDs.
- **sellers_dataset.csv** – Seller information including location.
- **products_dataset.csv** – Product details such as category, weight, dimensions, etc.
- **geolocation_dataset.csv** – Geolocation coordinates mapped to ZIP codes.
- **product_category_name_translation.csv** – Mapping of Portuguese category names to English.

These files will be merged together inside Power BI to build a relational data model that supports all 8 problem statements.

## 🎯 Problem Statements

This project focuses on solving the following 8 analytical problems using Power BI:

1. **Top Categories by Total Sales**  
   Identify and visualize the top 10 product categories based on total sales.

2. **Delayed Orders Analysis**  
   Determine the number of delayed orders in each category.  
   (An order is delayed if actual_delivery_date > estimated_delivery_date.)

3. **Monthly Delayed vs On-Time Orders Comparison**  
   Create visuals comparing delayed and on-time deliveries monthly, including drillthrough analysis.

4. **Payment Method Analysis**  
   Analyze which payment methods customers use the most.
---------------------------------------------------------------------------------------------------
5. **Product Rating Analysis**  
   Identify the top 10 highest-rated and bottom 10 lowest-rated products.

6. **State-wise Sales Analysis**  
   Visualize sales distribution across different states/regions.

7. **Seasonal (Quarterly) Sales Patterns**  
   Identify quarterly sales trends and seasonal variations.

8. **Revenue Analysis (Yearly Trends)**  
   Evaluate total revenue generated and how it changes year over year.

These insights will be represented using bar charts, line charts, maps.

## 📁 Repository Structure

The project is organized as follows:

shopnest-powerbi/
│
├── raw_data/                  # Original CSV files (uploaded dataset)
├── docs/                      # Documentation (problem statement included)
│   └── problem_statement.md
├── pbit/                      # Power BI template files 
├── README.md                  # Main project documentation



