# Power-BI---Blinkit-Business-Dashboard

# Blinkit Sales & Operations Analysis – Power BI Project

## Overview

This project is an end-to-end **Power BI Business Intelligence Case Study** built using Blinkit grocery sales data. The dashboard provides detailed insights into sales performance, customer purchasing behavior, product distribution, outlet analysis, and operational efficiency.

The objective of this project is to transform raw retail data into actionable business insights using Power BI, data modeling, DAX calculations, and interactive visualizations.

This project simulates a real-world retail analytics environment and demonstrates practical skills required for **Data Analyst** and **Business Intelligence Analyst** roles.

---

# Business Problem

Retail businesses generate massive amounts of transactional and operational data. However, without proper analysis, identifying trends, sales opportunities, and operational inefficiencies becomes difficult.

This project helps answer critical business questions such as:

* Which products generate the highest sales?
* Which outlet types perform best?
* How do customer ratings impact sales?
* Which outlet locations contribute most to revenue?
* What are the sales trends across item categories?
* How can inventory and operational decisions be improved?

---

# Project Objectives

* Analyze Blinkit grocery sales performance
* Build an interactive Power BI dashboard
* Create meaningful KPIs for business monitoring
* Identify high-performing products and outlets
* Perform location-based sales analysis
* Demonstrate data visualization and storytelling skills

---

# Tech Stack

* **Power BI** – Dashboard Development & Data Visualization
* **DAX** – KPI Calculations & Measures
* **Power Query** – Data Cleaning & Transformation
* **Excel / CSV** – Dataset Source
* **Data Modeling** – Relationship Management

---

# Dataset Information

The dataset contains grocery sales and outlet-related information including:

| Dataset                    | Description                      |
| -------------------------- | -------------------------------- |
| `BlinkIT Grocery Data.csv` | Main transactional sales dataset |
| `Cities.csv`               | City-level information           |
| `Items.csv`                | Product category information     |
| `Items Content.csv`        | Item content details             |
| `Outlet Info.csv`          | Outlet details and attributes    |
| `Outlet Location.csv`      | Outlet location mapping          |

---

# Key KPIs

The dashboard tracks the following business KPIs:

* Total Sales
* Average Sales
* Number of Items Sold
* Average Customer Rating
* Outlet Performance
* Sales by Item Type
* Sales by Outlet Size
* Sales by Outlet Location
* Fat Content Analysis
* Year-wise Outlet Establishment Trends

---

# Dashboard Features

## Sales Performance Analysis

* Total revenue monitoring
* Product category-wise sales analysis
* High-performing item identification

## Outlet Analysis

* Outlet size comparison
* Outlet type performance tracking
* Location-based sales insights

## Customer Insights

* Customer rating analysis
* Consumer preference identification
* Product demand distribution

## Operational Insights

* Inventory planning support
* Revenue contribution analysis
* Business growth trend analysis

---

# Data Cleaning & Transformation

Data preprocessing was performed using **Power Query** including:

* Handling missing values
* Standardizing categorical data
* Data type conversion
* Removing duplicates
* Creating calculated columns
* Building data relationships

---

# Data Modeling

The project uses a relational data model connecting:

* Grocery sales data
* Outlet information
* Product categories
* Location datasets

Relationships were created to ensure accurate filtering and dashboard interactivity.

---

# DAX Measures Used

Examples of DAX calculations used in the project:

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
```

```DAX
Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
```

```DAX
Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
```

```DAX
Number of Items = COUNT('BlinkIT Grocery Data'[Item Identifier])
```

---

# Folder Structure

```bash
project-blinkit/
│
├── Blinkit_BI_Project_final.pbix
├── Blinkit Bi Case Study.docx
│
├── Blinkit Bi dataset/
│   ├── BlinkIT Grocery Data.csv
│   ├── Cities.csv
│   ├── Items.csv
│   ├── Items Content.csv
│   ├── Outlet Info.csv
│   ├── Outlet Location.csv
│   └── Original.xlsx
```

---

# Dashboard Insights

Some important insights derived from the analysis:

* Certain outlet locations contribute significantly higher revenue
* Medium-sized outlets generate strong overall sales performance
* Specific item categories dominate total sales contribution
* Customer ratings show a positive correlation with product demand
* Outlet establishment trends indicate business expansion patterns

---

# Business Impact

This dashboard can help stakeholders:

* Monitor sales performance efficiently
* Improve inventory management
* Optimize outlet operations
* Identify profitable product categories
* Support data-driven business decisions

---

# Skills Demonstrated

This project showcases:

* Data Cleaning
* Data Modeling
* DAX Calculations
* Business Intelligence Reporting
* KPI Development
* Dashboard Design
* Retail Sales Analytics
* Data Visualization
* Business Problem Solving

---

# Future Enhancements

Possible future improvements include:

* Adding predictive sales forecasting
* Integrating SQL database connectivity
* Creating automated refresh pipelines
* Building advanced customer segmentation
* Deploying dashboards to Power BI Service

---
# Project Description

Constructed an interactive Power BI dashboard using DAX measures, Power Query, and data
modeling techniques to analyze INR 1.2M sales data across multiple outlet categories
Created KPI metrics for sales, ratings, and outlet performance.
Identified key trends in product categories and regional sales distribution

---

# Author

## Nomula Pratyusha

Data Analyst | Power BI | SQL | Python | Excel

---
# Challenges Faced 

Cleaned inconsistent and missing data using Power Query
Built relationships between multiple tables for accurate analysis
Created DAX measures for KPIs and business insights
Optimized dashboard performance for large datasets
Designed interactive and user-friendly dashboard visuals
Managed data transformation and formatting issues
Implemented dynamic filters and slicers for better analysis
Ensured accurate sales and outlet performance reporting
Structured data model for efficient dashboard navigation
Converted raw retail data into actionable business insights

---

<img width="1373" height="741" alt="Screenshot 2026-04-28 184558" src="https://github.com/user-attachments/assets/cd18419c-fc70-435d-b8db-02b049d5e7d6" />

---

<img width="1368" height="746" alt="Screenshot 2026-04-28 184652" src="https://github.com/user-attachments/assets/9a80df93-dff2-4bd8-82ec-a8b1a0503b1f" />

---
<img width="1377" height="746" alt="Screenshot 2026-04-28 184727" src="https://github.com/user-attachments/assets/b3146bc9-1b89-43cb-b149-9c86a75faa1d" />

