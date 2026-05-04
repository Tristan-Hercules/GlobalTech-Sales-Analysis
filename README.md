# 📊 GlobalTech Sales Analysis (Module 9 Assignment)

## 📌 Overview

This project is part of a data analysis assignment using **Python**, **Pandas**, and **NumPy**. It simulates and analyzes quarterly sales data for a fictional company, **GlobalTech**, to generate meaningful business insights.

The program processes sales data, performs exploratory analysis, and outputs a structured business report.

---

## 🎯 Objectives

* Load and explore dataset using Pandas
* Perform data cleaning and inspection
* Analyze sales performance across regions and categories
* Evaluate promotion effectiveness
* Identify trends and key business insights
* Generate a formatted sales report

---

## 🛠️ Technologies Used

* Python 3
* Pandas
* NumPy

---

## 📂 Dataset

The dataset is **simulated using a CSV string** (no external file required). It includes:

* Date
* Region
* Store
* Category
* Product
* Units Sold
* Unit Price
* Total Sales
* Promotion Status

---

## 🚀 Features & Analysis

### 1. Data Exploration

* View dataset structure (`head`, `info`, `describe`)
* Identify data types and summary statistics
* Check dataset shape

### 2. Key Metrics

* Total Units Sold
* Total Revenue
* Average Unit Price

### 3. Data Filtering

* Sales in North America
* High-volume transactions (>20 units)
* Promotions on specific products (e.g., PhoneX)
* Monthly filtering (February sales)

### 4. Grouped Analysis

* Best-performing product (by revenue)
* Sales by region
* Average units sold by category

### 5. Promotion Analysis

* Average sales (with vs without promotion)
* Total revenue from promotions
* Comparison of promotional effectiveness

### 6. Data Quality Check

* Missing values count
* Missing value percentages

### 7. Advanced Insights

* Top-performing category per region
* Average price by category
* Revenue contribution by product (%)

---

## 📈 Sample Output

The program generates a structured report:

```
============================================================
GLOBALTECH Q1 2024 SALES ANALYSIS REPORT
============================================================

Overall Performance:
- Total Revenue: $XXX,XXX.XX
- Total Units Sold: XXXX
- Average Sale Value: $X,XXX.XX

Regional Performance:
North America: $XXX,XXX.XX
Europe: $XXX,XXX.XX
...

Category Performance:
Smartphones: Avg Units: XX.X, Avg Price: $XXX.XX
...

Promotion Effectiveness:
- Promoted Items Avg Sale: $X,XXX.XX
- Non-Promoted Items Avg Sale: $X,XXX.XX

Data Quality Report:
- Missing Values Found: [...]
- Total Missing Entries: X
```

---

## 💡 Key Business Insights

* High-performing products like **PhoneX** drive major revenue
* Certain regions (e.g., North America) dominate sales performance
* Promotions can significantly impact revenue outcomes
* Data quality issues (missing values) should be addressed

---

## 📌 Recommendations

1. Increase promotions on top-selling products
2. Expand operations in high-revenue regions
3. Improve data collection to reduce missing values

---

## ▶️ How to Run

1. Install dependencies:

```bash
pip install pandas numpy
```

2. Run the script:

```bash
python sales_analysis.py
```

---

## 📎 Notes

* No external dataset is required
* All data is generated within the script using `StringIO`
* Designed for learning and demonstration purposes

---

## 👨‍💻 Author

Created as part of a **Data Analysis with Pandas** assignment.

---


