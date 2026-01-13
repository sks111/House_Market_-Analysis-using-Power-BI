# 📊 Sales Analytics Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811)
![DAX](https://img.shields.io/badge/DAX-red)
![Power Query](https://img.shields.io/badge/Data%20Transformation-violet)
![Power Query](https://img.shields.io/badge/Power%20Query-blue)
![Status](https://img.shields.io/badge/Project-Complete-success)

---

## 📌 Summary

This project presents a **comprehensive sales analytics dashboard** developed entirely using **Microsoft Power BI**.  
It demonstrates the **complete business intelligence workflow** within Power BI — from raw data ingestion and cleaning to advanced DAX calculations and interactive dashboard creation.

The project is designed to showcase **strong Power BI skills**, including data transformation, data modeling, DAX time intelligence, and business-focused visualization.

---

## 🎯 Business Problem Statement

Organizations often face challenges such as:
- Limited visibility into sales performance trends
- Difficulty tracking year-over-year growth
- Inconsistent pricing analysis (offer vs purchase price)
- Fragmented regional performance insights
- Dashboards that lack clarity for decision-makers

This project addresses these challenges by building a **structured, interactive, and insight-driven Power BI dashboard** that enables stakeholders to quickly understand performance and take action.

---

## 🧠 Dataset Overview

The dataset consists of historical sales records containing:
- Transaction dates
- Sales values and quantities
- Offer and purchase pricing
- Regional segmentation
- Property and customer attributes

The structure supports **time-based analysis**, **pricing comparison**, and **segmentation across multiple business dimensions**.

---

## 🛠️ Tools & Technologies Used

| Area | Tools |
|----|------|
| BI Platform | Microsoft Power BI Desktop |
| Data Preparation | Power Query Editor |
| Data Modeling | Power BI Data Model |
| Calculations | DAX |
| Visualization | Power BI Interactive Visuals |

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed directly within **Power BI** using **Power Query** and visuals to understand the dataset before building metrics.

### EDA Activities
- Verified total record count and column completeness
- Reviewed date ranges and sales distribution
- Identified missing or inconsistent values
- Analyzed pricing outliers and anomalies
- Reviewed regional and categorical coverage

📌 **Outcome:**  
Ensured the data was reliable, complete, and suitable for accurate reporting and analysis.

---

## 🧩 Data Cleaning & Transformation (Power Query)

Data preparation was conducted using **Power Query Editor** to create a clean and analysis-ready dataset.

### Key Transformations
- Handling missing and null values
- Standardizing date and numeric formats
- Creating calculated columns such as:
  - Age
  - Offer Price per Square Meter
- Removing unnecessary columns
- Ensuring consistent categorical values

These steps ensured high data quality and reliable calculations.

---

## 🧠 Data Modeling

A clean and efficient data model was created within Power BI:
- Proper relationships between tables
- Optimized column data types
- Logical organization of measures and fields

This modeling approach supports **fast performance** and **accurate calculations**.

---

## 🧮 DAX Measures & Calculations

Advanced **DAX measures** were created to support business analysis.

### Time Intelligence Metrics
- **Year-over-Year (YoY) Sales Growth**
- **Year-to-Date (YTD) Sales**
- **Last 12 Months (LTM) Sales**
- Quarterly and yearly aggregations

### Sales & Pricing Metrics
- Units Sold
- Average and Median Sales Prices
- Offer Price vs Purchase Price
- Offer Price per Square Meter

### DAX Functions Used
- `CALCULATE`
- `SUM`
- `MAX`
- `YEAR`, `QUARTER`
- `DATESINPERIOD`
- `ALLEXCEPT`
- `IF`, `BLANK`
- `MEDIANX`
- `TOTALYTD`

---

## 📊 Dashboard Pages & Visual Design

The dashboard was designed using **best practices in data visualization**, focusing on clarity, usability, and storytelling.

### 🔹 Sales Performance Page
- KPI Cards (Sales, Units Sold, YoY Growth)
- Line charts showing trends over time
- Donut chart for contribution analysis
- Clustered bar charts for comparisons

### 🔹 Regional Performance Page
- Sales by region
- Median price comparison
- Scatter plot for offer vs purchase price

### 🔹 Customer & Property Insights Page
- Key Influencers visual
- Age-based analysis
- House type performance
- Offer vs purchase price comparison

---

## 📈 Key Insights & Findings

- Sales trends show clear seasonality and growth patterns
- Pricing varies significantly across regions
- Median prices provide more reliable insights than averages
- Offer prices frequently differ from final purchase prices
- Customer and property attributes influence sales outcomes

---

## 📌 Assumptions & Limitations

- Analysis is based on the available dataset
- Currency consistency is assumed
- Some transformations are handled in Power Query
- Results reflect historical data and do not predict future outcomes

---


