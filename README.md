# From Data to Dashboard: Retail Sales Analysis with Excel

Proyek ini adalah latihan end-to-end analisis data menggunakan Microsoft Excel, mulai dari data transaksi mentah yang berantakan, sampai jadi dashboard interaktif yang bisa difilter.

Datanya adalah data penjualan fashion retail fiktif selama Maret 2025, mencakup 5 sales person, 5 kota, dan berbagai dimensi transaksi seperti kategori produk, channel penjualan, metode pembayaran, dan tipe customer.

---

## Dashboard Preview

![Dashboard](assets/dashboard.png)

---

## Apa yang Dikerjakan

Data mentahnya punya masalah klasik: inkonsistensi kapitalisasi nama dan spasi ekstra di kolom wilayah. Sebelum bisa dianalisis, data harus dibersihkan dulu.

Setelah itu, gua bangun 9 Pivot Table untuk menjawab pertanyaan bisnis yang berbeda-beda, lalu visualisasikan hasilnya ke 9 jenis chart. Semuanya dihubungkan lewat 5 global slicer sehingga dashboard bisa difilter secara real-time tanpa perlu ubah data.

**Workflow:**
```
Raw Data → Data Cleaning → Pivot Table → Chart → Slicer → Dashboard → Insight
```

---

## Dataset

| Item | Detail |
|---|---|
| Periode | 1–31 Maret 2025 |
| Jumlah Transaksi | ~400 baris |
| Sales Person | Andi Wijaya, Budi Santoso, Dewi Lestari, Siti Aisyah |
| Wilayah | Jakarta, Bandung, Surabaya, Medan |
| Kategori Produk | Hijab, Blouse, Rok, Sepatu, Tas |
| Channel | Online, Offline |
| Metode Pembayaran | Transfer, E-Wallet, Cash |
| Tipe Customer | New, Returning |

---

## Analisis yang Dibangun

### Pivot Tables (9 tabel)

| # | Dimensi Analisis | Metrik |
|---|---|---|
| 1 | Sales Person | Total Penjualan |
| 2 | Kategori Produk | Jumlah Transaksi |
| 3 | Wilayah | Total Penjualan |
| 4 | Channel (Online vs Offline) | Jumlah Transaksi |
| 5 | Promo vs Non-Promo | % Kontribusi |
| 6 | Metode Pembayaran | Jumlah Transaksi |
| 7 | Tipe Customer (New vs Returning) | Jumlah Transaksi |
| 8 | Tanggal Transaksi | Total Penjualan (time series) |
| 9 | Promo × Channel | Cross-tab interaksi |

### Charts (9 visualisasi)

| Chart | Tipe | Insight yang Dituju |
|---|---|---|
| Sales by Sales Person | Bar Chart | Performa individu |
| Sales by Category | Column Chart | Kontribusi kategori |
| Sales by Region | Column Chart | Distribusi geografis |
| Online vs Offline | Donut Chart | Komposisi channel |
| Promo vs Non-Promo | Donut Chart | Efektivitas promo |
| Payment Method | Donut Chart | Preferensi pembayaran |
| New vs Returning Customer | Bar Chart | Loyalitas customer |
| Sales Trend by Date | Line Chart | Tren harian |
| Promo × Channel | Stacked Bar | Interaksi kampanye per channel |

### Interactive Slicers

Dashboard bisa difilter secara global menggunakan 5 slicer: **Sales Person**, **Wilayah**, **Kategori**, **Channel**, dan **Promo**. Semua chart terhubung ke slicer yang sama, jadi filtering satu elemen langsung update seluruh dashboard.

---

## Key Findings

**Sales Performance**
- Dewi Lestari (Rp 17.4M) dan Budi Santoso (Rp 16.2M) mendominasi total penjualan, jauh di atas Siti Aisyah dan Andi Wijaya
- Jakarta menjadi wilayah dengan penjualan tertinggi (Rp 11.4M) — hampir dua kali lipat Surabaya dan Medan

**Channel & Transaksi**
- Online mendominasi jumlah transaksi (56 vs 28 offline), tapi transaksi offline cenderung memiliki nilai lebih tinggi per transaksi
- Transfer adalah metode pembayaran paling dominan (35 transaksi), diikuti E-Wallet (32) dan Cash (17)

**Customer & Promo**
- Returning customer (49) lebih banyak dari new customer (35) — sinyal awal loyalitas yang cukup baik untuk data satu bulan
- Promo berkontribusi ~36% dari total transaksi, dengan konsentrasi lebih tinggi di channel online

**Kategori Produk**
- Rok memiliki jumlah transaksi tertinggi (84 transaksi) — kategori volume driver
- Total GMV keseluruhan: **Rp 47.6 Juta** dalam 31 hari

---

## Struktur Repo

```
From-Data-to-Dashboard-Visualizing-with-Excel/
├── README.md
├── .gitignore
├── data/
│   └── Jawaban Weekly Task 3_From Data to Dashboard.xlsx
└── assets/
    └── dashboard.png
```

---

## Tools

| Tool | Kegunaan |
|---|---|
| Microsoft Excel | Data cleaning, Pivot Table, Chart, Slicer, Dashboard |

---

**Achmad Faishal**  
Ekonomi Pembangunan — FEB UPN "Veteran" Yogyakarta

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/achmad-faishal-062313274/)
