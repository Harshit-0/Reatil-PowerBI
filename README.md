# 🛍️ Retail Sales Power BI Dashboard

A comprehensive **Retail Sales Dashboard** built using **Power BI** to analyze performance across stores, categories, and salespersons with a clean, dynamic layout and interactive filters.

---

## 📊 Project Objective

To build a professional-grade dashboard that provides clear insights into retail sales data and enables business stakeholders to:

- Track **Total Sales**, **Total Orders**, **Average Order Value**
- Compare **Monthly Sales Trends**
- Analyze performance by **Store Location**, **Category**, and **Salespersons**
- Monitor **Sales This Month** and **YoY Growth %**

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **CSV** data modeling with star schema

---

## 🗂️ Dataset Overview

Dataset used contains ~1M records across 6 tables (normalized star schema):

| Table | Description |
|-------|-------------|
| `factsales.csv` | Transaction-level sales fact table |
| `customers.csv` | Customer demographic data |
| `products.csv` | Product and category info |
| `dates.csv` | Date dimension with month, year, etc. |
| `salespersons.csv` | Sales team details |
| `stores.csv` | Store locations and names |

---

## 📌 Key KPIs

| KPI | Value |
|-----|-------|
| **Total Sales** | ₹3B |
| **Total Orders** | 1M |
| **Average Order Value** | ₹2751 |
| **Sales This Month** | ₹60.59M |
| **YoY Growth %** | -0.98% |
| **Sales Last Year** | ₹2.75B |

---

## 📈 Visuals & Interactions

| Visual | Purpose |
|--------|---------|
| **KPI Cards** | High-level summary |
| **Line Chart** | Monthly sales trend |
| **Clustered Bar** | Sales by Category |
| **Donut Chart** | Sales by Store Location |
| **Bar Chart** | Top 3 Salespersons |
| **Dropdown Filter** | Category selection |

---

## 🖼️ Dashboard Preview

![Dashboard Screenshot](dashboard.png)

---

## ✅ Insights Example

- **Highest Revenue Store:** Detroit
- **Top Category:** Electronics
- **Top Salesperson:** Michael Davis
- **Sales declining from Sept–Jan**: Indicates seasonal patterns

---


---

## 💡 Future Improvements

- Add drillthrough for store-level or product-level detail
- Time comparison filters (Q1 vs Q2)
- Geo-mapping store performance
