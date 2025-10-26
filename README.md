# 💳 Credit Card Financial Dashboard  

### 📊 Project Overview  
This project analyzes **credit card transaction and customer data** to uncover key financial insights such as spending patterns, revenue performance, and customer segmentation.  
The final deliverable is an **interactive Power BI dashboard** that provides a 360° view of business performance for decision-makers in the financial domain.  

---

### 🧠 Objective  
To design and develop a **comprehensive Power BI dashboard** that helps visualize and track:  
- Total and category-wise revenue  
- Customer demographics and spending habits  
- Monthly and yearly growth trends  
- High-value customers and active card usage  

---

### 🧰 Tools & Technologies Used  

| **Category** | **Tools / Technologies** |
|:-------------:|:-------------------------|
| Data Cleaning & Preparation | SQL, Power Query |
| Data Analysis | DAX, Power BI |
| Visualization | Power BI |
| File Format | CSV |
| Report Export | PDF |

---

### 🗂️ Dataset Description  

**Source:** Synthetic dataset (created for educational & analytical purposes).  

**Tables Used:**  

| **Table Name** | **Description** |
|:---------------|:----------------|
| `Customer.csv` | Contains customer demographic details like age, gender, income group, and marital status. |
| `Cust_Address.csv` | Includes city, state, and country details for each customer. |
| `Credit_Card.csv` | Provides credit card details and spending categories. |
| `Transaction.csv` | Contains transaction IDs, amounts, payment methods, and transaction dates. |

Each table was connected using **Customer ID** as a key field to build a **Star Schema** data model.

---

### 🔄 Data Preparation Workflow  

1. **Data Connection:** Imported all four CSV files into Power BI via SQL Database.  
2. **Data Cleaning:** Removed duplicates, handled missing values, and standardized field names.  
3. **Data Transformation:** Merged datasets and created relationships between tables.  
4. **Data Modeling:** Defined calculated measures using DAX (e.g., total revenue, spend per customer, active card users).  
5. **Dashboard Creation:** Designed interactive visuals for revenue trends, customer overview, and transaction insights.  

---

### 📈 Key KPIs & Metrics  

- **Total Revenue**  
- **Average Transaction Value**  
- **Year-to-Date Revenue Growth (%)**  
- **Active Customers Count**  
- **Revenue by Category / State / Month**  

---

### 🖼️ Dashboard Preview  

| **Dashboard Section** | **Preview Image** |
|:----------------------:|:-----------------:|
| Customer Insights | ![Customer Insights](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Customer_Snapshot.jpg) |
| Transaction Analysis | ![Transaction Analysis](https://github.com/shradha-pol/Credit_Card_Financial_Dashboard/blob/main/Credit_Card_Report-Transaction_Snapshot.jpg)
  
 |

> 💡 *Tip: Place your actual Power BI screenshots in a folder named `images/` inside the repo and rename them to match the above image names.*

---

### 💡 Insights & Findings  

- **Top 10% of customers** contribute to nearly **45% of the total revenue.**  
- **Online transactions** show a steady **month-on-month increase of 12–15%.**  
- **Dining, travel, and entertainment** categories drive the highest spending.  
- **Most active customer age group:** 30–45 years with high annual income range.  

---

### 🚀 Business Impact  

This dashboard empowers financial and business teams to:  

- Identify high-value customers and target retention offers.  
- Track revenue growth and spending patterns across demographics and categories.  
- Optimize marketing and promotional campaigns based on customer insights.  
- Monitor performance KPIs in near real-time for data-driven decision-making.  

---

### ⚙️ How to Use  

1. **Clone this repository:**  
   ```bash
   git clone https://github.com/shradha-pol/Credit_Card_Financial_Dashboard.git
