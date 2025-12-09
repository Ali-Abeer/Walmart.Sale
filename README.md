# Walmart.Sale

📊 **Walmart Sales Analytics Dashboard – Power BI**

A fully interactive Power BI analytics solution built using Walmart’s sales forecasting dataset. This project transforms raw weekly sales data into meaningful insights for executives, store managers, and category/department teams.

🚀 **Project Overview**

This dashboard provides a multi-layered analysis of Walmart’s store and department performance across weekly periods, holidays, markdowns, economic factors, and store characteristics.

The solution includes:

A cleaned and modeled data foundation

A dedicated Date table enabling accurate time intelligence

A rich DAX measure layer powering KPIs such as Total Sales, Average Weekly Sales, Holiday Uplift, Markdown Impact, WoW Changes, and more

Three fully-interactive dashboards (Executive, Store, Department performance)

📁 **Dashboard Pages**
1. **Executive Summary Dashboard**

Designed for leadership, providing a top-level view of:

Total Sales (≈ $6.74B)

Average Weekly Sales

Markdown Sales

Store Count

Sales by Store & Department

Holiday vs Non-Holiday trends

Impact of fuel price and temperature on sales

Weekly trend line for seasonality patterns


2. **Store Performance Dashboard**

A detailed breakdown of the performance of 45 stores, including:

Sales by Store Type (A, B, C) and Store Size

Top-performing stores and low-performing outliers

Revenue by individual store

Week-by-week performance using interactive slicers

Comparative analysis across store clusters


3. **Department Analytics Dashboard**

Deep insights at the department level:

Sales by Department

Markdown Impact on Sales

Holiday vs Non-Holiday sales performance

Relationship between sales and macroeconomic variables such as CPI, Unemployment, Temperature

Weekday performance comparison

DAX-driven calculations for deeper trend understanding

🧹 **Data Preparation & Modeling**
✔ Cleaned Dataset (walmart_cleaned) Includes:

Weekly Sales

Store Type & Size

Holiday Flags

Markdown Values (Multiple Markdown fields)

Fuel Price

Temperature

CPI (Consumer Price Index)

Unemployment

Date Key

✔ **Data Model**

Fact Table: Walmart weekly sales

Dimension Table: Date table (marked as Date)

Relationships: One-to-many relationships to support time intelligence

Star-schema style structure for optimized reporting

reporting

🧮 **Key DAX Measures Developed**

Some of the critical calculations include:

Total Sales

Average Weekly Sales

Sales per Store

Holiday Sales vs Non-Holiday Sales

Markdown Sales

Markdown Impact

Week-over-Week Change & % Change

Sales-to-Fuel Price Ratio

Sales-to-Temperature Ratio

These measures provide the backbone for all visual insights.

🛠 ** Tools & Technologies**

Power BI

DAX (Data Analysis Expressions)

Power Query (data cleaning & transformations)

Data Modeling


**Insights Uncovered**

Larger stores (Store Type A) consistently outperform others.

Sales spike significantly during holiday weeks.

Markdown activities influence demand differently across departments.

External factors such as fuel price, temperature, and CPI correlate with fluctuations in customer demand.

Some departments show higher sensitivity to economic conditions than others.


**📂 Project Files**
File	Description
Project 2.pbix	Full Power BI dashboard
Project Summary.docx	Written overview of the dashboard
Dashboard explanation.docx	Detailed explanation of dashboard visuals and logic


🤝 **How to Use**

Download or clone this repository.

Open Project 2.pbix in Power BI Desktop.

Explore dashboards using the slicers (Store, Department, Date).

Review documentation files for detailed metric definitions and modelling notes.


**Future Improvements**

Add forecasting using Power BI’s built-in predictive analytics

Expand model to include inventory or customer demographics

Deploy via Power BI Service and build automated refresh pipelines


**📬 Contact**

Email = aabeer.au@gmail.com
Linkedin profile = www.linkedin.com/in/ali-abeer-522289357


