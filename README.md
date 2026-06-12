# Supply-Chain-Analysis

## Supply Chain Analysis Dashboard using Power BI and Python

## Project Overview

This project presents a complete supply chain diagnostic analysis for a consumer goods company operating across India. The analysis covers **100 SKUs** across three product categories — **Skincare, Haircare, and Cosmetics** — spanning **5 major Indian cities** and **5 suppliers**.

The goal is to identify revenue patterns, supplier performance gaps, quality control issues, and logistics cost inefficiencies using **Power BI** for visualization and **Python (Pandas)** for data cleaning and exploratory data analysis (EDA).

**Project ID:** CDACL-003
**Tool:** Power BI Desktop + Python
**Dataset:** 100 Rows × 24 Columns
**Region:** India | FY 2024

---

## 🎯 Business Problem

A consumer goods company faces several critical supply chain challenges:

* 36% of products failed quality inspection, indicating a systemic quality control issue.
* Average defect rate is 2.28%.
* 76% of SKUs fall into Average or Poor quality categories.
* Route B costs 22.7% more than Route A, increasing logistics expenses.
* Shipping delay rate stands at 17%, affecting customer satisfaction.
* Skincare products generate the highest revenue but remain understocked.

---

## 📊 Dashboard Preview
<img width="1328" height="748" alt="Supply Chain Analysis Dashboard" src="https://github.com/user-attachments/assets/e2c05eb3-eed5-41f2-b92b-e3ce3081d235" />



### Supply Chain Analysis Dashboard

The dashboard includes:

* 5 KPI Cards (Revenue, SKUs, Defect Rate, Lead Time, Inspection Fails)
* Revenue by Product Type (Bar Chart)
* Top Locations by Revenue (Ranked Horizontal Bar Chart)
* Transportation Modes Distribution (Donut Chart)
* Supplier Performance Table with Conditional Formatting
* Quality Tier Breakdown
* Inspection Results Analysis
* Customer Demographics Overview
* Key Insights Panel
* Product Type Slicer for Interactive Filtering

---

## 💡 Key Insights

### Best Supplier

**Supplier 1**

* Lowest defect rate: 1.80%
* Fastest lead time: 14.8 days

### Top Product Category

**Skincare**

* Revenue: ₹2.42 Lakhs
* Contributes 42% of total revenue
* Average stock level: 40.2 units (understocked)

### Quality Crisis

* Passed Inspection: 23%
* Failed Inspection: 36%
* Pending Inspection: 41%

### Route Inefficiency

* Route A: ₹485 per unit
* Route B: ₹595 per unit
* Route B is 22.7% more expensive

---

## 📈 Analysis Summary

### Revenue Analysis

| Product Category | Revenue   |
| ---------------- | --------- |
| Skincare         | ₹2,41,628 |
| Haircare         | ₹1,74,455 |
| Cosmetics        | ₹1,61,521 |

**Total Revenue:** ₹5,77,605

#### City Performance

| City   | Revenue   |
| ------ | --------- |
| Mumbai | ₹1,37,755 |
| Delhi  | ₹81,028   |

Revenue gap between top and bottom city: **41%**

---

### Quality Analysis

| Inspection Status | Percentage |
| ----------------- | ---------- |
| Pass              | 23%        |
| Fail              | 36%        |
| Pending           | 41%        |

#### Quality Tiers

| Quality Tier                       | SKUs |
| ---------------------------------- | ---- |
| Good Quality (<1% Defect Rate)     | 24   |
| Average Quality (1–3% Defect Rate) | 44   |
| Poor Quality (>3% Defect Rate)     | 32   |

---

### Logistics Analysis

#### Transportation Distribution

* Road: 29%
* Rail: 28%
* Air: 26%
* Sea: 17%

#### Route Cost Comparison

| Route   | Cost per Unit |
| ------- | ------------- |
| Route A | ₹485          |
| Route B | ₹595          |
| Route C | ₹500          |

#### Delivery Performance

* Delayed Orders: 17
* Delay Rate: 17%

---

## 🛠 Tools & Technologies

* Power BI
* Python
* Pandas
* NumPy
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Intelligence

---

## 📌 Project Outcome

This analysis helped identify:

* High-performing suppliers
* Quality control bottlenecks
* Costly transportation routes
* Revenue-driving product categories
* Inventory optimization opportunities
* Logistics efficiency improvements

The dashboard enables management to make data-driven decisions for improving overall supply chain performance.
