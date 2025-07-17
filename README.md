# Vendor_Performance_Analysis
# 📊 Vendor Performance Analysis

## Project Overview

This project analyzes vendor performance for a retail/wholesale business to help drive strategic decisions in purchasing, pricing, and inventory management. Using a combination of **SQL**, **Python (Pandas, Seaborn, Matplotlib)**, and **Power BI**, we identified key insights to improve profitability, streamline inventory, and reduce vendor-related risk.

![Power BI Dashboard](https://github.com/Harshalpatil9767/Vendor_Performance_Analysis/blob/84a8d9a3912cb9c5744f6606fa95447eb72577e0/Screenshot%202025-07-17%20133621.png)


---

## 📌 Business Objectives

- Identify **underperforming brands** for pricing or promotional adjustment.
- Determine **top-performing vendors** based on sales and profit contribution.
- Analyze **bulk purchasing effects** on unit cost savings.
- Assess **inventory turnover** to reduce holding costs.
- Statistically compare profit margins between **high- and low-performing vendors**.

---

## 🧪 Tools & Technologies

| Tool       | Purpose                      |
|------------|------------------------------|
| SQL        | Data extraction & filtering  |
| Python     | Data cleaning, analysis, visualization |
| Power BI   | Interactive dashboarding     |
| Excel      | Data preparation             |

---

## 🧹 Data Cleaning & Preprocessing

- Removed records with:
  - Negative or zero **gross profit** or **profit margin**.
  - Zero **sales quantity** (unsold inventory).
- Handled extreme outliers in cost and freight.
- Derived metrics:
  - Stock Turnover Ratio
  - Profit Margin %
  - Unit Cost Comparison (bulk vs. retail)

---

## 🔍 Key Insights

### 1. **Top Vendors Dominate Sales**
- Top 10 vendors contribute **65.69%** of total purchases.
- Indicates **over-reliance** and potential supply chain risk.

### 2. **Bulk Purchasing Saves Cost**
- Bulk orders showed **72% lower unit costs** on average.
- Strategic purchasing can **optimize margins** significantly.

### 3. **Slow-Moving Inventory**
- ~$2.71M tied up in unsold inventory.
- Certain vendors show poor stock turnover.

### 4. **Profitability Disparities**
- High-performing vendors: High sales, ~31% profit margin.
- Low-performing vendors: Lower sales, **~41.5% margin**.
- Opportunity to **re-price and re-market** underexposed vendors.

---

## 📈 Correlation Insights

| Relationship                          | Correlation Coefficient |
|---------------------------------------|--------------------------|
| Purchase Price vs Sales Revenue       | -0.012 (very weak)       |
| Purchase Quantity vs Sales Quantity   | **0.999 (very strong)**  |
| Profit Margin vs Sales Price          | -0.179 (moderate)        |
| Stock Turnover vs Profitability       | ~ -0.05 (weak negative)  |

---

## ✅ Final Recommendations

- 📦 **Reprice** slow-moving, high-margin brands to boost sales.
- 🤝 **Diversify vendor base** to reduce dependency risks.
- 💰 Use **bulk discounts** strategically to lower unit costs.
- 🧾 **Clear excess inventory** with sales or optimized purchasing.
- 📢 Improve **marketing and distribution** for low-performing vendors.

---

## 📊 Dashboard (Power BI)

The Power BI dashboard offers interactive visuals:
- Vendor Rankings
- Profit Margin vs Sales
- Inventory Turnover by Brand
- Bulk Purchase Impact Chart



---

## 🧪 Statistical Validation

A two-sample t-test was used to compare profit margins:

- **Result**: Statistically significant difference between high and low-performing vendors.
- **p-value < 0.05**: Reject null hypothesis.

---


