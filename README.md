# Data-Analytics-Portfolio
Portfolio of data projects focused on analysis, visualization, and automation to drive informed decision-making.
# Jerry Oghuan | Data Analytics Portfolio

Welcome to my data analytics portfolio!  
This repository highlights my work in **data analysis, visualization, and automation** using tools such as **Power BI, SQL, Excel, Tableau, Snowflake, and R**.  
It’s designed to demonstrate how I approach business data problems — from cleaning and modeling datasets to building dashboards that uncover key trends like revenue growth, retention, and performance efficiency.

---

## 🧭 Overview
I specialize in translating data into practical business insights through clear models and visuals.  
Each project here is simple enough to follow yet reflects professional-level logic used in real-world environments.  

You’ll find examples covering:
- Revenue and performance tracking (Month-over-Month, Year-over-Year)
- Data cleaning and transformation with SQL and R
- Executive dashboards in Power BI and Tableau
- Data modeling in Snowflake for reporting automation
- Excel-based analytics templates

The goal is to show not just technical ability, but *data storytelling* — how numbers translate to decisions.

---

## 📊 Featured Projects

  ### 1. Revenue Performance Dashboard (Power BI)

**Goal:** Show month-over-month (MoM) and year-over-year (YoY) revenue trends with business-unit and regional segmentation.

**Highlights:**
- Built DAX measures for Total Revenue, Budget Variance %, and YoY Growth %.
- Added slicers for Year, Business Unit, and Month to enable flexible analysis.
- Compared Actual vs Budget revenue using a combo chart.
- Included doughnut and trend visuals for an executive-friendly overview.

**Files:**
- Data source (Excel): `/data/Revenue_Dashboard_Data.xlsx`
- Power BI report: `/PowerBI/Revenue_Performance_Dashboard.pbix`


---

### 2. Sales Analytics & Customer Insights (SQL)
**Goal:** Identify customer retention rates and sales performance by category.  
**Highlights:**
- Used CTEs and window functions (`ROW_NUMBER`, `LAG`, `LEAD`) to analyze repeat customers.  
- Applied CASE logic for segmentation and cohort labeling.  
- Exported results to Power BI for visualization.  
**Files:** `/SQL/sales_insights.sql`

---

### 3. Business Metrics Tracker (Excel)
**Goal:** Create an Excel template for revenue, expenses, and KPI tracking.  
**Highlights:**
- Used dynamic formulas (`SUMIFS`, `INDEX-MATCH`, and slicers).  
- Auto-refresh setup through Power Query.  
- Designed for quick executive summaries and print-ready reports.  
**Files:** `/Excel/business_metrics_tracker.xlsx`

---

### 4. Data Model & Snowflake Integration
**Goal:** Build a reusable data model to automate reporting refreshes.  
**Highlights:**
- Modeled fact and dimension tables (Star Schema).  
- Used Snowflake SQL to optimize joins and calculations.  
- Documented lineage for Power BI connection.  
**Files:** `/Snowflake/data_model_design.sql`

---

### 5. Data Visualization Showcase (Tableau)
**Goal:** Create a Tableau dashboard for regional sales and profitability.  
**Highlights:**
- Designed clean, minimalist visuals emphasizing comparative trends.  
- Added parameter controls for category filtering.  
- Used calculated fields for growth percentages.  
**Files:** `/Tableau/Sales_Performance_Dashboard.twbx`

---

### 6. Statistical Trends & Forecasting (R)
**Goal:** Use R to project future revenue based on historical trends.  
**Highlights:**
- Applied basic time-series forecasting using `forecast` and `ggplot2`.  
- Visualized residual patterns and accuracy.  
- Exported output for Power BI integration.  
**Files:** `/R/revenue_forecast.R`

---

## 🧰 Technical Skills

| Category | Tools & Skills |
|-----------|----------------|
| **Data Visualization** | Power BI, Tableau, Excel Dashboards |
| **Data Modeling & SQL** | SQL (CTE, Joins, DAX, Views), Snowflake |
| **Data Transformation** | Power Query, R (Data Wrangling), Excel Formulas |
| **Automation** | Power BI Service, Excel Macros, Scheduled Refresh |
| **Reporting Focus** | Revenue Analysis, Operational KPIs, Forecasting |

---

## 🚀 Repository Structure
