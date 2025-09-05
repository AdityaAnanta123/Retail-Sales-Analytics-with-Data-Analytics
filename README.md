#  Retail Sales Analytics Dashboard

Dokumentasi ini menjelaskan tiga halaman utama di dashboard Power BI yang dibuat dalam proyek ini. Fokusnya adalah memberikan insight mendalam mengenai performa penjualan ritel.

---

##  1. Overview
**Tujuan:** Memberikan gambaran umum performa bisnis secara holistik.

**Tampilan Visual:**
- **KPI Cards**: Menampilkan *Total Sales*, *Total Profit*, *Total Orders*, dan *Profit Margin %*.
- **Line Chart**: Tren penjualan berdasarkan kategori (2014–2017).
- **Bar Chart**: Profit margin per sub-kategori.
- **Donut Chart**: Distribusi total penjualan per region.

**Insigh Utama yang Diharapkan:**
- Gambaran tren penjualan dan profit.
- Kontribusi kategori/subkategori terhadap revenue.
- Identifikasi region dengan performa terbaik.

---

##  2. Orders (Produk & Pesanan)
**Tujuan:** Melakukan analisis mendalam terhadap produk dan pola order.

**Tampilan Visual:**
- **Stacked Bar Chart**: Top 10 sub-kategori berdasarkan penjualan.
- **Scatter Plot**: Analisis *Sales vs Profit*, dikategorikan.
- **Matrix Table**: Detail penjualan, profit, kuantitas per kategori & region.
- **Donut Chart**: Distribusi pesanan berdasarkan kuantitas.

**Insight Utama:**
- Identifikasi produk terlaris dan margin-nya.
- Deteksi sub-kategori dengan profit rendah meski memiliki penjualan tinggi.
- Analisis penyebaran order berdasarkan kategori dan region.

---

##  3. Customers & Region
**Tujuan:** Memahami profil pelanggan dan distribusi geografis penjualan.

**Tampilan Visual:**
- **KPI Cards**: Total Customers, Average Order Value, Repeat Customer %, New Customers.
- **Bar Chart**: Sales vs Profit berdasarkan region.
- **Donut Chart**: Kategori terbaik berdasarkan jumlah pelanggan.
- **Line Chart**: Tren produk terlaris per bulan berdasarkan region.

**Insight Utama:**
- Kontribusi pelanggan vs performa penjualan.
- Segmentasi pelanggan (baru/veteran) dan nilai rata-rata order.
- Identifikasi region dengan performa tinggi serta kategori favorit pembeli.

---

##  Struktur File di Repository
Retail-Sales-Analytics-with-Data-Analytics/
│
├── dashboard/
│ └── RetailSalesDashboard.pbix
│
├── README.md ← (ini file ini)
└── assets/
└── screenshot-overview.png
└── screenshot-orders.png
└── screenshot-customers.png
---

##  Cara Export ke PDF
1. Buka halaman *Retail Sales Insight* di Power BI Desktop.
2. Pilih **File → Export → PDF**.
3. Ekspor per page, atau versi lengkap sesuai kebutuhan laporan.

---

##  Kesimpulan
Dashboard ini menyediakan wawasan lengkap dari tingkat makro (*Overview*) hingga mikro (produk & pelanggan), mendukung pengambilan keputusan berbasis data untuk strategi penjualan, pemasaran, dan operasi ritel.
