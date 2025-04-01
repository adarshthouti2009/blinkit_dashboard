# Blinkit Analytics Dashboard

## 1. Requirement Gathering / Business Requirement

The goal of this project is to conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution. The insights derived from the dashboard will help in optimizing business strategies using various KPIs and visualizations in Power BI.

## 2. Data Walkthrough

  * Understanding the structure, sources, and integrity of the Blinkit sales data.
  * Identifying key tables, fields, and relationships relevant to the analysis.
  * Reviewing historical data trends and missing values.

## 3. Data Connection

  * Establishing connections to Blinkit's data sources (SQL databases, Excel files, APIs, or cloud storage).
  * Integrating real-time or batch data pipelines for continuous data refresh in Power BI.

## 4. Data Cleaning / Quality Check

  * Handling missing, duplicate, or inconsistent data.
  * Standardizing column formats (dates, numbers, text categories).
  * Validating data accuracy to ensure reliable insights.

### 5. Data Modeling

  * Creating relationships between sales, customer, inventory, and outlet data tables.
  * Designing a star schema with a fact table (Sales) and multiple dimension tables (Items, Customers, Outlets, etc.).

### 6. Data Processing

  * Implementing transformations (aggregations, data type conversions, derived columns).
  * Applying business rules and logic to enrich data.

### 7. DAX Calculations

  * Developing calculated measures and columns for KPIs:
  * Total Sales: SUM(Sales[Revenue])
  * Average Sales: AVERAGE(Sales[Revenue])
  * Number of Items Sold: COUNT(Sales[Item_ID])
  * Average Rating: AVERAGE(Sales[Customer_Rating])

### 8. Dashboard Layout Design

  * Structuring the dashboard for intuitive navigation.
  * Using a clean and professional layout with consistent color schemes.
  * Implementing interactive filters and slicers.

### 9. Charts Development and Formatting

#### Charts & Objectives:

a. Total Sales by Fat Content

   * Objective: Analyze the impact of fat content on total sales.
   * Chart Type: Donut Chart
   * Additional KPIs: Average Sales, Number of Items, Average Ratings

b. Total Sales by Item Type

  * Objective: Identify the performance of different item types in terms of total sales.
  * Chart Type: Bar Chart
  * Additional KPIs: Average Sales, Number of Items, Average Ratings

c. Fat Content by Outlet for Total Sales

  * Objective: Compare total sales across different outlets segmented by fat content.
  * Chart Type: Stacked Column Chart
  * Additional KPIs: Average Sales, Number of Items, Average Ratings

d. Total Sales by Outlet Establishment

  * Objective: Evaluate how the age or type of outlet establishment influences total sales.
  * Chart Type: Line Chart

e. Sales by Outlet Size

  * Objective: Analyze the correlation between outlet size and total sales.
  * Chart Type: Donut/Pie Chart

f. Sales by Outlet Location

   * Objective: Assess the geographic distribution of sales across different locations.
   * Chart Type: Funnel Map

g. All Metrics by Outlet Type

   * Objective: Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, Average Rating) broken down by different outlet types.
   * Chart Type: Matrix Card

### 10. Dashboard / Report Development

  * Assembling all charts, filters, and KPIs into an interactive Power BI dashboard.
  * Ensuring responsiveness and dynamic filtering capabilities.
  * Testing for performance and usability.

### 11. Insights Generation

  * Identifying trends, patterns, and outliers in sales performance.
  * Recognizing top-performing items, outlet types, and locations.
  * Recommending data-driven strategies to improve sales, customer satisfaction, and inventory distribution.

## Conclusion

This structured approach will ensure the development of a powerful, interactive, and insightful Blinkit Sales Analytics Dashboard in Power BI that supports data-driven decision-making for business optimization.
