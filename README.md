# Analisis Faktor yang Memengaruhi Preferensi Street Hail dan Strategi untuk Meningkatkan Penggunaan Aplikasi

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi rendahnya preferensi pemesanan taksi berbasis aplikasi (dispatch) dibandingkan metode street hail di New York City. Selain itu, proyek ini juga memberikan rekomendasi strategi untuk meningkatkan penggunaan aplikasi dispatch.

## Dataset
Dataset yang digunakan berasal dari **NYC Taxi and Limousine Commission (TLC)**, mencakup informasi seperti:
- **VendorID**: Penyedia layanan taksi.
- **PULocationID & DOLocationID**: Zona penjemputan dan pengantaran.
- **Trip Distance**: Jarak perjalanan.
- **Fare Amount**: Tarif perjalanan.
- **Payment Type**: Metode pembayaran.
- **Trip Type**: Jenis perjalanan (street hail atau dispatch).
- **Durasi Perjalanan**: Waktu tempuh perjalanan.

## Teknologi yang Digunakan
- **Python**: Analisis data.
- **Pandas**: Manipulasi data.
- **Seaborn & Matplotlib**: Visualisasi data.
- **Statsmodels & Scipy**: Uji statistik.
- **Jupyter Notebook**: Dokumentasi analisis.


## Langkah-Langkah Analisis
1. **Data Understanding**: Memahami struktur dataset dan mengidentifikasi missing values, outliers, serta inkonsistensi.
2. **Data Cleaning**: Menghapus atau menangani nilai yang tidak relevan, seperti nilai negatif atau nol pada kolom numerik.
3. **Eksplorasi Data**: Analisis distribusi variabel, pola perjalanan, metode pembayaran, dan zona penjemputan.
4. **Analisis Statistik**: Menggunakan uji statistik untuk mengidentifikasi korelasi dan pola signifikan.
5. **Visualisasi Data**: Membuat grafik untuk memahami perbandingan antara street hail dan dispatch.
6. **Kesimpulan & Rekomendasi**: Menyimpulkan temuan utama dan memberikan strategi untuk meningkatkan penggunaan dispatch.

## Temuan Utama
- **Faktor-Faktor yang Memengaruhi Rendahnya Dispatch**:
  - Larangan penggunaan aplikasi di beberapa wilayah.
  - Tarif perjalanan dispatch lebih tinggi dibandingkan street hail.
  - Durasi perjalanan dispatch lebih lama.
  - Zona dispatch kurang terfokus pada area dengan permintaan tinggi.
  - Kemudahan akses street hail di wilayah padat penduduk.
  - Kebiasaan pengguna lebih memilih street hail.
  
- **Strategi untuk Meningkatkan Dispatch**:
  - Memberikan diskon atau insentif di wilayah dengan permintaan rendah.
  - Menurunkan tarif dispatch agar lebih kompetitif.
  - Menambah pengemudi dispatch di wilayah dengan permintaan tinggi selama jam sibuk.
  - Edukasi pengguna tentang kelebihan dispatch, seperti keamanan dan kenyamanan.

