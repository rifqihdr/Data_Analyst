# **Market Research for Business Growth:Customer Behavior Analysis for a Garment Company in Bandung**

## 🎯 **Project Overview**
Proyek ini dirancang untuk mendukung peningkatan penjualan e-commerce pada sebuah perusahaan garmen di Bandung. Walaupun telah memiliki banyak pelanggan, perusahaan masih kesulitan dalam memahami kebiasaan dan preferensi belanja mereka. Untuk itu, dilakukan analisis data pelanggan dan transaksi menggunakan pendekatan data mining seperti clustering, decision tree, dan association rule mining guna merumuskan strategi pemasaran yang lebih tepat sasaran. 

Project ini melibatkan beberapa hal kunci, antara lain:
1.	Analisis dilakukan menggunakan Python (Pandas, NumPy, Matplotlib, Seaborn, dan Scikit-learn).
2.	Exploratory Data Analysis (EDA) untuk memahami distribusi dan pola data pelanggan serta transaksi.
3.	Menerapkan K-Means Clustering untuk melakukan segmentasi pelanggan berdasarkan total pembelian dan jarak pengiriman.
4.	Menggunakan Decision Tree untuk mengidentifikasi faktor utama yang memengaruhi keputusan pembelian pelanggan.
5.	Menerapkan Association Rule Mining untuk menemukan pola pembelian produk guna mendukung strategi bundling dan promosi.

Proyek ini menghasilkan segmentasi pelanggan, identifikasi faktor keputusan pembelian untuk mendukung stratefi pemasaran dan peningkatan penjualan berbasis data.

## 💻 **Alat & Teknik**
1.	Python (Pandas, NumPy, Matplotlib, Seaborn, Sklearn.cluster)
2.	Exploratory Data Analysis (EDA)
3.	K-Means Clustering
4.	Decision Tree
5.	Association Rule Mining

## 📁 **Dataset**
Data dianalisis berdasarkan output random number generation di Microsoft Excel.
1.	Dataset pelanggan berisi 15.000 data dengan ID urut, total pembelian (rata-rata Rp250.000, SD Rp150.000), dan jarak pengiriman (rata-rata 120 km, SD 70 km), keduanya berdistribusi normal dan menggunakan nilai absolut untuk menghindari negatif.
2.	Dataset pola keputusan pembelian berisi 15.000 data pelanggan dengan ID urut, variabel biner terkait kualitas produk, informasi produk, jenis pengiriman, ongkos kirim, rating, metode pembayaran, dan status pembelian; semua dihasilkan dengan distribusi Bernoulli sesuai peluang masing-masing
3.	Dataset transaksi pembelian produk berisi 20.000 catatan dengan status pembelian (0 = tidak membeli, 1 = membeli) untuk 17 jenis produk, masing-masing dihasilkan dengan distribusi Bernoulli sesuai peluang yang ditentukan
Dataset terdiri dari 17 kolom dan merepresentasikan data penjualan global secara simulatif.

**🔗 Lihat detailnya di sini:**
https://docs.google.com/spreadsheets/d/1KZR0jR13btd88eklSvkYGvnXt3iDzRX2/edit?usp=drive_link&ouid=112147009984858765975&rtpof=true&sd=true 

## 🔍 **Temuan Utama**
1.	Eksplorasi & visualisasi data sintetis dari tiga dataset (pelanggan, pola keputusan, transaksi).
2.	Segmentasi pelanggan berbasis total pembelian & jarak pengiriman untuk strategi marketing.
3.	Aturan keputusan pembelian (max depth = 3) dari data pola keputusan untuk rekomendasi strategi.
4.	Pola pembelian produk (min support = 0.3, confidence = 0.5) untuk pengembangan strategi penjualan.

## ✨ **Kesimpulan & Dampak Bisnis**
1. Ketiga dataset (pelanggan, pola keputusan, transaksi) menunjukkan bahwa sebagian besar pelanggan bertransaksi dalam skala kecil, menilai produk serta informasi dengan baik, dominan memilih COD, dan memiliki preferensi pembelian yang beragam, memberikan wawasan penting untuk strategi pemasaran yang lebih tepat sasaran.
2. Segmentasi K-Means mengidentifikasi empat klaster pelanggan dengan mayoritas pembelian rendah di area dekat, memberikan peluang penerapan strategi pemasaran lokal, optimasi stok, dan promosi terarah untuk meningkatkan nilai serta frekuensi pembelian.
3. Hasil pohon keputusan mengungkap faktor dominan dalam pembelian produk, termasuk kualitas dan informasi produk, metode pembayaran, rating, ongkos kirim, serta jenis pengiriman, yang dapat dimanfaatkan untuk strategi pemasaran berbasis data.
4. Association Rule Mining mengidentifikasi keterkaitan signifikan antara T-Shirt dan Jeans, memberikan dasar untuk strategi pemasaran bundling dan kampanye cross-selling yang terarah
