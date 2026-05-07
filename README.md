# 🛒 E-Commerce Sales Analysis Dashboard

A comprehensive Excel-based sales analytics dashboard built on the **Olist Brazil E-Commerce Dataset**. This dashboard provides interactive insights into revenue trends, seller performance, customer behaviour, payment methods, and order status — all within a single Excel workbook.

---

## 📌 Project Overview

| Detail | Info |
|---|---|
| **Tool Used** | Microsoft Excel (Pivot Tables, Charts, Slicers) |
| **Dataset** | Olist Brazil Public E-Commerce Dataset |
| **Time Period** | September 2016 – August 2018 |
| **Total Orders** | 1,12,650 |
| **Unique Customers** | 99,441 |
| **Total Revenue** | ₹ 1,35,91,643.70 |
| **Avg Freight Value** | 19.99 |

---

## 📊 Dashboard Features

### KPI Cards (Top Section)
Four summary metric cards are displayed at the top of the dashboard:

| KPI | Value |
|---|---|
| Sum of Price (Total Revenue) | $13,591,643.70 |
| Count of Orders | 1,12,650 |
| Count of Unique Customers | 99,441 |
| Average Freight Value | 19.99 |

### Charts Included

| Chart | Description |
|---|---|
| **Monthly Sales Trend** | Line chart showing revenue growth from Sep 2016 to Aug 2018 |
| **Best Selling Product Categories** | Bar chart of top 10 categories by revenue |
| **Most Used Payment Method** | Pie chart showing payment type distribution |
| **Order Status Breakdown** | Bar chart comparing delivered, cancelled, and other order statuses |
| **Seller Analysis** | Bar chart of top 10 sellers by total revenue |
| **Top Purchasing States** | Area/bar chart showing customer distribution by state |

### Interactive Filters (Slicers)
The dashboard includes the following slicers for dynamic filtering:

- **order_status** — Filter by approved, cancelled, delivered, invoiced, processing, shipped, unavailable, created
- **product_cate...** — Filter by product category (e.g., beleza_saude, cama_mesa_banho, etc.)
- **payment_type** — Filter by boleto, credit_card, debit_card, not_defined, voucher
- **customer_st...** — Filter by customer state (AC, AL, AM, AP, BA, etc.)
- **Date Timeline** — Filter orders by month/year range (2017–2018)

---

## 🗂️ Workbook Structure

The Excel file contains the following sheets:

| Sheet Name | Purpose |
|---|---|
| **Dashboard** | Main interactive dashboard with all charts and KPIs |
| **KPIs** | Source data for the 4 KPI summary cards |
| **Monthly Sales Trend** | Month-wise revenue data from 2016 to 2018 |
| **Product Categories** | Revenue breakdown by product category (top 10) |
| **Order Status** | Count of orders by each status type |
| **Payment Method Analysis** | Count of orders by payment method |
| **Seller Performance** | Top 10 sellers ranked by total revenue |
| **State-wise Orders** | Customer order count by Brazilian state |

---

## 📈 Key Insights

1. **Revenue Peak** — November 2017 recorded the highest monthly revenue at **$1,010,271** (likely due to Black Friday/seasonal sales).
2. **Top State** — **São Paulo (SP)** leads with **41,746 orders**, nearly 4x the next state (RJ: 12,852).
3. **Dominant Payment Method** — **Credit Card** accounts for **76,795 orders (73.9%)**, making it the most preferred payment type.
4. **Top Product Category** — **Health & Beauty (beleza_saude)** generated the highest revenue at **$1,258,681**.
5. **Order Delivery Rate** — Out of 99,441 total orders, **96,478 were successfully delivered** — a delivery success rate of ~97%.
6. **Freight Cost** — Average freight value across all orders is **$19.99**.

---

## <img width="541" height="580" alt="Screenshot 2026-05-08 021455" src="https://github.com/user-attachments/assets/73c82245-937a-409f-97d7-98adc76de70e" />

---

## 📂 Dataset Information

This dashboard is built on the **Olist Brazilian E-Commerce Public Dataset**, which is available on Kaggle.

- **Source:** [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Records:** 99,000+ orders placed between 2016 and 2018
- **Note:** Product category names are in **Portuguese** (original dataset language) — e.g., `beleza_saude` = Health & Beauty, `cama_mesa_banho` = Bed & Bath.

### Portuguese Category Name Reference

| Original Name | English Translation |
|---|---|
| beleza_saude | Health & Beauty |
| relogios_presentes | Watches & Gifts |
| cama_mesa_banho | Bed & Bath |
| esporte_lazer | Sports & Leisure |
| informatica_acessorios | Computer Accessories |
| moveis_decoracao | Furniture & Decor |
| ferramentas_jardim | Tools & Garden |
| utilidades_domesticas | Home Utilities |
| cool_stuff | Novelty Items |
| automotivo | Automotive |

---

## 🛠️ Tools & Techniques Used

- **Microsoft Excel**
  - Power Query
  - Power Pivot 
  - Pivot Tables
  - Pivot Charts
  - Slicers & Timeline Filters
  - Conditional Formatting
  - KPI Card Design
  - VLOOKUP
  - Data Cleaning

---


