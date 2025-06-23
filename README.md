# ✨ Bank Transaction Customer Segmentation 

## 🚀 Deskripsi Proyek 
Proyek ini menggunakan Bank Transaction Dataset untuk menganalisis dan mengelompokkan pola perilaku transaksi pelanggan. Melalui serangkaian tahapan mulai dari eksplorasi data, pra-pemrosesan fitur relevan, hingga penerapan algoritma unsupervised learning seperti K-Means, kami berupaya mengidentifikasi segmen-segmen pelanggan yang berbeda.

## 🎯 Goals:
1. Melakukan segmentasi pelanggan bank ke dalam 4 kelompok yang berbeda berdasarkan karakteristik transaksi mereka.
2. Mengidentifikasi wawasan awal mengenai perbedaan perilaku transaksi antar kelompok yang terbentuk.
3. Memvisualisasikan hasil clustering secara jelas untuk mempermudah interpretasi dan pemahaman.
4. Mempelajari dasar-dasar eksplorasi data (EDA) pada data transaksional dan pra-pemrosesan untuk machine learning.
5. Memahami dan menerapkan algoritma unsupervised learning (K-Means) dalam konteks segmentasi data nyata.

## ✨ Fitur Utama Proyek 
Berikut adalah tahapan kunci yang dilakukan dalam proyek ini:

### Pemuatan & Pemahaman Data: 📂 
Memuat dataset dan memahami struktur awal serta tipe datanya.

2. Eksplorasi Data (EDA) Transaksi: 🔍
- Menganalisis distribusi amount, transaction_type, dan customer_id.
- Memvisualisasikan pola transaksi seiring waktu untuk menemukan tren.
- Mengidentifikasi fitur-fitur yang paling berpotensi untuk analisis clustering.
3. Pra-pemrosesan Data untuk Clustering: 🧹
- Mengagregasi data transaksi per pelanggan (misal: total amount, jumlah transaksi, rata-rata amount per pelanggan).
- Menangani nilai yang hilang (jika ada) dan outlier untuk memastikan kualitas data.
- Normalisasi/Penskalakan fitur numerik (penting untuk K-Means) agar semua fitur memiliki bobot yang setara.
4. Penerapan Algoritma Clustering (K-Means): 📊
- Menentukan jumlah cluster yang optimal (dalam kasus ini, 4 cluster).
Melatih model K-Means pada data yang telah diproses untuk mengelompokkan pelanggan.
5. Analisis & Visualisasi Hasil Clustering: 🎨
- Menambahkan label cluster yang dihasilkan ke dataset asli untuk analisis lebih lanjut.
- Menganalisis karakteristik setiap cluster (misal: rata-rata amount, frekuensi, tipe transaksi dominan di setiap cluster) untuk memahami profil segmen pelanggan.
- Memvisualisasikan cluster menggunakan scatter plot (misal: PCA/t-SNE untuk reduksi dimensi jika fitur banyak) atau box plot fitur-fitur penting per cluster.

## Setup Environment ✨
Sebelum menginstal library, disarankan untuk menggunakan virtual environment agar dependensi proyek tetap terisolasi dan tidak mengganggu proyek Python lainnya. Jalankan perintah berikut di Shell/Terminal :
- python -m venv venv
- .\venv\Scripts\activate

## Setup Library 📦
Setelah mengaktifkan virtual environment, instal semua dependensi dari file requirements.txt dengan perintah berikut: pip install -r requirements.txt
