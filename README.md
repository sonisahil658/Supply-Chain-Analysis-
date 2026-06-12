# Supply-Chain-Analysis-
Supply Chain Analysis Dashboard using Power BI and Python

 Project Overview

This project presents a complete supply chain diagnostic analysis for a consumer goods company operating across India. The analysis covers 100 SKUs across three product categories — Skincare, Haircare, and Cosmetics — spanning 5 major Indian cities and 5 suppliers.

The goal is to identify revenue patterns, supplier performance gaps, quality control issues, and logistics cost inefficiencies using Power BI for visualization and Python (Pandas) for data cleaning and EDA.


Project ID: CDACL-003

Tool: Power BI Desktop + Python

Dataset: 100 rows × 24 columns

Region: India | FY 2024




🎯 Business Problem

A consumer goods company faces critical challenges in its supply chain:


36% of products failed quality inspection — systemic quality control issue
2.28% average defect rate — 76% of SKUs in Average or Poor quality tier
Route B costs 22.7% more than Route A — logistics budget being drained
17% shipping delay rate — customer service level at risk
Skincare understocked despite being the top revenue product (₹2.42L)



📊 Dashboard Preview

<img width="1328" height="748" alt="Supply Chain Analysis Dashboard" src="https://github.com/user-attachments/assets/93e838d6-c368-46f6-a6c8-45c25c84453b" />



Dashboard includes:


5 KPI Cards — Revenue, SKUs, Defect Rate, Lead Time, Inspection Fails
Revenue by Product Type (bar chart)
Top Locations by Revenue (ranked horizontal bars)
Transportation Modes (donut chart)
Supplier Performance Table (with conditional formatting)
Quality Tier Breakdown
Inspection Results (color-coded bar chart)
Customer Demographics (donut chart)
Key Insights Strip (bottom)
Product Type Slicer (interactive filter tabs)

💡 Key Insights

Best SupplierSupplier 1 — lowest defect rate (1.80%) and fastest lead time (14.8 days)
Top ProductSkincare — ₹2.42L revenue (42% of total) but understocked at 40.2 avg units
Quality CrisisOnly 23% of products passed inspection — 36% failed, 41% still pending
Route InefficiencyRoute B costs ₹595/unit — 22.7% more expensive than Route A (₹485/unit)

📈 Analysis Summary

Revenue


Total Revenue: ₹5,77,605
Skincare: ₹2,41,628 (41.8%) · Haircare: ₹1,74,455 (30.2%) · Cosmetics: ₹1,61,521 (28%)
Top city: Mumbai ₹1,37,755 | Weakest: Delhi ₹81,028 (41% gap)


Quality


Pass: 23% · Fail: 36% · Pending: 41%
Good quality (<1% defect): 24 SKUs
Average quality (1–3%): 44 SKUs
Poor quality (>3%): 32 SKUs


Logistics


Road 29% · Rail 28% · Air 26% · Sea 17%
Route A: ₹485/unit ✅ · Route B: ₹595/unit ❌ · Route C: ₹500/unit
17 orders delayed (17% delay rate)
