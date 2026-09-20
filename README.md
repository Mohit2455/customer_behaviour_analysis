# customer_behaviour_analysis
End-to-end customer behavior analysis of 3.9K customers using Python, SQL, and Power BI. Covers data cleaning, manipulation, and an interactive dashboard on revenue, sales, subscriptions, and demographics.


# Customer Behavior Dashboard

An end-to-end data analytics project that analyzes customer purchasing behavior to uncover revenue, sales, subscription, and demographic insights. The project covers the full workflow: **data cleaning in Python, data manipulation in SQL, and an interactive dashboard in Power BI.**

---

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Tools & Technologies](#tools--technologies)
- [Project Workflow](#project-workflow)
- [Dashboard Overview](#dashboard-overview)
- [Key Metrics](#key-metrics)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)

---

## Project Overview

Understanding how customers buy is essential for growing revenue and retaining customers. This project analyzes a customer dataset of roughly **3.9K customers** to answer questions such as:

- Which product categories drive the most revenue and sales?
- Which age groups contribute the most to the business?
- How many customers have an active subscription?
- How satisfied are customers, based on their review ratings?

The results are presented in a clean, easy-to-read Power BI dashboard that decision-makers can use to spot trends and opportunities quickly.

---

## Objectives

- Clean and prepare raw customer data for analysis
- Use SQL to aggregate and extract business-relevant metrics
- Analyze revenue and sales performance by **product category** and **age group**
- Measure the **subscription rate** among customers
- Summarize customer satisfaction through **average review rating**
- Build an interactive dashboard that presents findings clearly
- Provide actionable recommendations based on the data

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** (Pandas, NumPy) | Data cleaning, preprocessing, and feature preparation |
| **SQL** | Data manipulation, filtering, and aggregation |
| **Power BI** | Interactive dashboard and data visualization |

---

## Project Workflow

### 1. Data Cleaning & Preprocessing (Python)
- Loaded and inspected the raw dataset
- Checked for missing values, duplicates, and inconsistent entries
- Standardized column names and corrected data types
- Created derived fields such as **age groups** (e.g., Young Adult, Middle Adult) for demographic analysis
- Exported the cleaned dataset for further analysis

### 2. Data Manipulation & Aggregation (SQL)
- Loaded the cleaned data into a SQL database
- Wrote queries to calculate:
  - Total customers, average purchase amount, and average review rating
  - Revenue and sales volume by product category
  - Revenue and sales volume by age group
  - Subscription status distribution

### 3. Visualization (Power BI)
- Connected Power BI to the cleaned and aggregated data
- Designed charts and KPI cards to present key findings
- Structured the dashboard so that insights are easy to read at a glance

---

## Dashboard Overview

The dashboard includes the following views:

| Section | Description |
|---------|-------------|
| **Key Metrics at a Glance** | KPI cards for total customers, average purchase, and average review rating |
| **Subscription Status** | Donut chart showing subscribers vs. non-subscribers |
| **Revenue by Category** | Bar chart comparing revenue across Clothing, Accessories, Footwear, and Outerwear |
| **Sales by Category** | Bar chart comparing sales volume across product categories |
| **Revenue by Age Group** | Revenue comparison between Young Adult and Middle Adult customers |
| **Sales by Age Group** | Sales volume comparison between Young Adult and Middle Adult customers |
| **Key Takeaways** | Summary of the most important insights |


---

## Key Metrics

| Metric | Value |
|--------|-------|
| **Total Customers** | ~3.9K |
| **Average Purchase Amount** | $59.76 |
| **Average Review Rating** | 3.75 |
| **Active Subscribers** | 27% |
| **Non-Subscribers** | 73% |

---

## Key Insights

### 1. Clothing dominates the business
Clothing is the top category in both **revenue (~$100K)** and **sales volume**. Revenue by category follows this order: Clothing > Accessories > Footwear > Outerwear. Clothing earns roughly **5× the revenue of Outerwear**.

| Category | Revenue |
|----------|---------|
| Clothing | ~$100K |
| Accessories | ~$70K |
| Footwear | ~$40K |
| Outerwear | ~$20K |

### 2. Young Adults are the strongest customer segment
Young Adults generate higher revenue (**$80K**) than Middle Adults (**$60K**) and also lead in sales volume.

### 3. Subscription is a major growth opportunity
Only **27%** of customers have an active subscription, while **73%** do not. Converting even a small share of non-subscribers could noticeably improve customer retention and recurring revenue.

### 4. Customer satisfaction is moderate
An average review rating of **3.75** suggests customers are generally satisfied, but there is room to improve the customer experience.

---

## Business Recommendations

- **Double down on Clothing:** keep investing in the best-performing category through better inventory, promotions, and new arrivals.
- **Grow underperforming categories:** run targeted campaigns or bundles to lift Footwear and Outerwear.
- **Target Young Adults:** tailor marketing, offers, and product mix toward the highest-revenue age group.
- **Boost subscriptions:** introduce subscriber-only discounts, early access, or loyalty rewards to convert the 73% of non-subscribers.
- **Improve satisfaction:** analyze low-rated purchases to identify product or service issues and raise the average rating.



---

⭐ If you found this project useful, consider giving it a star!
