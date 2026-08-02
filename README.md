# 📱 Mobile Sales Performance & Time-Intelligence Dashboard

## 📌 Project Overview
This project presents an interactive **Mobile Sales Analytics Dashboard** built using Power BI. The goal of this dashboard is to analyze mobile device sales trends across India, track key performance metrics (KPIs), evaluate customer ratings, and analyze year-over-year revenue performance using advanced Time Intelligence calculations (MTD & SPLY).

---

## 💡 Business Goals & Objectives
- **Sales & Revenue Tracking:** Monitor overall sales volume, total transactions, and average transaction values.
- **Geographic Insights:** Identify key high-performing geographic regions across India.
- **Payment Preference Analysis:** Analyze customer preferences across payment gateways (UPI, Credit Card, Debit Card, Cash).
- **Performance Benchmarking:** Compare current sales performance against Month-To-Date (MTD) targets and Same Period Last Year (SPLY) trends.
- **Customer Satisfaction:** Track customer rating distribution (1 to 5 stars) to assess product satisfaction levels.

---

## 🛠️ Data Architecture & Tech Stack
| Layer | Tool / Technique |
|---|---|
| **Data Source** | Excel Dataset (Kaggle) |
| **ETL & Data Cleaning** | Power Query (handling missing values, standardizing column types) |
| **Data Modeling** | Custom Date/Calendar Table linked with Fact Sales table |
| **Analytics Engine** | Power BI (DAX) |

---

## 📊 Key Dashboard Views

### 1. Main Dashboard View
- **KPI Cards:** Total Sales, Quantity Sold, Total Transactions, and Average Sales Value.
- **Interactive Map:** Visual representation of sales volume across regional Indian cities.
- **Payment Breakdown:** Pie chart analyzing distribution between UPI, Credit Card, Debit Card, and Cash.
- **Product & Rating Analysis:** Bar charts displaying top mobile models (e.g., Vivo S1, Galaxy A51, iPhone SE, OnePlus 8T) and customer review funnels.

### 2. MTD Report (Month-to-Date)
- Dedicated page tracking revenue growth across quarters and years ($20M+ trajectory).

### 3. SPLY Report (Same Period Last Year)
- Advanced time-intelligence view comparing current year sales performance against historical quarters (2022–2024).

---

## ⚡ DAX & Time-Intelligence Techniques
Key DAX patterns implemented in this dashboard include:
- **MTD Calculations:** Tracking cumulative sales within active calendar months.
- **SPLY (Same Period Last Year):** Utilizing `SAMEPERIODLASTYEAR()` and a custom calendar table to compare historical performance.
- **Dynamic KPIs:** Interactive card visuals showing total revenue, units sold, and average metrics.

---

## 🖼️ Dashboard Preview
![Main Dashboard View](Screenshot%202026-07-25%20111413.png)
![MTD Report View](Screenshot%202026-07-25%20111701.png)
![SPLY Analysis View](Screenshot%202026-07-25%20111848.png)



## 👤 Author
**Lovepreet**
Data Coordinator | Aspiring Data Analyst
📍 Targeting Data Analyst / MIS roles in Dubai, UAE
