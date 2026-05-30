# Olist Sales & Customer Analytics – Case Study

## 1. Background

Olist is an e-commerce platform that connects sellers and customers. The dataset contains multiple tables including orders, customers, products, sellers, and reviews.

The purpose of this project was to analyze how the business is performing and understand what drives sales and customer satisfaction.

---

## 2. Problem

Even though e-commerce platforms generate a lot of data, it’s not always clear:

* What drives repeat purchases
* Which products actually generate most revenue
* How delivery experience affects customer reviews
* Which sellers contribute most to business growth

This project tries to answer these questions using data.

---

## 3. Data Structure

The dataset included multiple related tables:

* Orders
* Order items
* Customers
* Products
* Sellers
* Payments
* Reviews

These were connected using SQL-style joins to build a complete dataset.

---

## 4. Approach

### Step 1: Data cleaning

* Removed missing or inconsistent records
* Fixed date formats
* Handled duplicate entries

### Step 2: Data integration

All tables were combined using SQL joins to build a unified dataset for analysis.

### Step 3: Feature engineering

Created new variables like:

* Delivery time (purchase to delivery date)
* Order value
* Customer repeat behavior
* Delay vs on-time delivery flag

---

## 5. Analysis

### Sales performance

Sales were not evenly distributed. A few categories contributed most of the revenue.

---

### Customer behavior

Most customers were one-time buyers. However, repeat customers showed higher lifetime value.

---

### Delivery impact

Delivery time had a strong relationship with customer reviews. Late deliveries generally received lower ratings.

---

### Seller performance

Some sellers consistently performed better in both volume and customer satisfaction, showing that seller quality matters as much as product quality.

---

## 6. Key findings

* Revenue is concentrated in a few categories
* Delivery delays negatively affect customer satisfaction
* Repeat customers are valuable but limited
* Seller performance is uneven across the platform

---

## 7. Recommendations

* Improve logistics to reduce delivery delays
* Focus on high-performing product categories
* Encourage repeat purchases through loyalty strategies
* Monitor underperforming sellers more closely

---

## 8. Final thoughts

This project gave me a better understanding of how real e-commerce platforms operate behind the scenes.

Working with multiple related tables helped me understand how data engineering and analytics come together in real business environments.

It also improved my ability to think beyond charts and focus on actual business decisions.

---
