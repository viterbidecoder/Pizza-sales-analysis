# Pizza-sales-analysis
# Real-Time Pizza Sales Analysis Using MySQL and Power BI

This project implements an end-to-end data analytics solution to analyze pizza sales data and extract actionable business insights. The solution emphasizes relational database design, ER modeling, data cleaning, SQL-based analysis, and interactive dashboard development using Power BI.


## Project Overview

The objective of this project was to analyze transactional pizza sales data for the year 2015 and derive insights related to revenue performance, order patterns, product demand, and temporal sales trends.

The workflow begins with structured data modeling and ingestion into MySQL, followed by data cleaning, transformation, and analytical querying. The processed data is then visualized using Power BI dashboards to enable intuitive exploration of key business metrics.


## Data Engineering and Database Design

- Designed an **Entity–Relationship (ER) model** to represent core business entities such as orders, order details, pizzas, pizza categories, and pricing.
- Converted the ER model into a normalized relational schema.
- Imported raw sales data into MySQL and validated schema consistency.
- Applied normalization principles to reduce redundancy and improve data integrity.
- Defined primary and foreign key relationships to enforce referential integrity.
- Performed data cleaning to:
  - Handle missing and inconsistent values
  - Standardize date, quantity, and pricing formats
  - Validate transactional records before analysis


## SQL Analysis and Data Processing

- Used MySQL for ETL and analytical processing.
- Implemented optimized SQL queries involving:
  - Multi-table JOINs across normalized tables
  - Aggregate functions such as SUM, COUNT, and AVG
  - GROUP BY and HAVING clauses
  - Date-based filtering for time-series analysis
- Derived key business metrics including:
  - Total revenue
  - Total number of orders
  - Total pizzas sold
  - Average order value
  - Average pizzas per order
- Identified:
  - Top 5 and bottom 5 pizzas by revenue
  - Top 5 and bottom 5 pizzas by quantity sold
  - Top 5 and bottom 5 pizzas by total orders
  - Busiest days of the week and peak sales months


## Data Visualization and Dashboards

Power BI was used to build interactive dashboards connected directly to the MySQL database. The dashboards support dynamic filtering by date and pizza category and allow drill-down analysis for detailed insights.

### Sales Overview Dashboard

This dashboard provides a high-level view of overall business performance and sales distribution.

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/e5ef4514-56a7-403b-913d-6dfd32937a65" />

Displayed metrics and insights:
- Total revenue, total orders, and total pizzas sold
- Day-wise and month-wise order trends
- Sales distribution by pizza category and size
- Identification of busiest days and months


### Best and Worst Sellers Dashboard

This dashboard focuses on product-level performance to identify high-performing and underperforming pizzas.

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/59f8cce5-48d0-4e8e-aa06-1cec6b236830" />

Displayed insights:
- Top and bottom pizzas by revenue
- Top and bottom pizzas by quantity sold
- Top and bottom pizzas by total orders
- Clear differentiation between best-selling and least-performing items


## Tools and Technologies

- **MySQL**
  - ER modeling and relational schema design
  - Data cleaning and transformation
  - Analytical SQL queries

- **Power BI**
  - Data modeling
  - Interactive dashboards
  - KPI and trend visualization

- **Excel**
  - Initial data exploration and validation
