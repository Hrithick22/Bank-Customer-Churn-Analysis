# 🏦 Bank Customer Churn Analysis

> An end-to-end data analysis project investigating customer churn across **10,000 bank customers** using **MySQL** for analysis and **Excel** for interactive visualization.

---

## 📊 Dashboard Preview

![Dashboard](dashboard/dashboard_preview.png)

---

## 🎯 Project Objective

To identify the key drivers of customer churn in a multinational bank and provide actionable retention recommendations. The analysis segments churn risk across demographics, geography, product holdings, and customer behavior.

---

## 🛠️ Tools & Techniques

| Tool | Purpose |
|------|---------|
| **MySQL 8.0** | Data exploration, segmentation, and statistical analysis (22+ queries) |
| **Microsoft Excel** | Interactive dashboard with slicers, pivot tables, and KPI cards |
| **SQL Concepts** | GROUP BY, HAVING, CASE WHEN, Subqueries, Views, Aggregate functions |

---

## 📈 Key Findings

1. **Germany has 2× the churn rate** of France and Spain (~32% vs ~16%) — despite similar customer count
2. **Customers holding 3 or 4 products churn at 82%+** — counterintuitive finding suggesting product overselling
3. **Complaint flag predicts churn near-perfectly** (~99% correlation) — flag for immediate retention intervention
4. **Inactive members churn at nearly 2× the rate** of active members
5. **Age group 46–60 is the highest-risk demographic** — needs targeted retention campaigns
6. **Female customers churn at a higher rate than male customers** across all geographies

---

## 🗂️ Dataset

- **Source:** Kaggle (Bank Customer Churn Dataset)
- **Size:** 10,000 rows × 18 columns
- **Features:** Demographics (Geography, Gender, Age), Financial (CreditScore, Balance, EstimatedSalary), Behavioral (IsActiveMember, Complain, NumOfProducts), Target (Exited)
- **Quality:** Zero null values, zero duplicates — analysis-ready

---

## 🔍 SQL Analysis Highlights

The SQL portion answers 22 business questions across 3 complexity tiers:

- **Basic exploration:** Customer counts, distributions, averages
- **Segmentation:** Churn rates by Age × Gender × Geography × Product Count
- **Advanced:** Subquery-based benchmarking, HAVING clauses for group-level filtering, CASE-based age bucketing

📄 [View full SQL script](sql/Bank_churn_Analysis.sql)

---

## 📊 Excel Dashboard Features

- **KPI Cards:** Total Customers, Churn Rate, Avg Balance, Avg Credit Score
- **Interactive Slicers:** Geography, Gender, Card Type, Age Group
- **Visualizations:** Churn by country, product holdings, age, activity status
- **Dynamic Filters:** All charts respond to slicer selections

📂 [Download dashboard file](dashboard/Customer_Churn_Dashboard.xlsx)

---

## 💡 Business Recommendations

1. **Launch a Germany-specific retention program** — address the 2× churn anomaly
2. **Audit the "3+ products" customer segment** — identify if overselling is driving exits
3. **Build a complaint-to-retention pipeline** — every complaint flag should trigger a retention call within 24 hours
4. **Re-engage inactive members** before they churn — they're the leading indicator

---

## 📁 Repository Structure

```
bank-customer-churn-analysis/
├── data/                  → Raw dataset
├── sql/                   → MySQL analysis script
├── dashboard/             → Excel dashboard + preview
├── insights/              → Detailed findings document
└── README.md              → This file
```

---

## 👤 About Me

I'm Hrithick, a **Quality Control & Operations Analyst** transitioning into data analytics. My background in cement manufacturing (XRF/XRD, SPC, IS/BIS compliance) gives me a strong foundation in working with measured data, statistical thinking, and process analysis — skills I apply to business analytics problems.

**Skills:** Python (pandas, NumPy, Matplotlib) · SQL (MySQL) · Power BI  · Advanced Excel

📧 **Email:** pandiayaraj2273@gmail.com


---

⭐ *If you found this project useful, please consider giving it a star!*
