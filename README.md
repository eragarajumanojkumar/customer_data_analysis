# Customer_data_analysis
A complete customer analytics project using SQL, Power BI, Excel &amp; Orange Data Mining. It analyzes demographics, revenue contribution, product category performance, payment behavior &amp; shopping mall trends. Includes interactive dashboards, predictive modeling with Linear Regression and business recommendations for improving sales performance.
# Power BI · SQL · Excel · Machine Learning

This project analyzes customer shopping behavior data collected from 10 major malls in Istanbul (2021–2023).  
Using SQL, Excel, Power BI, and Orange Data Mining, the project reveals **who buys more**, **when they buy**,  
**what products they prefer**, and **how much revenue they generate** — helping retail businesses make  
data-driven decisions.

---

## Project Objectives

Analyze customer demographics (Gender & Age)  
Understand product category performance  
Identify top revenue-generating customer segments  
Study preferred payment methods  
Create an interactive Power BI dashboard for business insights  
Build a Machine Learning model to predict revenue  
---

##  Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning & preparation |
| MySQL | Data storage & SQL queries |
| Power BI | Dashboard and interactive insights |
| Orange (ML) | Regression model, predictions |
| PowerPoint/PDF | Report & presentation |

---

##  Dataset Description

Each row represents a shopping transaction.  
Main columns:

- Invoice Number  
- Customer ID  
- Gender  
- Age  
- Category (Clothing, Cosmetics, Technology, etc.)  
- Quantity  
- Price  
- Payment Method (Cash, Credit, Debit)  
- Shopping Mall  
- Invoice Date  
- Total Revenue (Quantity × Price) → Added by us

Additional feature created: **Age Group**

---

##  Business Questions Answered

1️.Shopping distribution by **Gender**  
2️.Which gender **buys more** products?  
3️.Which gender **generates more revenue**?  
4️.Category performance by **Gender, Age & Payment Mode**  
5️.Age-wise shopping distribution  
6️.Top age group for **quantity & revenue**  
7️.Payment adoption behavior  
8️.Shopping Mall performance  
9️.Power BI visualization & insights  
10.Retail Recommendations & Conclusions  

---

## Key Insights

 **Female customers contribute ~60%** of total sales & revenue  
 Age groups **21–30** & **31–40** drive the highest purchases  
 **Clothing** is the most purchased category  
 **Cash** is the most used payment method, then Credit Card  
 A few malls significantly outperform others in revenue  
 Price × Quantity is highly predictive of revenue  

---

##  Predictive Modeling (Machine Learning)

Model: **Linear Regression**  
Tool: **Orange Data Mining**

| Metric | Score |
|--------|------|
| R² Score | **0.981 (98.1% Accuracy)** |
| MSE | Very low error |

 The model can reliably forecast future revenue.


---

##  Power BI Dashboard Includes

- KPI Cards (Revenue, Quantity, Transactions)
- Gender insights
- Age group performance
- Category breakdown
- Payment method analysis
- Shopping Mall revenue comparison

---

##  Sample SQL Query

```sql
SELECT gender,
       SUM(quantity * price) AS total_revenue
FROM customer
GROUP BY gender;


##  Project Structure

