# Restaurant-Sales-Analysis

## Project Overview
You are provided with a quarter’s worth of order data from a fictitious restaurant that serves international cuisine. Each order includes details such as the items purchased, order date and time, and information about the menu items.

The restaurant’s management wants to better understand customer ordering behavior, menu performance, and revenue trends in order to make informed, data-driven business decisions.

As a Data Analyst, my task was to analyze the dataset and present key insights and recommendations using a one-page Power BI dashboard that clearly communicates findings in a simple and actionable way.

## Project Objectives

The goal of this project was to apply data analysis and visualization techniques to transform raw restaurant order data into meaningful business insights. By the end of the project, I:

* Built a clean and accurate data model in Power BI

* Used Power Query to clean, transform, and prepare data for analysis

* Created DAX measures to calculate key business metrics

* Analyzed menu items, cuisines, and time-based performance

* Designed a single-page executive dashboard for decision-makers

* Translated analytical findings into clear business insights and recommendations

## Business Questions Addressed

The Power BI dashboard was designed to answer the following key business questions:

**1.** Which menu items are the most ordered and least ordered?

**2.** Which cuisine categories perform best and worst in terms of orders and revenue?

**3.** What characteristics define the highest-spending orders?

**4.** Are there specific days or times with higher or lower order volumes?

**5.** Which cuisines should the restaurant prioritize for further development and promotion?

**Disclaimer:**
This project was created solely for educational and portfolio purposes. The dataset represents a fictitious restaurant, and the analysis is intended to demonstrate how I apply data analysis and visualization skills learned during my training to solve a real-world business problem.

This project serves as a capstone project completed after my training period and does not reflect real business data or decisions.

## Dataset Description

The dataset used in this project consists of two tables that capture menu information and customer order details for a fictitious restaurant.

### Table 1: `menu_items`
This table contains information about the restaurant’s menu offerings.

- **menu_item_id** – Unique identifier for each menu item  
- **item_name** – Name of the menu item  
- **category** – Cuisine type (e.g., Italian, Asian, Mexican)  
- **price** – Price of the menu item  

### Table 2: `order_details`
This table contains transactional data for customer orders.

- **order_details_id** – Unique identifier for each order line  
- **order_id** – Identifier linking multiple items within the same order  
- **order_date** – Date the order was placed  
- **order_time** – Time the order was placed  
- **item_id** – Foreign key linking to `menu_items.menu_item_id`

- # 🍽 Restaurant Orders Performance Analysis

##  Project Overview

This project analyzes transactional restaurant order data to evaluate sales performance, customer behavior, and category profitability.  
The objective is to uncover actionable insights that can help management optimize revenue, improve operational efficiency, and drive strategic decision-making.

---

#  Executive Summary

The restaurant generated **$73.31K in revenue** from **2,427 total orders**, with an average order value of **$30.21**.  

Sales performance is driven primarily by Asian and Italian cuisines, with strong demand during lunch and early evening hours. However, midweek performance and category revenue imbalance present opportunities for growth and optimization.

---

#  Core Business KPIs

- **Total Orders:** 2,427  
- **Total Revenue:** $73.31K  
- **Total Items Sold:** 5,542  
- **Average Order Value (AOV):** $30.21  

---

# Key Insights & Business Recommendations

---

## 1️⃣ Category Performance Analysis

###  Findings
- Asian cuisine recorded the highest order volume (1,219 orders).
- Italian cuisine generated the highest revenue contribution (31%).
- American category contributed the lowest revenue share (18%).

### Insight
High order volume does not always translate into highest revenue. Italian dishes likely have higher pricing or stronger profit margins.

###  Business Recommendations
- Promote high-margin Italian dishes through targeted marketing.
- Bundle Asian bestsellers with drinks to increase order value.
- Improve positioning and promotion of the American category.

### KPIs to Monitor
- Revenue by Category
- Orders by Category
- Revenue per Order by Category
- Category Profit Margin %

---

## 2️⃣ Top Performing Menu Items

### Findings
Top ordered items:
- Korean Beef Bowl
- Cheeseburger
- Edamame
- Hamburger

### Insight
A small number of menu items are responsible for a large share of total orders, creating revenue concentration risk.

###  Business Recommendations
- Introduce cross-selling strategies (e.g., sides + drinks).
- Promote mid-tier menu items.
- Introduce limited-time specials to diversify demand.

###  KPIs to Monitor
- Top 5 Items Revenue Share %
- Menu Contribution Ratio
- Sales Growth of Low-Performing Items

---

## 3️⃣ Day-of-Week Performance

###  Findings
- Monday recorded the highest order volume.
- Wednesday recorded the lowest performance.

### Insight
Midweek sales underperformance indicates untapped revenue opportunity.

### Business Recommendations
- Launch midweek promotions (e.g., Wednesday specials).
- Introduce loyalty rewards for weekday visits.
- Run targeted discounts during low-traffic days.

### KPIs to Monitor
- Revenue by Day of Week
- Weekday Sales Growth %
- Promotion Conversion Rate

---

## 4️⃣ Hourly Sales Trends

### Findings
Sales peak during:
- Lunch hours (around 12 PM)
- Early evening (5 PM – 7 PM)

Sales decline significantly after 9 PM.

### Insight
The restaurant relies heavily on lunch and early dinner traffic for revenue generation.

### Business Recommendations
- Increase staffing during peak hours.
- Optimize inventory preparation before peak times.
- Introduce late-evening offers to boost slower hours.

### KPIs to Monitor
- Revenue per Hour
- Orders per Hour
- Average Service Time
- Peak Hour Revenue Contribution %

---

# Strategic Opportunities

### Strengths
- Strong category diversity
- Healthy Average Order Value
- Clear peak demand periods

### Opportunities
- Improve midweek performance
- Reduce revenue concentration risk
- Optimize underperforming categories

---

# 🛠 Tools Used

- **Power BI** (Data Modeling, DAX, Dashboard Design)
- **Excel** (Data Cleaning & Preparation)
- **Data Visualization & KPI Development**

---

# 📷 Dashboard Preview

![Restaurant Dashboard](dashboard_screenshot.png)

---

# 🚀 Conclusion

This analysis demonstrates the ability to:

- Translate raw data into actionable business insights  
- Develop performance-driven KPIs  
- Identify operational and revenue growth opportunities  
- Communicate findings clearly to support strategic decisions  



- **





