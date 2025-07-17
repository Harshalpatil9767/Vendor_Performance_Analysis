# 📦 Vendor Performance Analysis

## 💡 Project Motivation

In the retail and wholesale industry, effective vendor management directly impacts profitability, operational efficiency, and customer satisfaction. This project was motivated by the need to:

- Identify the vendors contributing most to profits and sales.
- Optimize pricing and purchasing strategies.
- Reduce losses caused by unsold inventory and poor-performing vendors.
- Build a scalable data-driven approach for vendor evaluation.

---

## 🧠 Project Objective

To evaluate vendor performance using historical purchasing and sales data, leveraging data analysis tools to deliver actionable business insights around profitability, purchasing behavior, and inventory optimization.

---

## 🧰 Features

✔️ Vendor ranking based on sales and profitability  
✔️ Brand-level sales distribution  
✔️ Bulk vs. retail cost analysis  
✔️ Inventory turnover and dead stock detection  
✔️ Statistical comparison of vendor profit models  
✔️ Power BI dashboard for stakeholder presentation

---

## 🚀 Tools & Technologies

| Tool        | Purpose                             |
|-------------|-------------------------------------|
| Python      | Data wrangling, EDA, visualizations |
| SQL (SQLite)| Data extraction from database       |
| Power BI    | Interactive dashboard               |
| Pandas, Seaborn, Matplotlib | Data analysis & plots |
| SciPy       | Hypothesis testing                  |

---

## 📂 Data Source

- **Table Used**: `vendor_sales_summary`  
- **Database**: SQLite (`inventory.db`)
- **Key fields**:
  - Vendor ID, Brand Name
  - Purchase and Sales Quantities
  - Unit Prices, Freight Costs
  - Gross Profit & Profit Margin
  - Stock Turnover Ratio

---

## 🔬 Data Cleaning Strategy

To ensure accurate analysis, the following were removed:
- Rows with zero or negative profit margin
- Products that were never sold (zero sales quantity)
- Transactions with extreme outliers or zero revenue

---

## 📊 Metrics Evaluated

- **Top Vendors by Sales & Profit**
- **Top Brands by Sales**
- **Purchase Share (%) by Vendor**
- **Inventory Turnover**
- **Gross Profit & Margin**
- **Bulk vs Retail Cost Comparison**

---

## 🔍 Exploratory Data Analysis

### 📊 Summary Statistics

![Summary Statistics](https://github.com/Harshalpatil9767/Vendor_Performance_Analysis/blob/00ceed5e578aadae738025a65e53cac8ac7d323f/EDA_Stat.png)

---

## 🛍️ Sales Performance

### 🏆 Top 10 Vendors by Sales and top 10 Brands by sales

![Top 10 Vendors by Sales](https://github.com/Harshalpatil9767/Vendor_Performance_Analysis/blob/4fb6725989619d838660733c19b876a1a938b62e/output.png)


## 📦 Purchase Contribution

### 🧮 Top 10 Vendors by Purchase Share (%)

This chart shows dependency on top suppliers and guides procurement diversification.

![Top 10 Purchase Contribution](https://github.com/Harshalpatil9767/Vendor_Performance_Analysis/blob/83e58145cc842916c4127b3fe833f6a5e6b9e39a/output2.png)

---

## 📈 Dashboard View (Power BI)

The Power BI dashboard offers a stakeholder-ready visualization layer with filters and slicers to explore:
- Vendor-level sales and profit
- Inventory and pricing metrics
- Bulk discount trends

![Power BI Dashboard](https://github.com/Harshalpatil9767/Vendor_Performance_Analysis/blob/e1a86cc42b018c8f12142c4eabfa2ac9b4e12bda/Screenshot%202025-07-17%20133621.png)

---

## 📌Learnings from This Project

- How to connect SQL data into Python and Power BI workflows
- Cleaning and filtering real-world business data
- Visualizing large datasets for business storytelling
- Using statistics to validate business hypotheses
- Communicating insights with dashboards and documentation

---

## ✅ Key Insights

- **66%** of all purchases come from just 10 vendors (concentration risk).
- Vendors ordering in bulk save **~72% per unit**, enhancing margins.
- ~$2.71M in inventory was unsold — calling for better demand forecasting.
- Low-performing vendors showed high margins but insufficient sales — marketing or pricing inefficiencies.
- **p-value < 0.05** from t-test confirms significant margin differences between vendor groups.

---

## THANK YOU

