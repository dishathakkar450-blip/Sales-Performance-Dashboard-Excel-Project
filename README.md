# 📊 Sales Performance Dashboard | Excel Project

An interactive **Excel dashboard** built end-to-end: from a messy raw dataset to cleaned data, summary tables, advanced formulas, charts and a filterable dashboard. Built as my **Final Practical Exam** project in Data Analysis with Excel.

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Focus](https://img.shields.io/badge/Focus-Data%20Analysis%20%7C%20Dashboarding-blue)

---

## 🎯 Project Overview

The goal was to take a retail sales dataset, clean it, analyse it, and present the results in a single dashboard that a manager can filter and read in seconds.

**The dashboard answers:**
- 💰 How much did we sell, and how profitable were we?
- 🌍 Which regions, categories and customer segments perform best?
- 📅 How do sales change month by month?
- 🏆 Which products drive the most revenue?

---

## 📸 Preview

> Add your screenshots to an `images/` folder and update the paths below.

| Dashboard | Cover Page |
|---|---|
| ![Dashboard](images/dashboard.png) | ![Cover](images/cover.png) |

---

## 🔑 Key Results (sample data)

| Metric | Value |
|---|---|
| 💰 Total Sales | ₹65,14,241 |
| 📈 Total Profit | ₹12,65,564 |
| 🧾 Orders | 294 |
| 🛒 Average Order Value | ₹22,157 |
| 📊 Profit Margin | 19.4% |

**Insights found:**
- 🏆 **Technology** brings in about **71%** of total sales; **Laptop** is the top product, followed by **Smartphone** and **Monitor**.
- 🌍 **North** is the strongest region (~29.5% of sales); **South** is the weakest (~21.3%).
- 📅 **October** is the peak month (₹11.3L) and **April** is the lowest (₹1.98L).
- 👥 **Consumer** is the largest customer segment, followed by Corporate and Home Office.

> ⚠️ The dataset is a **generated sample** (300 orders, year 2025) created to mimic a Kaggle-style retail sales file, so these insights show the method and do not describe a real business.

---

## ✨ Features

- 🎛️ **Interactive dashboard**: dropdown filters for Region, Category and Segment update every KPI, table and chart instantly
- 🧹 **Data cleaning log**: formula-driven counts of duplicates, blanks and fixes
- 📊 **Summary tables** built with `SUMIFS` / `COUNTIFS` that refresh automatically
- 🧮 **Advanced formulas**: `VLOOKUP`, `INDEX-MATCH`, nested `IF`, `IFERROR`, `SUMPRODUCT`
- 📈 **10 charts**: line, bar, column, pie, clustered, horizontal bar
- 🎨 **Conditional formatting**: data bars, colour scales, icon arrows, top/bottom highlights
- 📏 **Dynamic named ranges** (`OFFSET` + `COUNTA`) so formulas grow as data grows
- 📝 **Documentation sheet** covering naming conventions, assumptions and how-to

---

## 🗂️ Workbook Structure

| Sheet | Purpose |
|---|---|
| 🏠 Cover | Project title, author details, clickable contents |
| 📺 Dashboard | KPI cards, filters and 4 live charts |
| 📋 Instructions | Exam rules |
| ✅ Tasks | 7 tasks with time estimate and weightage |
| 📥 Raw_Data | Original messy data (312 rows) |
| 🧹 Clean_Data | Cleaned data (294 rows) with calculated columns and cleaning log |
| 📊 Pivots | Region, Category × Region, Monthly, Product and Segment summaries |
| 🧮 Formulas | Lookup demos, region scorecard and other functions |
| 📈 Charts | Six supporting charts |
| 📝 Documentation | Assumptions, conventions and how-to |

---

## 🧹 Data Cleaning Steps

| Issue in raw data | Count | Fix |
|---|---|---|
| Duplicate Order IDs | 12 | Removed |
| Blank Region | 6 | Rows dropped |
| Missing Quantity | 11 | Filled with product median |
| Missing Discount | 13 | Set to 0% |
| Inconsistent Region text (case/spaces) | – | `TRIM` + proper case |
| Dates and quantities stored as text | – | Converted to real dates and numbers |

**Result:** 312 raw rows → **294 clean rows**.

**Calculated columns:** `Sales = Qty × Unit Price × (1 − Discount)` · `Profit = Sales × Margin %` · `Month` from the order date.

---

## 🛠️ Skills Demonstrated

`Data Import` · `Data Cleaning` · `Summary Tables` · `Lookup Functions` · `Conditional Logic` · `Named Ranges` · `Charts` · `Conditional Formatting` · `Dashboard Design` · `Documentation`

---

## 🚀 How to Use

1. Download `Sales_Performance_Dashboard_Excel_Project.xlsx` from this repository.
2. Open it in **Microsoft Excel** (or upload to Google Sheets).
3. Go to the **📺 Dashboard** sheet.
4. Use the yellow dropdowns (Region, Category, Segment) to filter the data.
5. To test with your own data, paste it into **🧹 Clean_Data** using the same columns. The tables and charts update automatically.

> 💡 In Windows Excel, emoji inside cells can show in black and white. They appear in colour in Google Sheets, Excel for Mac and mobile.

---

## 👩‍💻 Author

**Disha Thakkar**
🆔 GR ID: 12782
📅 October 2026

- 🔗 LinkedIn: *add your link*[Sales-Performance-Dashboard-Excel.](url)
- 💻 GitHub: *add your link*!

---

⭐ If you found this project useful, consider giving the repo a star
