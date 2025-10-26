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

## 🗂️ Dataset Details  
| **Dataset/Table** | **Description** | 
|------------------|-----------------|-------------------|
| `Customer` | Customer demographics (age, gender, income group, marital status) | 
| `Cust_Address` | Customer location (city, state, country) | 
| `Credit_Card` | Card type, limits, status, category | 
| `Transaction` | Transaction ID, amount, payment mode, date | 



---

## 🧭 Workflow  

### 1. Data Source & Connection
- Imported datasets from SQL / CSV files.  
- Connected Power BI to a relational database backend for query optimization.

### 2. Data Cleaning & Transformation
- Used **Power Query Editor** to filter, merge, rename, and format data.  
- Removed missing values and standardized column types.

### 3. Data Modeling
- Created relationships between fact (`Transaction`) and dimension (`Customer`, `Category`) tables.  
- Built a **Star Schema** for efficient analytics.  

### 4. DAX Measures
Defined key metrics such as:  
```text
Total Revenue = SUM(Transaction[Revenue])
Average Transaction Value = DIVIDE([Total Revenue], [Transaction Count])
Monthly Growth = (ThisMonth - LastMonth) / LastMonth

### **5. Dashboard Design**
- Bar charts, donut charts, line charts, KPI cards, and matrix visuals.  
- Slicers for filtering by customer, time, and category.  
- Consistent color palette and professional layout.

---

## **📊 Key KPIs**  

| **Category** | **Metric** | **Description** |
|--------------|-----------|----------------|
| 💰 **Revenue** | Total Revenue | Sum of all credit card revenue |
| 💳 **Transactions** | Total Transaction Amount | Total transaction value |
| 🧾 **Transactions** | Transaction Count | Number of transactions |
| 📈 **Revenue** | Interest Earned | Total interest from transactions |
| 👥 **Customers** | Customer Count | Active cardholders |
| 📊 **Trends** | Quarterly/Monthly Trends | Revenue and spending growth |
| 💎 **Card Category** | Insights by Type | Revenue breakdown by card type |
| 🧔 **Demographics** | Customer Insights | Spend by gender, age, income |

---

## **💡 Insights & Business Impact**  
- **High-value customers:** Top 10% contribute ~45% of revenue → targeted retention campaigns.  
- **Card performance:** Platinum and Gold cards drive the highest revenue.  
- **Customer behavior:** Younger customers (25–35) transact more frequently → marketing focus.  
- **Revenue growth:** Consistent quarter-over-quarter growth → indicates healthy card usage trends.  
- **Interest income:** Significant portion of revenue → helps prioritize high-interest products.  

---

## **🖼️ Dashboard Preview**  

### **🧾 Customer Dashboard**  
> Visualizes customer metrics like total spend, active users, and category distribution.  
![Customer Dashboard](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Customer_Snapshot.jpg)

### **💰 Transaction Dashboard**  
> Displays revenue, transaction counts, and trends for performance tracking.  
![Transaction Dashboard](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Transaction_Snapshot.jpg)

---

## **🧩 Challenges & Solutions**  
| **Challenge** | **Solution** |
|---------------|--------------|
| Inconsistent data across multiple tables | Standardized column names, removed nulls, validated relationships |
| Dashboard performance issues | Optimized DAX calculations and created aggregated tables |
| Complex KPI calculations | Developed step-by-step DAX measures for accuracy |
| Visual layout clarity | Applied consistent color scheme, clear labeling, and slicers |

---

## **🔮 Future Enhancements**  
- Integrate real-time data using **Power BI Service**.  
- Add predictive analytics for **customer churn** and **fraud detection**.  
- Automate email reports with **Power Automate**.  
- Expand dataset for multi-bank credit card analysis.  

---

## **🧰 Tools & Technologies**  

| **Tool / Technology** | **Purpose** |
|-----------------------|------------|
| Power BI Desktop | Dashboard development and visualization |
| SQL Database | Data storage and queries |
| DAX (Data Analysis Expressions) | KPI and measure calculations |
| Power Query (M) | Data cleaning and transformation |

---

## **📝 Credits**  
- Inspired by: [YouTube - Power BI Full Project for Data Analysis](https://www.youtube.com/watch?v=8XoDVwWdaqI)  
- Dataset: [Kaggle Credit Card Financial Dashboard](https://www.kaggle.com/datasets/nibeditasahu/credit-card-financial-dashboard-using-power-bi)  
- Developed by: [Shradha Pol](https://www.linkedin.com/in/shradhapolofficial)  

---

## **📜 License**  
This project is licensed under the **MIT License** — feel free to explore, learn, and reuse with credit.  

---

## **🤝 Contact**  
👤 **Shradha Pol**  
- 💼 [LinkedIn](https://www.linkedin.com/in/shradhapolofficial)  
- 📂 [GitHub](https://github.com/shradha-pol)
