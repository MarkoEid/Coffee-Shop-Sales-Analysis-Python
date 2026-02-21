# ☕ Coffee Shop Sales Analysis

## 📖 Project Overview
This project performs a comprehensive analysis of sales data for a coffee shop to uncover actionable business insights. Using **Python** and **Pandas**, I processed and cleaned over 3,500 transactions to understand product performance, peak operational hours, and revenue growth trends.

---

## 📂 Dataset Information
* **Source:** [Kaggle](https://www.kaggle.com/)
* **Domain:** Food & Beverage / Retail
* **Data Scale:** 3,500+ Transactional Records

### 📋 Column Glossary & Data Dictionary
| Column | Description |
| :--- | :--- |
| **Transaction ID** | Unique identifier for each sale |
| **Item** | The specific coffee or food product sold |
| **Price** | The unit price of the item |
| **Date / Time** | Timestamp of the transaction (used for trend analysis) |
| **Weekday** | *Derived Feature:* The day of the week (Monday-Sunday) |
| **Time_of_Day** | *Derived Feature:* Categorized into Morning, Afternoon, and Night |
| **Revenue Growth** | *Calculated:* Month-over-month percentage change |

---

## 📈 Key Insights & Findings
* **Top Seller:** The **Latte** is the most popular item, accounting for **24%** of all transactions.
* **Peak Hours:** The **Afternoon** is the most profitable period, generating **34%** of total daily revenue.
* **Weekly Trends:** **Tuesday** is the busiest day of the week (16% of sales), while **Sunday** is the slowest (11%).
* **Growth Metrics:** Observed a **14% revenue increase in March**, followed by a minor 5% seasonal dip in April.
* **Pricing Strategy:** Identified a consistent **5.88% price increase** across the entire product catalog.

---

## 🛠️ Data Cleaning & Feature Engineering
To ensure the data was "analysis-ready," the following technical steps were taken:
* **Datatype Correction:** Converted date/time strings into `datetime` objects for time-series sorting.
* **Feature Creation:** * Engineered the `Time_of_Day` column to analyze shifting customer behavior.
    * Extracted `Weekday` information to pinpoint peak staffing requirements.
* **Trend Analysis:** Automated the calculation of month-over-month growth percentages and price-change ratios.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Library:** Pandas (Data Manipulation)
* **Tool:** Jupyter Notebook

---

## 📁 Repository Structure
```text
├── coffee_sales_analysis.ipynb   # Main Jupyter Notebook
├── coffee_sales_data.csv         # Raw Dataset
├── images/                       # Visualization exports
└── README.md                     # Project Documentation
