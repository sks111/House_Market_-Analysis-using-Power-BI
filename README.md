# 📊 House Market Analysis using Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811)
![DAX](https://img.shields.io/badge/DAX-red)
![DAX](https://img.shields.io/badge/Data_Transformation-green)
![DAX](https://img.shields.io/badge/Power_Query-blue)
![Status](https://img.shields.io/badge/Project-Complete-success)

---

## 🧾Summary

This project presents an **end-to-end Power BI dashboard** designed to analyze **house market sales, pricing dynamics, and regional performance**.  
The solution is built **entirely in Power BI Desktop**, showcasing strong capabilities in:

- Data preparation using **Power Query**
- Analytical calculations using **DAX**
- Insight-driven **interactive dashboard design**

The dashboard enables stakeholders to **quickly evaluate market trends, compare pricing behavior, and understand key drivers behind property sales**.

---

## 🎯 Project Objectives

The primary objectives of this analysis are to:

- Compare **offer price vs final purchase price**
- Identify **high-performing regions and sales types**
- Track **recent market trends and YoY growth**
- Analyze **pricing efficiency using SQM-based metrics**
- Understand **factors influencing house prices**

---

## 🧠 Dataset Overview

The dataset contains historical house market transaction records, including:

- Date attributes (Year, Quarter, Month)
- Offer price and purchase price
- Property size (Square Meters)
- House type and sales type
- Region, city, and area
- Additional property-related attributes

This structure enables **time-based analysis, pricing comparison, and multi-dimensional filtering**.

---

## 🛠️ Tools & Technologies

| Area | Tool |
|---|---|
| BI Platform | Microsoft Power BI Desktop |
| Data Preparation | Power Query Editor |
| Calculations | DAX |
| Visualization | Native Power BI Visuals |

---

## 🔍 Data Preparation & Analysis

All data preparation was performed using **Power Query Editor**.

Key steps included:
- Cleaning missing and inconsistent values
- Standardizing numeric and date formats
- Creating calculated columns such as:
  - **Age**
  - **Offer Price per SQM**
- Removing unnecessary fields
- Ensuring consistency across categorical data

These steps ensured **high-quality, analysis-ready data**.

---

## 🧮 DAX Measures & Logic

Advanced DAX measures were created to support meaningful business analysis.

### ⏱️ Time Intelligence Metrics
- **Year-over-Year (YoY) Sales Growth**
- **Year-to-Date (YTD) Sales**
- **Last 12 Months Sales**

These measures allow stakeholders to assess both **short-term momentum and long-term trends**.

### 💰 Pricing & Performance Metrics
- Units Sold
- Average Sales Price
- **Median Sales Price Change**
- Offer Price vs Purchase Price
- Offer Price per Square Meter

### 🔑 Key DAX Functions Used
`CALCULATE`, `SUM`, `MAX`, `DATESINPERIOD`, `TOTALYTD`,  
`ALLEXCEPT`, `IF`, `BLANK`, `MEDIANX`

---

## 📊 Dashboard Overview & Insights

The Power BI report is organized into **multiple pages**, each designed with a clear analytical purpose.

---

## 🌍 Sales Overview Dashboard

![Sales Overview](https://github.com/sks111/House_Market_-Analysis-using-Power-BI/blob/main/Screenshot%20(2).png)

### Purpose
Provide a **high-level overview of sales performance** across regions and sales types.

### Key Visuals
- Sales by Region
- Average Price per SQM by Region
- Key Influencers analysis
- Offer-to-SQM ratio by sales type
- Detailed transaction table

### Business Insights
- Certain regions contribute disproportionately to total sales
- Sales type significantly impacts pricing efficiency
- Multiple attributes influence final purchase prices

---

## 📈 House Market Overview Dashboard

![House Market Overview](https://github.com/sks111/House_Market_-Analysis-using-Power-BI/blob/main/Screenshot%20(3).png)

### Purpose
Track **overall market trends and recent performance indicators**.

### Key Visuals
- Median sales price change by region
- Units sold in the latest quarter
- Last 12 months sales
- Offer vs purchase price scatter plot
- YoY sales growth by sales type

### Business Insights
- Regional variation in price growth trends
- Recent quarters highlight shifts in market momentum
- Strong correlation between offer and final purchase prices

---

## 📈 Key Insights Summary

- Significant regional variation in both sales volume and pricing
- Median-based analysis provides more reliable insights than averages
- Offer prices often differ meaningfully from final purchase prices
- Time-intelligence metrics clearly highlight market trends

---

## 📌 Assumptions & Limitations

- Analysis is based on historical data
- Currency consistency is assumed
- Results are descriptive, not predictive

---

