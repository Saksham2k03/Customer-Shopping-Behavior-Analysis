# 🛍️ Customer Shopping Behavior Analysis — SQL (MySQL) + Python + Power BI

An end-to-end **data analytics portfolio project** built to analyze retail customer shopping trends and deliver actionable business insights across **customer segments, purchase behavior, revenue, and loyalty**.
This project focuses on the full analyst workflow — data cleaning, SQL-based business analysis, and professional dashboard design.

---

## 📌 Project Overview

Retailers generate large volumes of transactional data every day. Turning this raw data into **meaningful insights** requires a structured, end-to-end analytics workflow — from cleaning and preparing the data, to querying it for business answers, to visualizing it for stakeholders.

This project addresses key business questions related to **customer segmentation, purchase drivers, loyalty, and category/seasonal trends** using Python, MySQL, and Power BI.

---

## 🎯 Business Objectives

- Understand overall customer purchasing patterns and revenue contribution
- Identify high-value customer segments and repeat-purchase behavior
- Analyze category, seasonal, and discount-driven purchase trends
- Understand the relationship between demographics and spending
- Enable data-driven marketing and retention decisions

---

## 📂 Dataset Overview

The dataset represents **customer-level retail transaction data** and includes:

- Customer demographics (age, gender, location)
- Purchase details (category, item, purchase amount)
- Purchase frequency and subscription status
- Discount and promo code usage
- Payment method and shipping type
- Review ratings

Data is analyzed at the **customer, category, and time-period** level to identify trends and patterns.

---

## 🧱 Project Architecture

The project follows a three-stage analytical pipeline, each serving a specific purpose:

1. **Data Preparation & EDA (Python)** — clean and explore the raw dataset
2. **Business Analysis (MySQL)** — query the cleaned data to answer business questions
3. **Visualization (Power BI)** — present findings through an interactive dashboard

---

## 🔍 Stage-wise Business Explanation

---

### 1️⃣ Data Preparation & EDA — Python

**Purpose**
- Import and clean the raw `customer_shopping_behavior.csv` dataset
- Handle missing values, standardize formats, and engineer features for analysis
- Perform exploratory data analysis to understand distributions and outliers
- Load the cleaned dataset into a MySQL database for querying

**Notebook:** `Customer_Shopping_Behavior_Analysis.ipynb`

**Business Value**
- Ensures downstream SQL and Power BI analysis is based on clean, reliable data

---

### 2️⃣ Business Analysis — MySQL

**Purpose**
Answer specific business questions using SQL against the cleaned dataset loaded into MySQL.

**Key Analysis**
- Revenue and purchase count by customer segment
- Repeat vs. first-time customer behavior
- Category and seasonal purchase trends
- Impact of discounts/promo codes on purchase amount
- Top customers by lifetime spend

**File:** `customer_behavior_sql_queries.sql`

**Business Value**
- Surfaces the specific numbers and segments that drive the dashboard's insights

---

### 3️⃣ Visualization — Power BI

**Purpose**
Present the analysis as an interactive dashboard for stakeholders.

**Key Metrics Displayed**
- Total Revenue / Total Customers / Total Orders
- Average Purchase Value
- Revenue by Category and Season
- Customer segments (new vs. returning, subscribed vs. not)
- Top locations and payment methods by revenue

**File:** `customer_behavior_dashboard.pbix`

**Business Value**
- Enables quick, visual, executive-level decision-making on customer and revenue trends

*![Dashboard](dashboard_screenshot.png)*

---

## 🛠 Tools & Technologies Used

- **Python** (Pandas, NumPy, Matplotlib/Seaborn) — data cleaning & EDA
- **MySQL** — data storage & business-question queries
- **Microsoft Power BI** — dashboard design & DAX calculations
- Data Modeling & Relationships
- KPI Design & Dashboard UX Principles

---

## 📈 Business Impact

This project enables stakeholders to:

- Track customer and revenue performance at a glance
- Identify the highest-value customer segments
- Understand which categories and seasons drive sales
- Evaluate the effectiveness of discounts and promotions
- Make informed, data-driven marketing and retention decisions

---

## 📚 Key Learnings

- End-to-end analytics workflow: Python → SQL → Power BI
- Writing business-oriented SQL queries (joins, aggregations, window functions)
- Migrating a project's database layer from PostgreSQL to MySQL
- Data storytelling and dashboard design for non-technical stakeholders

---

## 🚀 Future Enhancements

- Real-time / scheduled data refresh
- Customer churn prediction
- RFM (Recency, Frequency, Monetary) segmentation
- Predictive sales forecasting

---

## 📂 Repository Structure

```
├── Customer_Shopping_Behavior_Analysis.ipynb   # Data import, cleaning, EDA, MySQL connection
├── customer_behavior_sql_queries.sql           # Business-question SQL queries (MySQL)
├── customer_behavior_dashboard.pbix            # Power BI interactive dashboard
├── customer_shopping_behavior.csv              # Raw dataset
├── Business Problem Document.pdf               # Problem statement & objectives
├── Customer Shopping Behavior Analysis.pdf     # Final written report
├── Customer-Shopping-Behavior-Analysis.pptx    # Stakeholder presentation deck
└── LICENSE
```

---

## 👤 Author

**Saksham**
Aspiring Data Analyst | SQL · Python · Power BI

---

## 📎 Note

This project is created for **learning, portfolio, and demonstration purposes**, adapted from an existing tutorial with the database layer rebuilt in MySQL.

## 🙌 Credits

This project follows the structure and methodology taught by **Amlan Mohanty** in the [original tutorial and repository](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI).

## 📜 License

MIT — see [LICENSE](LICENSE) for details.
