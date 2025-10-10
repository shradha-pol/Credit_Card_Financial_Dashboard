# 💳 Credit Card Financial Dashboard — Power BI Project  

## 📘 Overview  
This project showcases a **complete end-to-end Power BI dashboard** for analyzing **credit card financial transactions**.  
It demonstrates data integration, transformation, modeling, DAX measures, and dashboard design — providing valuable business insights from transactional data.  

🔗 **Live Project Reference:** [YouTube - Power BI Full Project for Data Analysis](https://www.youtube.com/watch?v=8XoDVwWdaqI)  
📊 **Dataset Source:** [Credit Card Financial Dashboard Dataset (Kaggle)](https://www.kaggle.com/datasets/nibeditasahu/credit-card-financial-dashboard-using-power-bi)

---

## 🎯 Objectives  
- Build a dynamic dashboard to visualize credit card transaction data.  
- Implement a complete data analytics pipeline (SQL → Power BI → Insights).  
- Use DAX calculations for KPIs and performance tracking.  
- Provide business-ready insights for decision making.  

---

## 🧭 Project Workflow  

### 1. **Data Source & Connection**
- Imported datasets (Credit Card, Customer, Category) from SQL / CSV files.  
- Connected Power BI to a relational database backend.  

### 2. **Data Cleaning & Transformation**
- Used **Power Query Editor** for filtering, merging, renaming, and formatting data.  
- Removed missing values and standardized column data types.  

### 3. **Data Modeling**
- Created relationships between fact (transactions) and dimension (customer, category) tables.  
- Built a **star schema** for efficient analytics.  

### 4. **DAX Measures**
Defined key metrics such as:  
- `Total Revenue = SUM(Transaction[Revenue])`  
- `Average Transaction Value = DIVIDE([Total Revenue], [Transaction Count])`  
- `Monthly Growth = (ThisMonth - LastMonth) / LastMonth`  

### 5. **Dashboard Design**
- Added charts: bar, donut, line, KPI cards, and matrix visuals.  
- Used slicers for filtering by customer, time, and category.  
- Applied consistent color palette and layout for professional look.  

---

## 📊 Key KPIs & Insights  

| Metric | Description |
|--------|-------------|
| 💰 **Total Revenue** | Total revenue generated from all credit card transactions |
| 💳 **Total Transaction Amount** | Sum of all transaction values |
| 🧾 **Transaction Count** | Total number of transactions made |
| 📈 **Interest Earned** | Total interest collected from transactions |
| 👥 **Customer Count** | Number of active credit card customers |
| 📊 **Quarterly/Monthly Trends** | Tracks revenue and spending growth over time |
| 💎 **Card Category Insights** | Breakdown of revenue and spend by card type (Gold, Silver, Platinum, etc.) |
| 🧔‍♂️ **Demographic Insights** | Spend and revenue distribution by gender, age group, and income level |

### 📈 Key Insights Summary
- Platinum and Gold cards generate the highest revenue share.  
- Younger customers (25–35 age group) show higher transaction frequency.  
- Revenue has shown consistent growth quarter-over-quarter.  
- Interest income forms a significant portion of overall revenue.  
- High-income customers prefer premium card categories.  

---

## 🧰 Tools & Technologies  

| Tool / Technology | Purpose |
|-------------------|----------|
| **Power BI Desktop** | Data visualization and dashboard development |
| **SQL Database** | Data storage and connection |
| **DAX (Data Analysis Expressions)** | Measure calculations |
| **Power Query (M)** | Data cleaning and ETL process |

---

## 🖼️ Dashboard Preview  

### 🧾 Customer Dashboard  
> Visualizes customer-level metrics such as total spend, active customers, and spending distribution by category.
![Customer Dashboard](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Customer_Snapshot.jpg)

### 💰 Transaction Dashboard 
> Displays transactional insights such as total revenue, transaction count, and monthly trends for performance tracking.
![Transaction Dashboard](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Transaction_Snapshot.jpg)
  
---

## 📝 Credits  
- Inspired by: [Power BI Full Project for Data Analysis (YouTube)](https://www.youtube.com/watch?v=8XoDVwWdaqI)  
- Dataset: [Credit Card Financial Dashboard - Kaggle](https://www.kaggle.com/datasets/nibeditasahu/credit-card-financial-dashboard-using-power-bi)  
- Developed by: [Shradha Pol](https://www.linkedin.com/in/shradhapolofficial)  
