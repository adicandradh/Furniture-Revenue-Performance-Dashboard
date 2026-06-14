# Furniture Revenue Performance Dashboard (Looker Studio)
## 📌 Project Type
Final Project KarirNex Data Analyst Bootcamp Batch 5
## 📊 Overview
Project ini merupakan dashboard interaktif berbasis Google Looker Studio yang dikembangkan untuk menganalisis performa penjualan bisnis furniture.

Fokus utama dari project ini adalah mengolah data transaksi penjualan menjadi informasi yang terstruktur, mudah dipahami, dan dapat digunakan untuk mendukung pengambilan keputusan bisnis. Proses yang dilakukan mencakup data cleaning, exploratory data analysis (EDA), serta visualisasi data untuk mengidentifikasi pola dan performa bisnis secara menyeluruh.
## 🎯 Objectives
- Menyajikan ringkasan performa bisnis melalui KPI utama
- Menganalisis tren revenue dari waktu ke waktu
- Mengidentifikasi produk dengan kontribusi revenue tertinggi
- Menganalisis performa kategori produk
- Mengevaluasi distribusi status pesanan
- Memantau perilaku pelanggan melalui metrik transaksi
## ⚙️ Data Processing
- Data cleaning untuk memastikan kualitas data
- Penanganan missing values dan duplicate records
- Exploratory Data Analysis (EDA)
- Pembuatan calculated fields
- Agregasi data menggunakan SQL
- Transformasi data menggunakan Python
## 🧠 Business Logic
- Total Revenue dihitung dari akumulasi seluruh nilai transaksi penjualan
- Average Order Value (AOV) dihitung dari Total Revenue dibagi Total Orders
- Completion Rate dihitung dari persentase pesanan berstatus Completed terhadap total pesanan
- Total Customers dihitung berdasarkan jumlah pelanggan unik
- Units Sold dihitung dari total kuantitas produk yang berhasil terjual
- Revenue by Category dihitung berdasarkan total revenue pada masing-masing kategori produk
- Revenue by Product dihitung berdasarkan total revenue pada masing-masing produk
## 🛠️ Tools & Skills
- SQL (Google BigQuery)
- Python
- Google Looker Studio
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data transformation
- Data visualization & dashboard design
- Business analysis
## 🖼️ Preview
Berikut dashboard interaktif yang dapat dieksplorasi secara langsung melalui Google Looker Studio:
https://datastudio.google.com/reporting/9fe179b1-4b4c-4d37-b875-3994a01af7d6
<img width="2500" height="3126" alt="Furniture Revenue Performance" src="https://github.com/user-attachments/assets/868f90cf-ef8e-47ba-a495-f850667aae1b" />

## 📊 Insights
- Bisnis menghasilkan total revenue Rp53,03 miliar dari 10.000 transaksi dengan Average Order Value sebesar Rp5,30 juta dan completion rate 89,7%, menunjukkan performa penjualan yang kuat dengan tingkat penyelesaian pesanan yang tinggi.
- Revenue bulanan relatif stabil sepanjang tahun dengan rentang sekitar Rp3,98–Rp4,78 miliar. Revenue tertinggi terjadi pada Juli 2025 sebesar Rp4,78 miliar, sementara terendah terjadi pada November 2025 sebesar Rp3,98 miliar.
- Sebagian besar transaksi berhasil diselesaikan dengan status completed sebesar 89,7% (8.972 order), sedangkan cancelled sebesar 5,2% (519 order) dan refund sebesar 5,1% (509 order), menunjukkan performa operasional yang cukup baik.
- Kitchen Set menjadi produk dengan kontribusi revenue terbesar sebesar Rp8,63 miliar, diikuti Kasur sebesar Rp5,59 miliar dan Lemari Sliding sebesar Rp5,20 miliar, menjadikannya produk utama pendorong pendapatan.
- Kategori Kamar Tidur menghasilkan revenue tertinggi sebesar Rp19,47 miliar, diikuti Ruang Tamu sebesar Rp13,85 miliar dan Dapur sebesar Rp10,54 miliar, menunjukkan bahwa kategori furnitur rumah tangga mendominasi kontribusi pendapatan.
- Analisis revenue berdasarkan kombinasi kota, produk, dan kategori menunjukkan bahwa Kitchen Set pada kategori Dapur memiliki performa yang kuat di berbagai kota. Jakarta Utara menjadi kontributor tertinggi dengan revenue sekitar Rp1,18 miliar, diikuti Depok sebesar Rp985 juta dan Jakarta Barat sebesar Rp934 juta.
