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
- Menyediakan dashboard interaktif untuk kebutuhan monitoring bisnis
## ⚙️ Data Processing
- Data cleaning untuk memastikan kualitas data
- Penanganan missing values dan duplicate records
- Exploratory Data Analysis (EDA)
- Pembuatan calculated fields
- Agregasi data menggunakan SQL
- Data transformation menggunakan Python (Pandas)
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
* Business analysis
## 🖼️ Preview
<img width="2500" height="3020" alt="Furniture Revenue Performance Dashboard" src="https://github.com/user-attachments/assets/fea0ed5e-5721-43f0-a5d0-66a4ac02c7bc" />

## 📊 Dashboard Highlights
- Bisnis furniture menghasilkan total revenue sebesar Rp53,03 miliar dari 10.000 transaksi dengan total 19.948 unit terjual dan 3.290 pelanggan unik. Nilai Average Order Value (AOV) mencapai Rp5,30 juta per transaksi yang menunjukkan nilai pembelian yang relatif tinggi pada setiap pesanan.
- Tingkat penyelesaian pesanan (Completion Rate) mencapai 89,7%, menunjukkan mayoritas transaksi berhasil diselesaikan. Sementara itu, sebagian kecil transaksi berstatus cancelled maupun refund yang dapat menjadi area evaluasi untuk meningkatkan kualitas layanan.
- Kategori Kamar Tidur menjadi kontributor revenue terbesar dengan total Rp19,47 miliar, diikuti oleh Ruang Tamu sebesar Rp13,85 miliar dan Dapur sebesar Rp10,54 miliar. Temuan ini menunjukkan bahwa kebutuhan furnitur rumah tangga menjadi sumber pendapatan utama bisnis.
- Kitchen Set menjadi produk dengan kontribusi revenue tertinggi sebesar Rp8,63 miliar, diikuti oleh Kasur sebesar Rp5,59 miliar dan Lemari Sliding sebesar Rp5,20 miliar. Produk-produk tersebut berperan sebagai pendorong utama pendapatan perusahaan.
- Tren revenue menunjukkan pola yang relatif stabil sepanjang periode analisis dengan beberapa lonjakan penjualan pada waktu tertentu. Kondisi ini mengindikasikan adanya peluang untuk mengidentifikasi faktor yang mendorong peningkatan transaksi pada periode tersebut.
- Distribusi revenue antar kategori menunjukkan adanya konsentrasi pendapatan pada beberapa kategori utama. Kategori Ruang Kerja dan Penyimpanan memiliki kontribusi revenue yang lebih rendah dibandingkan kategori lainnya sehingga dapat menjadi area evaluasi untuk pengembangan produk maupun strategi pemasaran.
- Dashboard dilengkapi filter berdasarkan kota, produk, kategori, dan rentang waktu sehingga memungkinkan eksplorasi data secara lebih fleksibel sesuai kebutuhan analisis.
- Tabel performa penjualan membantu mengidentifikasi kombinasi kota, produk, dan kategori yang memberikan kontribusi revenue terbesar sehingga mendukung proses monitoring dan pengambilan keputusan bisnis.
