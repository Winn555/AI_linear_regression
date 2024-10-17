# Prediksi Rating Film IMDB Teratas

Proyek ini menggunakan dataset **TOP 100 IMDB MOVIES** untuk membangun model regresi linier yang memprediksi rating film berdasarkan tahun rilisnya. Proyek ini dilakukan di Google Colab dan terintegrasi dengan Google Drive untuk mengakses dataset.

## Deskripsi Proyek

Proyek ini bertujuan untuk:
- Memuat dan menganalisis data film teratas di IMDB.
- Membangun model regresi linier untuk memprediksi rating film berdasarkan tahun rilis.
- Menggunakan visualisasi untuk menunjukkan hasil prediksi.

## Persyaratan

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Instruksi Pengaturan

1. **Membuat dan Mengatur Google Drive**:
   - Pastikan file **"TOP 100 IMDB MOVIES.csv"** disimpan di dalam folder **"phyton"** di Google Drive Anda.

2. **Menghubungkan Google Colab ke Google Drive**:
   - Gunakan kode berikut untuk menghubungkan Google Colab dengan Google Drive:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
