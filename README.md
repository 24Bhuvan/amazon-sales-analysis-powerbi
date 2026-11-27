# Amazon Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard designed to analyze Amazon sales performance, monitor key business metrics, identify sales trends, and evaluate product performance.

## Dashboard Preview

![Amazon Sales Analysis Dashboard](screenshots/amazon_sales_dashboard.png)

## 1. Project Overview

The objective of this project is to develop an interactive and dynamic sales analysis dashboard that provides a high-level overview of business performance through Key Performance Indicators (KPIs), time-based sales trends, product category analysis, and top-performing products.

**Key Principle:** A good business dashboard should be interactive and dynamic, allowing users to explore data and derive meaningful insights.

## 2. Business Problem

Businesses need to continuously monitor sales performance, understand customer feedback, identify revenue-generating products, and analyze sales patterns over time.

This dashboard addresses these requirements by providing insights into:

- Overall sales performance through YTD and QTD metrics.
- Monthly and weekly sales trends.
- Sales distribution across product categories.
- Top-performing products based on sales.
- Products receiving the highest number of reviews.

## 3. KPI Requirements

The dashboard includes four primary Key Performance Indicators.

| KPI | Description |
|---|---|
| YTD Sales | Total sales generated from the beginning of the year up to the current reporting date. |
| QTD Sales | Total sales generated from the beginning of the current quarter up to the current reporting date. |
| YTD Products Sold | Total number of product units sold from the beginning of the year up to the current reporting date. |
| YTD Reviews | Total product reviews received during the year, helping monitor customer feedback. |

## 4. Dashboard Visualizations

| Visualization | Chart Type | Business Purpose |
|---|---|---|
| YTD Sales by Month | Line Chart | Identify monthly sales trends, seasonal patterns, and growth. |
| Sales by Week | Column Chart | Analyze weekly sales fluctuations and short-term performance. |
| Sales by Product Category | Matrix / Heat Map | Compare sales performance across product categories. |
| Top 5 Products by YTD Sales | Bar Chart | Identify the leading revenue-generating products. |
| Top 5 Products by YTD Reviews | Bar Chart | Identify products receiving the highest number of reviews. |

## 5. Interactive Functionalities

The dashboard incorporates interactive elements to support dynamic data exploration.

- Quarter slicer.
- Product Category slicer.
- Interactive visual filtering.
- Dynamic KPI calculations.
- Conditional formatting.
- Custom sorting.
- Visual-level formatting.

## 6. Technical Implementation

The project covers the following Power BI concepts and functionalities.

### Data Preparation
- Connecting to CSV files.
- Data quality assessment.
- Data cleaning and transformation.
- Power Query.
- Column distribution and column profiling.

### Data Modelling
- Creating a dedicated Date Table.
- Establishing relationships between the sales data and Date Table.
- Understanding data granularity.
- Working with calculated columns and measures.

### DAX and Time Intelligence
- CALCULATE function.
- YTD calculations.
- QTD calculations.
- Date functions.
- Text functions.
- Filter functions.
- Time intelligence calculations.

### Dashboard Development
- Custom sorting.
- Conditional formatting.
- New Card Visual.
- Chart creation and formatting.
- Dynamic measures.
- Slicer configuration.
- Dashboard layout and navigation.

## 7. Data Modelling and Preparation

### Step 1: Data Quality Assessment

The dataset was examined using Power Query's Column Distribution and Column Profiling features to assess data quality.

Special attention was given to the Date column, ensuring that it did not contain empty values or errors.

### Step 2: Date Table Creation

A separate Date Table was created to support date-based calculations and time intelligence operations.

This provides a structured foundation for YTD, QTD, monthly, and weekly analysis.

### Step 3: Establishing Relationships

A relationship was established between the Amazon sales data table and the Date Table using the relevant date columns.

### Step 4: Calculated Columns and Measures

Calculated columns and measures were used for different analytical requirements.

- **Calculated Columns:** Used for row-level calculations whose results are stored in the data model.
- **Measures:** Used to calculate results dynamically based on the current filter context.

## 8. Important Learning Concepts

**KPI (Key Performance Indicator):** A measurable value used to evaluate how effectively a business is achieving its objectives.

**Granularity:** The level of detail represented by the data.

**Domain Documentation:** Business or domain documentation should be reviewed to understand the meaning, structure, and context of the data before beginning an analytical project.

**Date Table:** A dedicated calendar table used to support consistent date-based analysis and time intelligence calculations.

**Filter Context:** The set of filters that determines which data is considered when a DAX measure is evaluated.

## 9. Tools and Technologies

- Microsoft Power BI
- Power Query
- DAX
- CSV
- Data Modelling
- Data Visualization

## 10. Project Structure

```text
amazon-sales-analysis-powerbi/
│
├── dashboard/
│   └── Amazon_Sales_Dashboard.pbix
│
├── screenshots/
│   └── amazon_sales_dashboard.png
│
├── docs/
│   └── project_overview.md
│
└── README.md
```

## 11. Learning Reference and Credits

This project was developed as a hands-on learning exercise by following the Power BI tutorial published by **Data Tutorials**.

**Original Tutorial:**

[Amazon Sales Analysis Power BI Project | Complete End-to-End Project](https://www.youtube.com/watch?v=VCjuCKczztQ)

The project provided practical exposure to Power BI, data preparation, data modelling, DAX, time intelligence, and interactive dashboard development.

## 12. Future Improvements

- Extend the dashboard with additional business KPIs.
- Develop independent analytical questions.
- Add deeper product and category performance analysis.
- Improve the dashboard with additional business insights.
- Explore further DAX and time intelligence capabilities.

---

**Project Type:** Power BI Learning Project  
**Domain:** Sales Analytics  
**Status:** Completed (Tutorial-Based Implementation)