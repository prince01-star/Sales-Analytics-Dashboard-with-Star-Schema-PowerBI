# 📊 Enterprise Sales & Profit Analytics Dashboard | Power BI

## 🚀 Project Overview

This project delivers an enterprise-level Business Intelligence solution built in Power BI to analyze multi-year sales and profitability data.

The solution integrates **data modeling, Star Schema architecture, DAX measures, and interactive dashboards** to transform raw transactional data into actionable executive insights.

Designed with real-world BI standards, this project demonstrates how organizations can monitor performance, identify revenue drivers, and optimize strategic decisions.

---

## 🎯 Business Problem

Organizations often struggle with:

- Fragmented sales data
- Lack of profitability visibility
- Poor regional performance tracking
- No centralized KPI monitoring
- Limited time-based analysis

This project solves these challenges by creating a scalable analytics framework for leadership decision-making.

---

## 🧠 Solution Approach

The project follows a structured BI workflow:

**Data → Modeling → DAX → Visualization → Insights → Recommendations**

✔ Data Cleaning & Preparation  
✔ Schema Design  
✔ Relationship Modeling  
✔ KPI Development  
✔ Dashboard Engineering  
✔ Business Insight Generation  

---

# ⭐ Data Architecture – Star Schema

## 🔷 Data Model Strategy

A **Star Schema** was implemented to improve query performance, simplify relationships, and support scalable analytics.

The architecture centers around a transactional **Fact table** connected to multiple **Dimension tables**.
<img width="1816" height="797" alt="Screenshot 2026-02-12 150339" src="https://github.com/user-attachments/assets/b4f08500-a9d0-41b9-baa2-4396dffaae1a" />


## 📌 Why Star Schema?

- Faster aggregations  
- Simplified filtering  
- Better report performance  
- Industry-standard BI modeling approach  

---

## 🏗 Schema Structure

### 🔵 Fact Table

### **Sales (Fact Table)**  
Acts as the analytical core containing transactional metrics.

**Key Columns:**
- CustomerID  
- ProductID  
- CampaignID  
- Date  
- Units  
- Unit Price  
- Unit Cost  
- Sales  
- Profit  

👉 Serves as the **single source of truth** for revenue and profitability.

---

### 🟢 Dimension Tables

#### ✅ Customer_Dim
Provides customer-level attributes for segmentation and behavioral analysis.

Columns include:
- CustomerID  
- Name  
- Email  
- ZipCode  

---

#### ✅ Product_Dim
Supports product performance and pricing analytics.

Columns include:
- Product  
- Category  
- Price Category  
- Segment  
- Transaction Category  

---

#### ✅ Address_Dim
Enables geographic intelligence.

Columns include:
- City  
- State  
- District  
- Region  
- Country  

---

#### ✅ Dates (Calendar Table)

Custom-built date table enabling **Time Intelligence**.

Columns include:

- Year  
- Quarter  
- Month  
- Week Number  
- Day of Week  

---

## 🔗 Relationship Design

- One-to-Many relationships from dimensions → fact table  
- Controlled filter direction  
- Eliminated ambiguity  
- Optimized for analytical queries  

👉 This structure ensures **high-performance dashboard rendering.**

---

# 📈 Executive KPI Snapshot

| KPI | Value |
|--------|---------|
| **Total Sales** | **$65.48M** |
| **Total Profit** | **$17.74M** |
| **Transactions** | **536K** |
| **Customers** | **282.6K** |
| **Products** | **173** |

---

# 📊 Dashboard 1 – Sales Analysis
<img width="1771" height="995" alt="Screenshot 2026-02-12 150547" src="https://github.com/user-attachments/assets/caef2d33-6893-45f8-8052-474606212f9a" />

## Key Insights

### ✅ Revenue Seasonality
- **Q2 generated the highest sales (23.6M)**  
- Q4 recorded the lowest performance.

### ✅ Monthly Trend
- April and May are peak revenue months.
- December shows the weakest demand.

### ✅ Weekly Behavior
- Wednesday drives the highest sales.
- Monday underperforms significantly.

### ✅ Pricing Strategy Insight
- High price category contributes **37M**, dominating revenue share.

### ✅ Transaction Distribution
- High-value transactions generate the majority of income.

### ✅ Geographic Analysis
District-level mapping enables identification of strong vs underperforming regions.

---

# 📊 Dashboard 2 – Profit Analysis
<img width="1776" height="997" alt="Screenshot 2026-02-12 150623" src="https://github.com/user-attachments/assets/baa0f80f-9c14-4f79-97c9-9aefe09e5aee" />

## Key Insights

### ✅ Profit Seasonality
- Q2 leads profitability.
- Q4 shows margin compression.

### ✅ Category Profitability
- High price products contribute **10M profit**.
- Low price items generate negligible returns.

### ✅ Customer Segment Insight
Urban customers dominate profit contribution.

### ✅ Operational Insight
Mid-week transactions yield stronger margins than early-week sales.

---

# ⚡ Performance Optimization Techniques

- Implemented Star Schema to reduce query complexity  
- Avoided many-to-many relationships  
- Used a dedicated Date table  
- Built reusable DAX measures  
- Reduced calculated columns  
- Enabled efficient filter propagation  

---

# 🛠 Tools & Technologies

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query (ETL)  
- Data Modeling  
- Interactive Visualizations  

---

# 💼 Business Recommendations

### 🔹 Strategic Actions

✅ Increase inventory before Q2 seasonal spikes  
✅ Promote high-margin products  
✅ Reassess low-price strategy  
✅ Launch campaigns to boost Monday sales  
✅ Focus expansion on high-performing districts  

---

# 🧪 Project Complexity Level

**Intermediate → Advanced BI Project**

Demonstrates capabilities expected from:

✔ Power BI Developer  
✔ Business Intelligence Analyst  
✔ Data Analyst  
✔ Reporting Analyst  

---

# 📂 Repository Structure
enterprise-sales-analytics-powerbi/
│
├── data/
│ └── Sales.csv
│
├── dashboard/
│ ├── Sales.pbix
│ └── Dashboard.pdf
│
├── images/
│ └── star-schema.png
│
└── README.md

---

# 👨‍💻 Author

**Prince Kumar**  
MBA – Business Analytics  
Aspiring Business Analytics | Data Analytics  

---


