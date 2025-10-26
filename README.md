
# 💳 Credit Card Financial Dashboard — Power BI Project
> **Why This Project Stands Out:** A complete end-to-end Power BI solution that transforms raw credit card transaction data into actionable business insights through interactive dashboards, KPI tracking, and customer behavior analysis.

## 📘 Overview
This project demonstrates an end-to-end **Power BI dashboard** analyzing **credit card transactions**, covering **data integration, transformation, modeling, DAX measures, and interactive visualization**. The dashboard enables tracking of revenue, customer behavior, transaction trends, and card category performance, helping financial institutions make **data-driven decisions**.

## 🎯 Objectives
- Build a dynamic, interactive Power BI dashboard for credit card analysis
- Implement a full **data analytics pipeline**: SQL → Power BI → Insights
- Calculate KPIs using **DAX measures** for accurate performance tracking
- Provide actionable insights to optimize **customer retention, revenue growth, and card performance**

## 🗂️ Dataset Details
| Dataset/Table | Description | 
|---------------|-------------|
| `Customer` | Customer demographics (age, gender, income group, marital status) | 
| `Cust_Address` | Customer location (city, state, country) | 
| `Credit_Card` | Card type, limits, status, category | 
| `Transaction` | Transaction ID, amount, payment mode, date | 

> All datasets are anonymized and used for **educational purposes**.  
**Dataset Source:** [Kaggle Credit Card Financial Dashboard](https://www.kaggle.com/datasets/nibeditasahu/credit-card-financial-dashboard-using-power-bi)

## 🧭 Workflow
1. **Data Source & Connection:** Imported datasets from SQL and CSV files. Connected Power BI to a relational database for efficient querying.
2. **Data Cleaning & Transformation:** Used **Power Query Editor** to filter, merge, rename, and standardize data. Handled missing values, duplicates, and data type inconsistencies.
3. **Data Modeling:** Built relationships between fact (`Transaction`) and dimension (`Customer`, `Credit_Card`) tables. Designed a **Star Schema** for optimized analysis.
4. **DAX Measures:** Key metrics:
\`\`\`text
Total Revenue = SUM(Transaction[Revenue])
Average Transaction Value = DIVIDE([Total Revenue], [Transaction Count])
Monthly Growth = ([ThisMonth] - [LastMonth]) / [LastMonth]
\`\`\`
5. **Dashboard Design:** Interactive visuals include bar charts, donut charts, line charts, KPI cards, and matrix visuals. Filters/slicers for customer, time, and card category. Professional and consistent color palette.

## 📊 Key KPIs
| Category | Metric | Description |
|----------|--------|------------|
| 💰 Revenue | Total Revenue | Sum of all credit card revenue |
| 💳 Transactions | Total Transaction Amount | Total transaction value |
| 🧾 Transactions | Transaction Count | Number of transactions |
| 📈 Revenue | Interest Earned | Total interest generated |
| 👥 Customers | Customer Count | Active cardholders |
| 📊 Trends | Quarterly/Monthly Trends | Revenue & spending growth |
| 💎 Card Category | Insights by Type | Revenue breakdown by card type |
| 🧔 Demographics | Customer Insights | Spend by gender, age, income group |

## 💡 Insights & Business Impact
- **High-value customers:** Top 10% contribute ~45% revenue → target retention campaigns.
- **Card performance:** Platinum & Gold cards drive highest revenue.
- **Customer behavior:** 25–35 age group transacts most → marketing focus.
- **Revenue growth:** Healthy quarter-over-quarter increase.
- **Interest income:** Significant contributor → prioritize high-interest products.

## 🖼️ Dashboard Preview
### Customer Dashboard
> Shows customer metrics: total spend, active users, category distribution  
![Customer Dashboard](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Customer_Snapshot.jpg)

### Transaction Dashboard
> Displays revenue, transaction counts, and trends  
![Transaction Dashboard](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Transaction_Snapshot.jpg)

**Live Project Video:** [YouTube Full Power BI Project](https://www.youtube.com/watch?v=8XoDVwWdaqI)

## 🧩 Challenges & Solutions
| Challenge | Solution |
|-----------|---------|
| Inconsistent data | Standardized columns, removed nulls, validated relationships |
| Dashboard performance | Optimized DAX, created aggregated tables |
| Complex KPI calculations | Step-by-step DAX measures for accuracy |
| Visual clarity | Consistent color scheme, labeling, and slicers |

## 🔮 Future Enhancements
- Real-time data integration via Power BI Service
- Predictive analytics: customer churn & fraud detection
- Automated email reporting with Power Automate
- Multi-bank credit card dataset expansion

## 🧰 Tools & Technologies
| Tool / Technology | Purpose |
|------------------|---------|
| Power BI Desktop | Dashboard development and visualization |
| SQL Database | Data storage and queries |
| DAX | KPI & measure calculations |
| Power Query (M) | Data cleaning and transformation |

## 📝 Credits
- Inspired by: [YouTube Power BI Full Project](https://www.youtube.com/watch?v=8XoDVwWdaqI)
- Dataset: [Kaggle Credit Card Dashboard](https://www.kaggle.com/datasets/nibeditasahu/credit-card-financial-dashboard-using-power-bi)
- Developed by: [Shradha Pol](https://www.linkedin.com/in/shradhapolofficial)


## 🤝 Contact
👤 **Shradha Pol**  
- 💼 [LinkedIn](https://www.linkedin.com/in/shradhapolofficial)  
- 📂 [GitHub](https://github.com/shradha-pol)
