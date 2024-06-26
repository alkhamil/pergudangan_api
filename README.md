## Aplikasi Pergudangan

Aplikasi pergudangan adalah sistem yang digunakan untuk mengelola berbagai aktivitas yang terkait dengan penyimpanan dan distribusi barang di dalam gudang. Sistem ini bertujuan untuk mengoptimalkan operasional gudang, termasuk penerimaan, penyimpanan, dan pengeluaran barang, serta pelacakan stok secara real-time. Berikut adalah komponen utama dari aplikasi pergudangan:


## Draft Menu
- Dashboard
    - Ringkasan stok, permintaan terbaru, dan status transaksi.
- Master Data
    - Barang
        - Tambah, edit, dan hapus data barang.
    - Proyek
        - Tambah, edit, dan hapus data proyek.
- Permintaan Material
    - Buat Permintaan
        - Formulir untuk membuat permintaan baru.
    - Lihat Permintaan
        - Daftar permintaan material dengan statusnya.
- Transaksi
    - Proses Transaksi
        - Proses permintaan material berdasarkan stok yang tersedia.
- Pembelian Material
    - Pengajuan Pembelian
        - Buat pengajuan pembelian jika stok tidak mencukupi.
    - Lihat Pengajuan
        - Daftar pengajuan pembelian dan statusnya.
- Laporan
    - Laporan Stok
    - Laporan stok barang di gudang.
    - Laporan Transaksi
    - Laporan transaksi pengiriman barang ke proyek.

## Draft Design ERD (Entity Relationship Diagram)
![ALT TEXT](https://github.com/alkhamil/pergudangan_api/blob/main/public/docs/erd.jpeg?raw=true)

## Flowchart untuk Sistem
![ALT TEXT](https://github.com/alkhamil/pergudangan_api/blob/main/public/docs/pergudangan.drawio.png?raw=true)

## System Requirement
- PHP 7.4
- Mysql 8.4

## Cara Install
- clone project
- jalankan "composer install"
- setup .env copy dari .env-example
- jalankan "php artisan migrate"
- jalankan "php artisan serve"

## Collection Postman
[link](https://github.com/alkhamil/pergudangan_api/blob/main/public/docs/collection_api.json)

