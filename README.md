# 📊 AtliQ Hardware — Business Insight 360 (Power BI Suite)

An end-to-end interactive Power BI reporting solution designed to provide **360-degree visibility** across AtliQ Hardware's key business functions: **Finance, Sales, Marketing, Supply Chain, and Executive Management**.AtliQ Hardwares is a consumer electronics company expanding rapidly but is not able to compete with other companies using data as most of their report still exists in Excel. My goal is to implement an advanced analytics solution using Power BI that will enable the company to get insights and make informed decisions.

---

## 🎯 Problem Statement & Objective
AtliQ Hardware, a global computer hardware manufacturer, faced challenges tracking regional profitability, inventory forecasting errors, and overall margin trends across B2B retail, e-commerce, and direct channels. 

**Objective:** Develop an interactive executive dashboard suite to deliver real-time operational insights, streamline decision-making, and track variance against targets and previous year performance.
In this project, the goal is to be one report which could be used by stakeholders from sales, marketing, finance and executive team. The focus is made on the following

1. Robust Data Modeling
2. User-empathetic Report design
3. Drillable Insights

**************************
Data modelling involving 10+ tables
<img width="720" height="450" alt="Project_Screenshot2_updated" src="https://github.com/user-attachments/assets/d1345136-71e1-49b2-84d6-8498a82b5dcc" />

---

## 🖼️ Dashboard Architecture & Core Views
### 1. OverView
<img width="2282" height="1286" alt="overview" src="https://github.com/user-attachments/assets/43ff8384-2546-4f76-95e5-26c394f8d8b4" />



### 1. Finance View
* **Focus:** Profitability & P&L Statement breakdown.
* **Key Metrics:** Net Sales, Gross Margin %, Net Profit %, Gross Margin vs Target / Last Year.
* **Visuals:**
  <img width="2294" height="1296" alt="image" src="https://github.com/user-attachments/assets/f6ba8bfa-e9d1-42c1-b193-e2dd0d328d94" />

  

### 2. Sales View
* **Focus:** Customer and product performance.
* **Key Metrics:** Net Sales, Gross Margin Variance.
* **Visuals:**
* <img width="2300" height="1290" alt="image" src="https://github.com/user-attachments/assets/fa17fc2b-47d8-4972-8d2e-77c349f0d215" />


### 3. Marketing View
* **Focus:** Market performance and product region dynamics.
* **Key Metrics:** Net Sales vs Gross Margin bifurcation, Net Profit %.
* **Visuals:**
  <img width="2298" height="1290" alt="image" src="https://github.com/user-attachments/assets/e3e1fbfa-f16d-4ddd-8046-0752851297f8" />


### 4. Supply Chain View
* **Focus:** Inventory and demand forecasting performance.
* **Key Metrics:** Forecast Accuracy %, Net Error, Absolute Error (ABS Error).
* **Visuals:**
  <img width="2290" height="1294" alt="image" src="https://github.com/user-attachments/assets/80ec34b5-6368-4a91-8280-56ccefb05444" />


### 5. Executive View
* **Focus:** Consolidated strategic overview for senior management.
* **Key Metrics:**
  <img width="2302" height="1296" alt="image" src="https://github.com/user-attachments/assets/c09f26eb-9dc1-4f8d-b1e1-dcde826e9002" />


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

I learned the following things in this project

1. Power Query (Basic and Advanced Operations) 
2. Basic and complex DAX formulas
3. Data modelling involving 10+ tables
4. Choosing the right visuals and formatting
5. Dashboard designing principles
6. Using bookmarks
7. Deploying in Power BI service
8. Stakeholder Feedback Implementation
9. Sales, Marketing, Finance & Supply Chain metrics


