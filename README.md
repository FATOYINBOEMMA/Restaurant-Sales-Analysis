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


