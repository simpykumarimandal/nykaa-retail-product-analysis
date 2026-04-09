# 💄 E-commerce Product Analytics Dashboard (Nykaa)

## 📌 Project Overview

This project analyzes product-level data from Nykaa to uncover insights related to pricing strategy, product performance, customer trust, and inventory risks. The goal is to simulate real-world business decision-making using data analytics.

---

## 🎯 Business Objectives

* Analyze the impact of discounts on product ratings and engagement
* Identify high-performing products using a custom Value Score
* Evaluate effectiveness of "Featured" product tagging
* Detect potential revenue loss due to out-of-stock products

---

## 🛠️ Tools & Technologies

* **Excel** → Data cleaning & feature engineering
* **Power BI** → Dashboard creation & visualization
* **DAX** → Measures and calculated insights

---

## 🧹 Data Preparation

Performed data cleaning and transformation in Excel:

* Removed duplicates based on `product_id`
* Handled missing values for rating and pricing fields
* Converted data types for numerical analysis

### 📊 Feature Engineering:

* **Discount %** = (MRP - Price) / MRP
* **Value Score** = (Rating × Rating Count) / Price
* Price Buckets (Low, Medium, Premium)
* Popularity Buckets (Low, Moderate, Highly Popular)
* Rating Categories (Average, Good, Excellent)

---

## 📈 Dashboard Overview

### 🔹 Executive Summary

* Total Products
* Average Rating
* Average Discount
* In-Stock Percentage

### 🔹 Pricing & Discount Insights

* Discount vs Rating scatter analysis
* Price bucket performance comparison

### 🔹 Product Performance

* Top 10 products based on Value Score
* Brand-wise performance analysis
* Product segmentation by rating & popularity

### 🔹 Inventory Risk Analysis

* Out-of-stock product tracking
* High-demand but unavailable products (potential revenue loss)

---

## 🔍 Key Insights

* Products with moderate discounts (~20–40%) show higher engagement
* Several high-rated products are not featured, indicating missed promotion opportunities
* High-demand products with strong ratings are out of stock, leading to potential revenue leakage
* Premium pricing does not always correlate with higher customer satisfaction

---

## 💡 Business Recommendations

* Optimize discount strategies to improve engagement
* Promote high-rated, low-visibility products
* Improve inventory planning for high-demand products
* Re-evaluate criteria for "Featured" product tagging

---



## 🚀 Conclusion

This project demonstrates how data analytics can drive business decisions in e-commerce, particularly in pricing, product positioning, and inventory management.

---
