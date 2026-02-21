# Coffee Shop Sales Analysis ☕📊

This project performs a comprehensive analysis of sales data for a coffee shop. Using Python and the Pandas library, I processed over 3,500 transactions to extract actionable business insights regarding product performance, peak timing, and revenue trends.

## 📈 Key Insights & Findings
* **Top Seller:** The **Latte** is the most popular item, accounting for **24%** of all transactions.
* **Peak Hours:** The **Afternoon** is the most profitable period, generating **34%** of total daily revenue.
* **Weekly Trends:** **Tuesday** is the busiest day of the week (16% of sales), while **Sunday** is the slowest (11%).
* **Growth Metrics:** Observed a **14% revenue increase in March**, followed by a minor 5% seasonal dip in April.
* **Pricing Strategy:** Identified a consistent **5.88% price increase** across the entire product catalog.

## 🛠️ Data Cleaning & Feature Engineering
To make the data ready for analysis, I performed the following steps:
* **Datatype Correction:** Converted date and time strings into datetime objects for accurate sorting and time-series analysis.
* **Feature Creation:** * Created `Time_of_Day` categories (Morning, Afternoon, Night) to analyze shifting customer behavior.
    * Extracted `Weekday` information to identify peak sales days.
* **Trend Analysis:** Calculated month-over-month growth percentages and price change ratios.

## 💻 Tech Stack
* **Language:** Python
* **Library:** Pandas
* **Tool:** Jupyter Notebook
