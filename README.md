# 📊 SQL Data Analytics Project

End-to-end SQL analytics project demonstrating real-world business analysis patterns using T-SQL.

[![TSQL](https://img.shields.io/badge/SQL-Data%20Analytics-blue?logo=Microsoft-SQL-Server)](https://www.microsoft.com/en-us/sql-server)

## ✨ Project Overview

This repository contains a collection of **T‑SQL scripts for data analytics and reporting**.  
The scripts demonstrate a variety of analytical techniques that are commonly used by **data analysts and BI professionals** when exploring and extracting insights from relational data.

This project is based on a **step‑by‑step guided SQL analytics tutorial by [Data With Baraa](https://www.youtube.com/@DataWithBaraa)**, and uses the datasets provided in the tutorial.

---

## 🛠️ Tools & Technologies

- **Microsoft SQL Server**
- **T-SQL**
- **SQL Server Management Studio (SSMS)**

### 🔎 SQL Techniques Applied

- Aggregations: `SUM()`, `COUNT()`, `AVG()`, `GROUP BY`
- Window Functions: `SUM() OVER()`, `AVG() OVER()`, `LAG()`, `RANK()`
- Time Intelligence: `YEAR()`, `MONTH()`, `DATEDIFF()`, `DATETRUNC()`
- Business Logic & Segmentation: `CASE`, CTEs (`WITH`)
- Reporting: `CREATE VIEW`

---

## 📚 Skills Demonstrated

This project demonstrates:

- Advanced SQL querying techniques  
- Analytics‑oriented SQL patterns  
- Data exploration and reporting logic  
- Use of window functions for advanced metrics  
- Practical business analytics query writing

---

## 📁 What's Inside

The repo includes:

📂 **datasets/** – Raw datasets used for running the SQL analytics scripts  
📂 **scripts/** – T‑SQL scripts demonstrating different analytical techniques

Each script focuses on a specific analytical theme, such as:

- 📈 Changes over time
- 📊 Cumulative metrics
- ⚡ Performance analysis  
- 🔍 Data segmentation
- 🧩 Part‑to‑whole analysis

---

## 📌 How to Use

1. **Restore or import** the provided datasets into Microsoft SQL Server.  
2. Open the SQL scripts in the [`scripts/`](scripts) folder using **SQL Server Management Studio (SSMS)** or another SQL client.  
3. Execute each script to explore analytical patterns and outputs.

Each script is self‑contained and focuses on a specific type of analysis.

---

## 📊 Key Insights

Using structured SQL analysis, the following business patterns were identified:

- 💰 Revenue is concentrated among a small group of top-performing products and customers.
- 🏆 Clear performance tiers exist across products, highlighting high and low revenue contributors.
- 📈 Sales trends vary over time, with measurable growth and fluctuation across months and years.
- 📊 Cumulative analysis reveals overall revenue growth patterns.
- 🔄 Year-over-year comparisons identify products with increasing or declining performance.
- 👥 Customer segmentation (VIP, Regular, New) provides insight into spending behavior and lifecycle value.
- 📑 Consolidated reporting views deliver actionable KPIs such as recency, lifespan, average order value, and monthly revenue.

---

## 📂 Repository Structure

```
sql-data-analytics-project/
├── datasets/                # Raw datasets for analysis
├── scripts/                 # SQL scripts demonstrating analytical queries
├── README.md                # Project overview and usage guide
└── LICENSE                  # MIT License
```

---

## 🎓 Project Inspiration

This repository implements SQL analytics patterns demonstrated in the following videos from **Data With Baraa**:

- **Time Series & Cumulative Metrics in SQL** – guided walkthrough of time-based and cumulative calculations in SQL.  
  [Watch on YouTube](https://www.youtube.com/watch?v=6cJ5Ji8zSDg&list=PLNcg_FV9n7qZ4Ym8ZriYT6WF8TaC2e_R7&index=5)

- **Advanced SQL Analytics Techniques** – covers segmentation, ranking, and analytics queries.  
  [Watch on YouTube](https://www.youtube.com/watch?v=2jGhQpbzHes&list=PLNcg_FV9n7qZ4Ym8ZriYT6WF8TaC2e_R7&index=6&t=15s)

These tutorials guided the development of the analytical scripts included in this repository.

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).

---
## 🌟 About Me

Hi! I'm [Gabriela Yordanova](https://www.linkedin.com/in/gabriela-yordanova-837ba2124/) - a transitioning data analyst with a background in pharmacy and real estate. My previous experience helped me develop strong analytical thinking, attention to detail, and problem-solving skills in fast-paced environments.

I am currently building hands-on projects in SQL, data analytics, and business intelligence, transforming raw data into actionable insights.

I’m actively seeking opportunities to contribute to a data-driven team.

---

*Thank you for exploring this project! Feel free to reuse, modify, or extend these analytics scripts for your own learning or professional growth.*
