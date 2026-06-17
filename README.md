# E-Commerce-Sales-Data-Analysis
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) 
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi) 
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-green) 
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

Analyzed 431K+ e-commerce transactions using Python, Power BI, and Linear Regression to uncover revenue trends, top products, customer insights, and sales performance.

# 🛒 E-Commerce Sales Data Analysis

## 📌 Project Overview
This project analyzes **4.3 lakh+ real e-commerce transactions** from 2019 to uncover revenue trends, top-performing products, best sales days, and country-wise performance — using Python for data cleaning & EDA and Power BI for interactive dashboards.

---

## 🛠️ Tools & Technologies
- **Python** — Data Cleaning, EDA, Visualization (Pandas, NumPy, Matplotlib, Seaborn)
- **Power BI** — Interactive Dashboard with DAX Measures
- **Machine Learning** — Linear Regression (Revenue Prediction, R² = 0.9466)

---

## 📊 Dataset Details
| Feature | Detail |
|---|---|
| Total Transactions | 4,31,000+ |
| Date Range | March 2019 – December 2019 |
| Unique Products | 3,600+ |
| Unique Customers | 4,300+ |
| Unique Countries | 37 |

---

## 🔍 Key Findings

| Insight | Finding |
|---|---|
| 🌍 Top Country by Revenue | **United Kingdom** |
| 📅 Best Sales Month | **November 2019** |
| 🛍️ Best-Selling Product | **Paper Craft Little Birdie** |
| 📆 Best Day of Week | **Sunday** |
| 💰 Total Revenue | **~£50.49 Million** |
| 📦 Total Orders | **~16,000** |
| 👥 Total Customers | **~4,000** |
| 🧾 Average Order Value | **£3,140** |

---

## 📁 Project Structure
```
E-Commerce-Sales-Analysis/
│
├── pr-6-E-commerce_Sales_Data_Analysis.ipynb   # Python EDA Notebook
├── cleaned_data/
│   └── my_cleandata.csv                        # Cleaned Dataset
├── powerbi/
│   └── pro-6-E-Commerce_Sales_Dashboard.pbix  # Power BI Dashboard
└── README.md
```

---

## 📈 Power BI Dashboard Features
![Power BI Dashboard](Screenshot%202026-06-17%20233043.png)
- **Total Revenue by Month & Year** — Line chart showing revenue trend
- **Total Revenue by Country** — World map visualization
- **Top Products by Revenue** — Horizontal bar chart
- **Revenue by Day of Week** — Best and worst performing days
- **KPI Cards** — Total Orders, Total Customers, Avg Order Value, Total Revenue
- **Interactive Filters** — Year, Country, MonthName slicers

---

## 🧹 Data Cleaning Steps (Python)
1. Removed duplicate rows
2. Converted `Date` column to proper datetime format
3. Filled missing values in `TransactionNo` and `CustomerNo`
4. Removed negative quantity rows (product returns)
5. Standardized text columns (strip + lowercase)
6. Added new columns: `Revenue`, `Year`, `Month`, `MonthName`, `DayOfWeek`

---

## 📉 Machine Learning — Revenue Prediction
- **Model:** Linear Regression
- **Accuracy (R²):** 0.9466 (~94%)
- **Key Feature:** Monthly quantity sold predicts revenue with high accuracy

---

## 👩‍💻 About the Analyst
**Pooja Kumari** | Fresher Data Analyst | New Delhi, India
- 🎓 Data Analytics & AI Certification — Ducat Institute, Noida (Feb 2026)
- 🔗 GitHub: [github.com/haru9266](https://github.com/haru9266)
- 🌐 Portfolio: [haru9266.github.io/data-analyst-portfolio](https://haru9266.github.io/data-analyst-portfolio)
- 📧 poojak110059@gmail.com
