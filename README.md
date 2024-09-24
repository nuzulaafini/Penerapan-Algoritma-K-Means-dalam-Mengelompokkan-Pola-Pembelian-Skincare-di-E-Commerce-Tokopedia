### README

# Penerapan Algoritma K-Means dalam Mengelompokkan Pola Pembelian Skincare di E-Commerce Tokopedia

Proyek ini bertujuan untuk menerapkan algoritma **K-Means Clustering** dalam mengelompokkan pola pembelian skincare di platform e-commerce Tokopedia. Tujuan utama dari proyek ini adalah untuk menemukan pola atau segmen pelanggan berdasarkan perilaku pembelian, yang nantinya dapat digunakan untuk meningkatkan strategi pemasaran, promosi, atau rekomendasi produk.

## Latar Belakang

E-commerce seperti Tokopedia memiliki volume data transaksi yang besar, yang menyimpan berbagai informasi tentang pola pembelian konsumen. Dengan menggunakan algoritma **K-Means**, kita dapat melakukan segmentasi pelanggan untuk memahami lebih dalam tentang kelompok pelanggan yang memiliki pola belanja serupa. Segmentasi ini berguna dalam membuat keputusan bisnis yang lebih baik seperti strategi pemasaran yang terarah dan promosi yang lebih efektif.

## Algoritma K-Means

**K-Means** adalah algoritma clustering yang mempartisi data ke dalam **K** kelompok (clusters). Algoritma bekerja dengan cara:
1. Menginisialisasi sejumlah **K** centroids secara acak.
2. Mengelompokkan setiap data ke centroid terdekat berdasarkan jarak Euclidean.
3. Menghitung ulang centroid dari setiap kelompok.
4. Mengulangi proses hingga centroid tidak berubah atau konvergensi tercapai.

## Dataset

Dataset yang digunakan dalam proyek ini berisi informasi transaksi pembelian produk skincare dari Tokopedia. Dataset berisi fitur-fitur seperti:
- Nama produk
- Harga
- Jumlah unit yang terjual
- Rating produk
- Tanggal transaksi

Setelah data ini diolah, K-Means akan digunakan untuk mengelompokkan pola pembelian.

## Struktur Proyek

```
|-- main.ipynb
|-- README.md
|-- requirements.txt
```

## Cara Menjalankan Proyek

1. Clone repositori ini:

   ```bash
   git clone https://github.com/nuzulaafini/Penerapan-Algoritma-K-Means-dalam-Mengelompokkan-Pola-Pembelian-Skincare-di-E-Commerce-Tokopedia.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Jalankan Jupyter Notebook untuk melakukan eksplorasi data dan menjalankan algoritma K-Means:

   ```bash
   jupyter notebook notebooks/KMeans_Tokopedia_Skincare.ipynb
   ```

4. Setelah proses clustering selesai, Anda dapat melihat visualisasi hasil dan interpretasi dari kelompok yang terbentuk berdasarkan pola pembelian.

## Hasil

Hasil dari penerapan K-Means Clustering adalah beberapa kelompok pelanggan dengan pola pembelian yang mirip. Setiap cluster dapat memberikan wawasan seperti:
- Pelanggan yang membeli produk dengan harga tinggi namun jarang.
- Pelanggan yang sering membeli produk dengan harga murah.
- Pelanggan dengan preferensi tertentu terhadap jenis produk atau brand.

## Dependencies

Proyek ini menggunakan beberapa pustaka Python yang diuraikan dalam file `requirements.txt` (lihat di bawah). Pastikan Anda menginstall semua dependencies tersebut sebelum menjalankan proyek.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori ini, buat branch baru untuk fitur atau perbaikan Anda, dan kirim **pull request**.

1. Fork repositori ini.
2. Buat branch baru untuk fitur atau perbaikan:

   ```bash
   git checkout -b fitur-baru
   ```

3. Commit perubahan:

   ```bash
   git commit -m "Menambahkan fitur baru"
   ```

4. Push branch Anda:

   ```bash
   git push origin fitur-baru
   ```

5. Buat **pull request** untuk menggabungkan perubahan Anda ke repositori utama.
