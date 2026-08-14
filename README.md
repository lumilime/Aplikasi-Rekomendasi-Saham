# Aplikasi-Rekomendasi-Saham

Proyek ini adalah alat analisis fundamental saham interaktif terutama IHSG, yang dibangun menggunakan Google Colab dan `ipywidgets`. Alat ini memungkinkan pengguna untuk:

1.  **Mengambil Data Fundamental Otomatis dari Web (Yahoo Finance)**: Dengan memasukkan kode saham (ticker), aplikasi akan mengambil data rasio fundamental kunci.
2.  **Mengekstrak Data dari Laporan Keuangan PDF**: Mendemonstrasikan kemampuan untuk mengurai data dari file PDF laporan keuangan resmi IDX.
3.  **Melakukan Analisis Scoring**: Memberikan skor berdasarkan rasio fundamental seperti Current Ratio (CR), Debt to Equity Ratio (DER), Return on Equity (ROE), Net Profit Margin (NPM), dan Price to Earnings Ratio (PER).
4.  **Memberikan Rekomendasi Horizon Investasi**: Berdasarkan skor dan kriteria tambahan, aplikasi merekomendasikan apakah saham cocok untuk investasi jangka panjang atau jangka pendek/momentum.
5.  **Menghasilkan Rekomendasi Transaksi**: Menghitung potensi harga masuk (Entry), target profit (TP), dan stop loss (SL) beserta Risk/Reward Ratio.
6.  **Menyajikan Ringkasan Alasan**: Memberikan penjelasan mengapa suatu saham dikategorikan 'Baik' atau 'Kurang Baik' berdasarkan rasio fundamentalnya.

## Cara Menggunakan

1.  **Buka di Google Colab**: Buka notebook ini di lingkungan Google Colab.
2.  **Instal Dependensi**: Jalankan sel-sel yang menginstal pustaka yang diperlukan.
3.  **Jalankan Semua Sel**: Jalankan semua sel dalam notebook secara berurutan.
4.  **Interaksi dengan UI**: Gunakan widget yang disediakan untuk memasukkan kode saham atau mengunggah file PDF, lalu klik tombol analisis untuk melihat hasilnya.

## Instalasi Dependensi

Untuk menjalankan notebook ini, Anda memerlukan pustaka Python berikut. Anda dapat menginstalnya dengan menjalankan perintah ini di sel Colab (biasanya sudah ada sel `!pip install` yang sesuai):

```bash
!pip install -r requirements.txt
```

Atau secara manual:

```bash
!pip install ipywidgets matplotlib pdfplumber yfinance pandas requests
```

## Struktur Proyek

*   `*.ipynb`: File notebook utama proyek ini.
*   `requirements.txt`: Daftar pustaka Python yang diperlukan.

## Kontribusi

Kontribusi sangat dihargai. Silakan buat *pull request* atau buka *issue* jika Anda memiliki saran atau menemukan *bug*.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License]. Lihat file `LICENSE` untuk detail lebih lanjut.
