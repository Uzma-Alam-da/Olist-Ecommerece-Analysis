# Olist E-Commerce Performance Dashboard

Analysis of the Olist Brazilian E-Commerce dataset (~100,000 orders, 2016–2018), covering revenue trends, product categories, delivery performance, payment behavior, and top-performing sellers.

## Project Overview

This project explores customer, order, payment, and review data from Olist, a Brazilian e-commerce marketplace, to answer key business questions:

- What does the revenue trend look like over time?
- Which product categories generate the most revenue?
- Does delivery speed affect customer review scores?
- Which states drive the most revenue?
- What payment methods do customers prefer?
- Who are the top-performing sellers?

## Tools & Process

**Phase 1 — Data Cleaning (Python / pandas)**
- Loaded and merged 9 raw CSV files (orders, order items, payments, reviews, customers)
- Handled missing values and duplicates
- Converted date fields and calculated delivery time (`delivery_days`)
- Translated product categories to English
- Exported four clean, joined tables: orders, order items, payments, reviews

**Phase 2 — Dashboard (Power BI)**
- Built relationships across cleaned tables
- Created DAX measures for Total Revenue, Total Orders, Average Review Score, and Average Delivery Days
- Designed 7 visuals across a single-page dashboard

## Dashboard Highlights

- **Total Revenue:** 13.59M | **Total Orders:** 99K | **Avg. Review Score:** 4.09 | **Avg. Delivery Days:** 12
- Revenue grew steadily from 2017 through mid-2018
- *Health & Beauty* and *Watches & Gifts* are the top revenue-generating categories
- Shorter delivery windows correlate with higher average review scores
- Revenue is heavily concentrated in São Paulo (SP) and other southeastern states
- Credit card is the dominant payment method (~78% of transactions), followed by boleto (~18%)
- Top 10 sellers by revenue are identified in a dedicated table view

## Files in This Repo

| File | Description |
|------|-------------|
| `olist_ecommerce_analysis.ipynb` | Python notebook — data cleaning and preparation |
| `Olist_dashboard.pbix` | Power BI dashboard file |
| `Olist_Dashboard.pdf` | Static export of the final dashboard |

## Dataset Source

[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle)

## Author

Uzma Alam — Aspiring Data Analyst# Olist-Ecommerece-Analysis
Python + Power BI analysis of the Olist Brazilian E-Commerce dataset
