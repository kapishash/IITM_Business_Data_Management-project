# 📊 Fast Food Sales Analysis and Demand Forecasting

## 📝 Project Overview

This project presents a **data-driven analysis of sales and customer behavior** using historical transaction data from a fast-food outlet. The main objectives were to identify best-selling items, understand time-based sales patterns, and forecast future demand to help optimize inventory, staff deployment, and menu planning strategies.

---

## 🎯 Problem Statements

1. **Limited Visibility into Best-Selling Items**
   No structured approach existed to determine which food items were driving the highest sales and revenue.

2. **No Predictive Mechanism for Demand Forecasting**
   The absence of forecasting limited the business’s ability to prepare for future demand variations.

3. **Lack of Awareness of Time-Based Sales Trends**
   Without clear visibility into peak sales periods, efficient staffing and promotional planning were not possible.

---

## 📦 Dataset

* **Source**: Secondary dataset sourced from [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/rajatsurana979/fast-food-sales-report])
* **Records**: Contains transaction-level data (date, items, quantity, revenue, etc.)
* **Key Columns**: `date`, `item_name`, `quantity`, `transaction_amount`, `staff_gender`

---

## 🧪 Methodology

* **Data Cleaning**: Null values handled, date fields converted, outliers examined using `describe()`.
* **Exploratory Data Analysis (EDA)**: Aggregation, pivoting, and grouping used to analyze sales patterns.
* **Visualization**: Created with `Matplotlib` and `Seaborn` to explore trends.
* **Forecasting**: Implemented **Prophet** model for time-series prediction of top-selling items.

---

## 📈 Key Insights

* **Cold Coffee**, **Sugarcane Juice**, and **Frankie** emerged as the top-selling items.
* **Sandwiches** had the highest revenue, indicating strong per-unit profitability.
* **Sales peaked at night** (7 PM–11 PM) and during festive months like October and January.
* **Male staff handled more orders**, while **female staff generated higher revenue during low-traffic hours**.

---

## ✅ Recommendations

* Prioritize inventory for top items to prevent stockouts.
* Promote high-margin items using combo deals or seasonal pricing.
* Optimize staff scheduling based on traffic and performance trends.
* Use forecast data to plan raw materials and marketing campaigns more effectively.

---

## 🛠️ Tools & Technologies

* `Python`
* `Pandas`, `Matplotlib`, `Seaborn`
* `Prophet` (Time Series Forecasting)
* `Jupyter Notebook`

---

## 📚 Learnings

* Applied BDM theory in real-world sales analysis.
* Gained hands-on experience with EDA, visualization, and time series forecasting.
* Demonstrated how data can directly support better decision-making in small businesses.

---

