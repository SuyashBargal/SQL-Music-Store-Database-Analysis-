# SQL-Music-Store-Database-Analysis

## Overview
This project analyzes customer transactions for an e-commerce store and a music store database using SQL. The dataset consists of customer orders, product details, and order history to extract insights into customer behavior, sales trends, and business performance.

## Database Schemas
The project consists of two database schemas:

### **E-Commerce Database Schema**
1. **customers** - Stores customer information.
2. **products** - Contains product details.
3. **orders** - Stores order records linked to customers.
4. **order_details** - Contains product quantities and prices per order.

### **Music Store Database Schema**
1. **artist** - Stores artist details.
2. **album** - Contains album information linked to artists.
3. **track** - Stores track details including genre, media type, and unit price.
4. **playlist** - Contains playlists created by users.
5. **playlist_track** - Maps tracks to playlists.
6. **customer** - Stores customer data including billing details.
7. **invoice** - Stores customer purchase records.
8. **invoice_line** - Contains invoice details with purchased tracks.
9. **employee** - Stores employee details and hierarchical relationships.

## Key Features
- **Sales Performance Analysis**: Monthly revenue calculation.
- **Customer Segmentation**: Identifies high-value and returning customers.
- **Product Analysis**: Determines top-selling products.
- **Market Basket Analysis**: Finds frequently bought-together items.
- **Customer Churn Analysis**: Detects inactive customers over time.
- **Music Store Analysis**: Evaluates popular tracks, artists, and revenue trends.

## Queries & Insights
- **Total Revenue Per Month**
- **Top-Selling Products**
- **High-Value Customers**
- **Returning vs. New Customers**
- **Product Combination Trends**
- **Customer Churn Rate**
- **Most Purchased Tracks**
- **Top Revenue-Generating Artists**
- **Most Popular Playlists**

## Technologies Used
- **SQL** (MySQL / PostgreSQL)
- **Data Visualization** (Power BI / Tableau for insights)

## Getting Started
1. **Database Setup**
   - Run the provided SQL script to create tables and insert sample data.
2. **Execute Queries**
   - Run the SQL queries to extract insights.
3. **Analyze and Visualize**
   - Use visualization tools to interpret the results.

## Future Enhancements
- Integrate with a business intelligence tool for real-time analytics.
- Optimize queries for faster execution.
- Expand the dataset for more detailed analysis.
- Implement predictive analytics for customer behavior.

## Sample Questions for Analysis
1. What are the total sales per month?
2. Which products are the best sellers?
3. Who are the top 10 highest-spending customers?
4. What percentage of customers return for repeat purchases?
5. What are the most frequently bought-together products?
6. Which tracks generate the most revenue?
7. Who are the top revenue-generating artists?
8. What are the most popular playlists?
9. Which employees handle the most invoices?
10. How does customer spending vary by country?



