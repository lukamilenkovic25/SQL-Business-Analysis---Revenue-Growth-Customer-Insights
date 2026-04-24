# SQL_Business_Analysis-Revenue_Growth_Customer_Insights

## Project Overview
This project presents a comprehensive SQL‑based business analysis designed to answer real‑world commercial questions using transactional data. The analysis focuses on revenue performance, year‑over‑year growth, customer concentration, product drivers, and customer retention. All queries are written using SQLite‑compatible SQL, demonstrating the ability to adapt enterprise‑level analytics logic to different SQL dialects.

---

## About Me
I am a Data Analyst with a strong focus on SQL and Power BI, specializing in business‑oriented analytics and decision support. My work emphasizes clean data preparation, robust data modeling, and KPI development, transforming raw and often inconsistent data into clear, actionable insights. I enjoy working end‑to‑end — from data cleaning and analytical SQL logic to well‑structured Power BI dashboards designed for management and business users.

---

## Business Questions Addressed
- How does revenue evolve over time on a monthly basis?
- How concentrated is revenue across the customer base (Pareto 80/20)?
- How fast is the business growing year‑over‑year?
- Which products are driving growth versus decline?
- What percentage of customers are repeat buyers versus one‑time buyers?

---

## Dataset Structure
The analysis is based on a realistic transactional schema:
- **customers** – customer master data with segment and country attributes
- **products** – product catalog with categories and pricing
- **orders** – order‑level transactions with order status and date
- **order_items** – line‑item level financial data (quantity, discounts, revenue, cost, profit)
The dataset includes tens of thousands of transactions, allowing for meaningful aggregation and growth analysis.

## Analysis Workflow
All SQL logic is contained in a single, well‑structured analysis.sql file using a step‑by‑step approach:
- **Step 1**: Monthly revenue trend analysis
- **Step 2**: Customer revenue and Pareto (80/20) concentration analysis
- **Step 3**: Year‑over‑year revenue growth (monthly, absolute and percentage)
- **Step 4**: Product‑level YoY growth and decline drivers
- **Step 5**: Customer retention and repeat‑purchase behavior analysis
Each step includes business‑oriented comments explaining the purpose and interpretation of the analysis.

---

## Key SQL Techniques
- SQLite (SQL analytics & data preparation)
- Multi‑table joins across transactional and dimension tables
- Common Table Expressions (CTEs) for readable, layered logic
- Window functions for cumulative and ranking analytics
- Time‑based analysis using SQLite date functions
- Business‑focused aggregations and classifications
 
---

## Business Value
- Identifies revenue trends and volatility patterns
- Highlights customer concentration and associated risk
- Isolates products driving growth or decline
- Quantifies customer retention and repeat behavior
- Demonstrates SQL skills aligned with real business decision support

---

## Contact ##
- LinkedIn: https://www.linkedin.com/in/luka-milenkovic-74768a285
- Email: m.milenkovicluka@gmail.com 
- GitHub: https://github.com/lukamilenkovic25
