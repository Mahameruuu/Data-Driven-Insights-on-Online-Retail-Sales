# Analisis Data Penjualan E-Commerce

Proyek ini bertujuan untuk menganalisis data penjualan dari e-commerce menggunakan dataset **Online Retail**. Dataset ini berisi semua transaksi yang terjadi antara 01/12/2010 dan 09/12/2011 untuk sebuah ritel online yang berbasis di Inggris.

## Deskripsi Dataset

Dataset terdiri dari kolom-kolom berikut:
- **InvoiceNo**: Nomor faktur.
- **StockCode**: Kode produk.
- **Description**: Deskripsi produk.
- **Quantity**: Jumlah produk yang dibeli.
- **InvoiceDate**: Tanggal dan waktu transaksi.
- **UnitPrice**: Harga per unit produk.
- **CustomerID**: ID pelanggan.
- **Country**: Negara pelanggan.
- **Revenue**: Total pendapatan dari penjualan (dihitung sebagai `Quantity * UnitPrice`).

## Tujuan Analisis

1. **Menghitung Total Pendapatan**: Mengetahui total pendapatan dari penjualan.
2. **Menganalisis Tren Penjualan Bulanan**: Memvisualisasikan perubahan pendapatan dari bulan ke bulan.
3. **Mengidentifikasi Produk Terlaris**: Menemukan 10 produk dengan penjualan tertinggi.
4. **Menganalisis Pendapatan Berdasarkan Negara**: Mengetahui pendapatan yang dihasilkan dari setiap negara.

## Prasyarat

Sebelum menjalankan skrip, pastikan Anda telah menginstal pustaka berikut:
- `pandas`
- `matplotlib`
- `seaborn`

Anda dapat menginstal pustaka ini dengan menggunakan pip:

```bash
pip install pandas matplotlib seaborn
