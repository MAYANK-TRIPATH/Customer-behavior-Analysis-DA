# Customer Shopping Behavior Analysis

## DashBoard
<img width="854" height="499" alt="Dashboard" src="https://github.com/user-attachments/assets/fcd711d8-6af7-4621-9668-b2e5ef2b166a" />

## Overview

This project focuses on analyzing customer shopping behavior using retail transaction data to understand what drives purchasing decisions and revenue.

The aim was not just to explore data, but to answer a practical business question:

**How can a retail company use customer data to improve sales, engagement, and long-term loyalty?**

---

## Business Problem

A retail company observed changing patterns in how customers shop across:

* Product categories
* Demographics
* Discounts and promotions
* Online vs offline behavior

The company wanted to understand:

* What factors influence customer purchases
* Which customers contribute the most to revenue
* How to improve repeat purchases and engagement

---

## Data Summary

* ~3,900 transactions
* 18 features

Key data includes:

* Customer details (age, gender, location, subscription status)
* Purchase behavior (category, amount, season, frequency)
* Engagement factors (discounts, reviews, shipping type)

---

## Approach

### 1. Data Preparation (Python)

* Cleaned and structured the dataset using Pandas
* Handled missing values in review ratings using category-wise median
* Standardized column names
* Created new features:

  * Age groups
  * Purchase frequency
* Removed redundant columns (promo code vs discount)

---

### 2. Data Analysis (SQL)

Used SQL to answer real business questions such as:

* Revenue contribution by gender
* Impact of discounts on high-spending customers
* Top-rated and best-performing products
* Spending behavior across shipping types
* Subscribers vs non-subscribers comparison
* Customer segmentation (New, Returning, Loyal)
* Revenue distribution across age groups
* Repeat purchase behavior and subscription trends

---

### 3. Visualization (Power BI)

Built a dashboard to highlight:

* Revenue distribution
* Customer segments
* Product performance
* Behavioral patterns

---

## Key Insights

* A small group of repeat customers contributes a large portion of revenue
* Discounts drive purchases but are also linked with high-spending customers
* Certain products consistently receive higher ratings and should be promoted
* Subscribers show better engagement and spending patterns
* Customers with higher purchase frequency are more likely to convert into loyal users
* Age groups contribute differently to revenue, enabling targeted strategies

---

## Business Recommendations

* Promote subscription plans to improve repeat purchases
* Build loyalty programs to convert returning customers into loyal customers
* Optimize discount strategy to balance revenue and margins
* Highlight top-rated and high-performing products in marketing campaigns
* Use targeted marketing based on age group and purchase behavior

---

## Tools Used

* Python (Pandas)
* SQL (PostgreSQL)
* Power BI

---

## What This Project Demonstrates

* Ability to work with structured retail data
* Strong SQL-based business analysis
* Understanding of customer segmentation and behavior
* Translating data into actionable business insights

---

## Final Note

This project focuses on practical business analysis rather than complex modeling, reflecting how real-world data analysts approach customer behavior problems.


