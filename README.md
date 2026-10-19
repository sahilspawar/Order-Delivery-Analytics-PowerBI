
# Order Delivery Analytics Dashboard | Power BI

## Project Overview

Order Delivery Analytics is an interactive Power BI project designed to analyze order revenue, customer activity, payment methods, city-level performance, and delivery operations.

The dashboard provides three views of the business: Executive Overview, Delivery Operations, and Customer & Order Analysis. It helps explore operational patterns and sales performance through interactive charts, KPI cards, and filters.

## Project Objectives

- Analyze revenue and order performance.
- Understand customer and payment-method patterns.
- Compare revenue and order activity across cities and food items.
- Explore delivery time in relation to traffic and distance.
- Examine delivery vehicles and driver availability.
- Monitor order status and cancellations.
- Present business metrics through interactive dashboards.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- CSV Dataset
- Data Cleaning and Transformation
- Data Visualization
- GitHub

## Dataset Information

The project uses an order-delivery dataset sourced from Kaggle.

The dataset supports analysis of order details, revenue, customer activity, food items, payment methods, cities, delivery time, traffic conditions, and delivery operations.

Original dataset URL: To be added after verification  
Dataset license: To be verified on the original Kaggle page.

The raw dataset is not included in this repository unless redistribution permission has been verified.

## Data Cleaning and Preparation

Power Query was used to prepare the data for dashboard development.

The preparation process should document the actual steps performed, such as:

- Reviewing column names and data types.
- Checking missing or invalid values.
- Correcting data formats where necessary.
- Reviewing category consistency.
- Preparing fields for KPI calculations and visualizations.
- Checking the transformed data before building the dashboard.

Only the transformations actually performed should be documented.

## Dashboard Pages

### 1. Executive Overview

Provides a high-level view of sales and order performance.

Key metrics:
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Average Delivery Time

Visualizations:
- Payment Method Distribution
- Revenue by Item
- Order Status Distribution
- Orders by City
- Monthly Revenue Trend

Filters:
- City
- Order Status
- Payment Method
- Traffic Level

### 2. Delivery Operations

Focuses on delivery performance and operational factors.

Key metrics:
- Average Delivery Time
- Average Distance
- Delivery Orders
- Cancellation Rate

Visualizations:
- Traffic vs. Delivery Time
- Distance vs. Delivery Time
- Time and Traffic Analysis
- Vehicle Performance
- Driver Availability

Filters:
- Traffic Level
- Delivery Speed
- Driver Vehicle

### 3. Customer & Order Analysis

Explores customer activity, food-item performance, and order patterns.

Key metrics:
- Total Customers
- Total Orders
- Average Order Value
- Average Quantity

Visualizations:
- Top 10 Items by Revenue
- Top Cities by Revenue
- Payment Method Revenue
- Orders by Hour
- Orders by Month

Filters:
- Item Name
- City
- Month

## Business Questions

- Which cities generate the most revenue?
- Which food items contribute the most revenue?
- How are orders distributed across payment methods?
- What is the distribution of delivered, cancelled, and in-transit orders?
- How does delivery time vary with traffic conditions?
- How does delivery distance relate to delivery time?
- Which vehicle types are represented in delivery operations?
- At what times of day does order activity change?
- How do order volumes and revenue vary by month?

## Key Insights

The dashboard is designed to explore sales performance, city and item comparisons, payment preferences, delivery operations, and order timing.

Specific business findings should be added after verifying the underlying measures and chart results. Visual patterns alone do not establish causation.

## Repository Structure

- `dashboard/` — Power BI dashboard file.
- `screenshots/` — Previews of all three dashboard pages.
- `data/` — Dataset source and access documentation.
- `README.md` — Project documentation.

## Limitations

- Results depend on the quality and coverage of the source data.
- Delivery-time patterns do not independently prove that traffic or distance caused a delay.
- Revenue, order counts, and delivery counts depend on their respective calculation definitions.
- Dataset redistribution is subject to the original source's license.

## Conclusion

This project demonstrates practical skills in data preparation, Power Query, Power BI dashboard development, KPI reporting, data visualization, and operational analysis.

It is part of my portfolio as an aspiring Data Analyst.

## Author

Sahil Pawar

GitHub: https://github.com/sahilspawar
