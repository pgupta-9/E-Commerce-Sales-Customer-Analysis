# E-Commerce Sales & Customer Analysis

## Project Overview

This project focuses on analyzing an e-commerce business dataset to understand sales performance, customer behavior, payment preferences, product categories, and regional demand.

The project uses the Brazilian E-Commerce Public Dataset by Olist and combines Python-based data analysis with an interactive Power BI dashboard.

---

## Problem Statement

E-commerce businesses generate a large amount of sales and customer data. Without proper analysis, it can be difficult to identify sales trends, understand customer behavior, evaluate regional performance, and make data-driven business decisions.

The objective of this project is to analyze e-commerce data and generate meaningful business insights using Python, Pandas, data visualization, and Power BI.

---

## Project Objectives

- Analyze overall e-commerce sales performance.
- Understand customer distribution across different states.
- Identify important product categories.
- Analyze payment method preferences.
- Study monthly sales trends.
- Identify data quality issues and prepare the data for analysis.
- Create meaningful visualizations.
- Build an interactive Power BI dashboard.
- Generate business insights and recommendations.

---

## Dataset

The project uses the Brazilian E-Commerce Public Dataset by Olist.

The dataset contains information related to:

- Orders
- Customers
- Order Items
- Payments
- Reviews
- Products
- Sellers

The dataset was downloaded from Kaggle and prepared for analysis.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Git
- GitHub

---

## Data Preparation & Cleaning

The following data preparation activities were performed:

1. Loaded multiple CSV datasets using Pandas.
2. Inspected dataset dimensions and columns.
3. Checked data types.
4. Identified missing values.
5. Checked duplicate records.
6. Converted relevant date columns into datetime format.
7. Replaced missing product categories with "Unknown".
8. Handled missing numerical product attributes using median values.
9. Created delivery-related columns for further analysis.

Exact duplicate records were not found in the analyzed datasets.

---

## Exploratory Data Analysis

The following areas were analyzed:

- Descriptive statistics
- Order status distribution
- Customer state distribution
- Product category distribution
- Monthly sales performance
- Delivery time
- Delivery delay
- Correlation between price and freight value
- Price outliers

The analysis helped identify important patterns and business trends in the e-commerce data.

---

## Data Visualizations

Five main visualizations were created using Python:

1. Monthly Sales Trend
2. Top 10 Product Categories
3. Top 10 Customer States by Orders
4. Payment Method Distribution
5. Customer Review Score Distribution

These visualizations were used to understand sales trends, customer distribution, product information, payment preferences, and customer feedback.

---

## Power BI Dashboard

An interactive Power BI dashboard was created to present the major business metrics and findings.

### Key Performance Indicators

- Total Revenue: Approximately 13.59M
- Total Orders: Approximately 99.44K
- Total Customers: Approximately 96.10K

### Dashboard Visuals

- Monthly Revenue Trend
- Top 10 Product Categories
- Top 10 Customer States
- Payment Method Distribution

### Filters / Slicers

- Order Status
- Customer State
- Product Category

The dashboard provides an interactive way to explore sales and customer-related information.

---

## Key Business Insights

### 1. Overall Sales Performance

The business generated approximately 13.59M in revenue from around 99.44K orders, indicating strong overall sales activity.

### 2. Large Customer Base

The analysis includes approximately 96.10K unique customers, showing that the business has a broad customer base and significant market reach.

### 3. Credit Card is the Dominant Payment Method

Credit card payments represent approximately 78.34% of the payment value, making credit cards the most dominant payment method.

### 4. São Paulo is a Major Customer Market

São Paulo (SP) has the highest customer/order contribution among the displayed states, followed by Rio de Janeiro (RJ) and Minas Gerais (MG).

### 5. Monthly Revenue Fluctuates

The monthly sales trend shows significant variation. Revenue reaches approximately 1.5M around May, while a noticeable decline occurs around September.

---

## Business Recommendations

### Recommendation 1: Strengthen High-Performing Regions

The company should focus marketing campaigns, promotions, and customer-service initiatives on high-performing states such as São Paulo, Rio de Janeiro, and Minas Gerais.

Targeted campaigns can also be used to increase demand in lower-performing regions.

### Recommendation 2: Improve Performance During Low-Sales Months

The company should investigate the reasons for lower revenue during weaker months such as September.

Seasonal discounts, promotional campaigns, targeted digital marketing, and special offers can be introduced to improve sales consistency.

---

## Project Structure

```text
E-Commerce-Sales-Customer-Analysis/
│
├── data/
│   ├── olist_orders_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   ├── product_category_name_translation.csv
│   └── olist_geolocation_dataset.csv
│
├── notebooks/
│   └── E-Commerce_Sales_Customer_Analysis.ipynb
│
├── powerbi/
│
├── visualizations/
│
├── report/
│
├── presentation/
│
└── README.md