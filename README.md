# 🎯 SQL Mini Project – Sales Data Insights  
*Day 14 of #30DaysDataAnalysisBeginnerChallenge*

## 📌 Project Objective  
The goal of this mini-project was to apply core SQL concepts on a real-world-style dataset to extract business insights, practice advanced queries, and prepare for end-to-end data analysis workflows.  

---

## 🗃️ Dataset  
The dataset simulates **sales transactions** and includes the following CSV files:
- Name: 100_Sales_Records.csv
- Source: GitHub Gist
- Records: 100 sales transactions


---

## 🛠️ Tools Used  
- **MySQL** for database creation and querying  
- **Jupyter Notebook** to integrate SQL + Python  
- **SQLAlchemy & ipython-sql** to run SQL inside Jupyter

---

## ✅ Key Concepts Practiced  
The notebook includes examples using:

### 🔹 Aggregations
- Total revenue by country  
- Average revenue per country  
- Revenue per sales representative

### 🔹 Window Functions
- Rank regions by total profit using `RANK()`  
- Assign row numbers with `ROW_NUMBER()`  
- Compare values across rows using `LAG()` and `LEAD()`  

### 🔹 Joins
- `INNER JOIN` between `sales` and `products` for enriched reporting

### 🔹 Subqueries and CTEs
- Nested SELECT statements to extract top-performing orders  
- Common Table Expressions (CTEs) for cleaner modular queries

---

## 📈 Sample Questions Answered
- Which country generated the most revenue?
- Who were the top-performing sales reps?
- What are the top 5 most profitable orders?
- How does average revenue vary by region?

---

## 📚 Learnings & Takeaways  
This project helped solidify SQL fundamentals by applying them in realistic business scenarios. Using **window functions**, **joins**, and **CTEs**, I was able to go beyond basic queries and extract layered insights from the data.

---

