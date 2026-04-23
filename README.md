# Vendor Performance and Inventory Analysis using Python (EDA)

## 📌 Project Overview

This project focuses on solving a real-world retail business problem using **data cleaning and exploratory data analysis (EDA)**.

The objective is to analyze **vendor performance, procurement patterns, inventory efficiency, and profitability trends** to support better business decision-making.

The analysis was performed using **Python, Pandas, Matplotlib, and Seaborn** on multiple retail datasets.

---

## 🎯 Business Problem

Efficient management of vendors, inventory, and purchasing decisions is essential for maximizing profitability in a retail business.

This project aims to answer key business questions such as:

* Which vendors and brands generate the highest sales?
* Which vendors contribute most to procurement cost?
* Is the business highly dependent on a few vendors?
* Does bulk purchasing reduce unit price?
* Which vendors have slow-moving inventory?
* How much capital is locked in unsold stock?
* Which brands need pricing or promotional adjustments?
* How stable are profit margins across vendors?

---

## 📂 Dataset Files

The project uses multiple datasets:

* `sales.csv`
* `purchases.csv`
* `vendor_invoice.csv`
* `purchase_prices.csv`
* `begin_inventory.csv`
* `end_inventory.csv`

Each dataset represents different aspects of retail operations such as sales, procurement, pricing, and inventory.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Handled missing values
* Removed duplicate records
* Checked and corrected data types
* Standardized column names
* Merged datasets where required
* Validated numerical fields and ensured data consistency

---

## 📊 Exploratory Data Analysis (EDA)

The following business questions were solved during analysis:

### 1. Sales Performance Analysis

* Identified vendors and brands with the highest sales performance
* Detected brands with **low sales but high profit margins**, indicating potential need for pricing or promotional adjustments

### 2. Procurement Analysis

* Determined vendors contributing most to total purchase dollars
* Measured dependency on top vendors

### 3. Cost Optimization Analysis

* Analyzed whether bulk purchasing reduces unit price
* Estimated optimal purchase volume for cost savings

### 4. Inventory Analysis

* Identified vendors with low inventory turnover
* Detected slow-moving and excess stock

### 5. Capital Efficiency Analysis

* Calculated capital locked in unsold inventory per vendor

### 6. Profitability Analysis

* Computed 95% confidence intervals for vendor profit margins

---

## 📈 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Key Insights

* A small number of vendors contribute significantly to total procurement, indicating dependency risk
* Bulk purchasing reduces unit cost up to a certain level, after which benefits may plateau
* Some vendors show slow-moving inventory, leading to excess stock and higher holding costs
* A significant amount of capital is tied up in unsold inventory, impacting cash flow efficiency
* Top-performing vendors exhibit more stable profit margins compared to low-performing vendors
* Certain brands have high profit margins but low sales, indicating opportunities for pricing or promotional optimization

---

## 🚀 Conclusion

This project demonstrates how exploratory data analysis can be used to solve real-world business problems related to **vendor performance, procurement efficiency, inventory management, and profitability**.

The insights generated can help businesses make better decisions in terms of vendor selection, pricing strategies, and inventory control.
