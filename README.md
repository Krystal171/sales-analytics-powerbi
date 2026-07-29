# 📊 AtliQ Hardware — Business Insight 360 (Power BI Suite)

An end-to-end interactive Power BI reporting solution designed to provide **360-degree visibility** across AtliQ Hardware's key business functions: **Finance, Sales, Marketing, Supply Chain, and Executive Management**.

---

## 🎯 Problem Statement & Objective
AtliQ Hardware, a global computer hardware manufacturer, faced challenges tracking regional profitability, inventory forecasting errors, and overall margin trends across B2B retail, e-commerce, and direct channels. 

**Objective:** Develop an interactive executive dashboard suite to deliver real-time operational insights, streamline decision-making, and track variance against targets and previous year performance.

---

## 🖼️ Dashboard Architecture & Core Views
### 1. OverView

![Uploading overview.gif…]()

### 1. Finance View
* **Focus:** Profitability & P&L Statement breakdown.
* **Key Metrics:** Net Sales, Gross Margin %, Net Profit %, Gross Margin vs Target / Last Year.
* **Visuals:**
  <img width="2294" height="1296" alt="image" src="https://github.com/user-attachments/assets/f6ba8bfa-e9d1-42c1-b193-e2dd0d328d94" />

  

### 2. Sales View
* **Focus:** Customer and product performance.
* **Key Metrics:** Net Sales, Gross Margin Variance.
* **Visuals:** Scatter plot performance matrix and customer margin performance tables.

### 3. Marketing View
* **Focus:** Market performance and product region dynamics.
* **Key Metrics:** Net Sales vs Gross Margin bifurcation, Net Profit %.
* **Visuals:** Market performance scatter plot and product segment breakdown.

### 4. Supply Chain View
* **Focus:** Inventory and demand forecasting performance.
* **Key Metrics:** Forecast Accuracy %, Net Error, Absolute Error (ABS Error).
* **Visuals:** Monthly accuracy trends and key metrics by customer/product segment.

### 5. Executive View
* **Focus:** Consolidated strategic overview for senior management.
* **Key Metrics:** Market Share trends, Revenue by Division, Revenue by Channel, Top 5 Customers, and Top 5 Products.

---

## 🛠️ Technical Stack & Key Capabilities

* **Tool:** Power BI Desktop
* **Data Modeling:** Star Schema design connecting Fact Sales, Forecast, and P&L tables with Dimension tables (Customer, Product, Market, Calendar).
* **DAX Formulas Applied:**
  * Dynamic measure toggling using `SWITCH(TRUE(), ...)`
  * Time Intelligence calculations (YTD, YTG, YoY Growth, vs LY, vs Target)
  * Custom KPI conditional formatting
* **Data ETL:** Power Query transformation, unpivoting datasets, and data hygiene cleaning.
* **UI/UX Features:** Navigation tabs, custom filter sidebar (Year, Quarter, Region, Store, Channel), dynamic tooltips, and bookmark toggles.

---


