# Weekly Task 3 — From Data to Dashboard: Visualizing with Excel

A hands-on Excel analytics task working with retail sales data from a fashion business operating across five Indonesian cities. The goal was to build a clean, interactive dashboard using Pivot Tables, charts, and slicers — entirely in Excel.

---

## What This Project Covers

Starting from raw transactional data, I cleaned, analyzed, and visualized sales performance across multiple dimensions: by sales person, product category, region, channel, promo status, payment method, and customer type.

The full workflow:

1. **Data cleaning** — standardized inconsistent casing and whitespace in the raw data
2. **Pivot Table analysis** — 9 pivot tables covering key business dimensions
3. **Chart creation** — 10 charts (bar, column, pie/donut, line, stacked bar)
4. **Interactive slicers** — global filters for Sales Person, Wilayah, Kategori, Channel, and Promo
5. **Dashboard layout** — all charts and slicers assembled in one canvas
6. **Narrative insight** — key business findings summarized from the visuals

---

## Dataset

| Item | Detail |
|---|---|
| Period | March 2025 (1–31 March) |
| Transactions | ~400+ rows of sales records |
| Sales Persons | Andi Wijaya, Budi Santoso, Dewi Lestari, Siti Aisyah |
| Regions | Jakarta, Bandung, Surabaya, Medan |
| Categories | Hijab, Blouse, Rok, Sepatu, Tas |
| Channels | Online, Offline |

---

## Pivot Tables Built

| # | Pivot Table | Metric |
|---|---|---|
| 1 | Sales Person | Total Penjualan |
| 2 | Category | Count of Transactions |
| 3 | Wilayah (Region) | Total Penjualan |
| 4 | Channel (Online vs Offline) | Count of Transactions |
| 5 | Promo vs Non-Promo | % Contribution |
| 6 | Payment Method | Count of Transactions |
| 7 | Customer Type (New vs Returning) | Count of Transactions |
| 8 | Date | Total Penjualan over time |
| 9 | Promo × Channel | Cross-tab interaction |

---

## Charts Built

| # | Chart | Type |
|---|---|---|
| 10 | Sales by Sales Person | Bar Chart |
| 11 | Sales by Category | Column Chart |
| 12 | Sales by Region | Column Chart |
| 13 | Online vs Offline Channel | Pie / Donut Chart |
| 14 | Promo vs Non-Promo | Pie / Donut Chart |
| 15 | Payment Method Composition | Pie / Donut Chart |
| 16 | New vs Returning Customer | Bar Chart |
| 17 | Sales Trend by Date | Line Chart |
| 18 | Promo × Channel Interaction | Stacked Bar Chart |

---

## Key Findings

- **Dewi Lestari** and **Budi Santoso** led in total penjualan, significantly ahead of other sales persons
- **Jakarta** contributed the highest regional sales (Rp 11.4M), nearly double Surabaya and Medan
- **Online channel** dominated transaction count (56 vs 28 offline), but offline transactions tended to have higher individual value
- **Rok (skirts)** had the highest transaction count among categories (84 transactions)
- **Transfer** was the most common payment method, followed by E-Wallet and Cash
- **Returning customers** outnumbered new customers (49 vs 35), suggesting reasonable early retention
- **Promo campaigns** accounted for ~36% of transactions — with stronger promo uptake on the online channel

---

## Tools

| Tool | Usage |
|---|---|
| Microsoft Excel | Pivot Tables, Charts, Slicers, Dashboard |

---

## File Structure

```
weekly-task-excel/
├── README.md
├── .gitignore
├── data/
│   └── Jawaban_Weekly_Task_3_From_Data_to_Dashboard.xlsx
└── assets/
    └── (dashboard screenshots — optional, add if available)
```

---

**Achmad Faishal**  
Ekonomi Pembangunan — FEB UPN "Veteran" Yogyakarta

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/achmad-faishal-062313274/)
