# ☕ Coffee Shop Sales Analysis

## 📖 Project Overview
This project performs a comprehensive analysis of sales data for a coffee shop to uncover actionable business insights. Using **Python** and **Pandas**, I processed and cleaned over 3,500 transactions to understand product performance, peak operational hours, and revenue growth trends.

---

## 📂 Dataset Information
* **Source:** [Kaggle](https://www.kaggle.com/)
* **Domain:** Food & Beverage / Retail
* **Data Scale:** 3,500+ Transactional Records

### 📋 Column Glossary
| Column | Description |
| :--- | :--- |
| **Transaction ID** | Unique identifier for each individual sale. |
| **Item** | The specific product sold (e.g., Latte, Tea, Cocoa). |
| **Price** | The unit price of the item (Analyzed for a **5.88%** consistent increase). |
| **Date / Time** | Timestamp of purchase (Converted for time-series analysis). |
| **Time_of_Day** | *Engineered Feature:* Categorized into **Morning, Afternoon, and Night**. |
| **Weekday** | *Engineered Feature:* Used to identify **Tuesday** as the peak sales day. |

---

## 📈 Key Insights & Findings
* **Top Seller:** The **Latte** is the dominant product, accounting for **24%** of all transactions.
* **Peak Hours:** The **Afternoon** is the most profitable period, generating **34%** of total daily revenue.
* **Weekly Trends:** **Tuesday** is the busiest day (16%), while **Sunday** is the slowest (11%).
* **Growth Metrics:** Revenue increased by **14% in March** and **12% in November**.
* **Pricing Strategy:** A uniform price increase of **5.88%** was applied across the entire product catalog.

---

## 🛠️ Data Cleaning & Feature Engineering
Based on the provided Jupyter Notebook, the following technical steps were implemented:
* **Datatype Correction:** Converted date and time strings into proper `datetime` objects.
* **Feature Engineering:** Created `Time_of_Day` and `Weekday` columns to segment sales patterns.
* **Advanced Aggregation:** Created multiple **Pivot Tables** to summarize complex relationships between time, product categories, and revenue.
* **Data Export:** Saved the processed insights into a multi-sheet Excel file (`stocks_weather.xlsx`) for business reporting:
    * `Pro-Month`: Product performance by month.
    * `Tim_mon`: Revenue trends over time.
    * `Tim_Day_mon`: Time-of-day revenue distribution.
    * `Caff_categ`: Sales broken down by coffee category.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Library:** Pandas (Analysis), OpenPyXL (Excel Export)
* **Tool:** Jupyter Notebook

