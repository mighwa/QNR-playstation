# 🎮 Billing PS Online - QARINA 11 RENTAL

Aplikasi billing rental Playstation berbasis web yang responsif, dirancang untuk memudahkan kasir mengelola durasi sewa PS 2, PS 3, PS 4, dan PS 5.

## ✨ Fitur Utama
- **Multi-Platform Support**: Mendukung tarif berbeda untuk PS 2, 3, 4, dan 5.
- **Logika Harga Dinamis**: Perhitungan otomatis berdasarkan nominal uang (termasuk paket jam dan sisa uang jadi menit).
- **Sistem Keamanan**: PIN khusus kasir untuk mengakses billing.
- **Bonus Waktu Otomatis**: Bonus 30 menit otomatis untuk penyewaan paket 4 jam (pada unit tertentu).
- **Integrasi Google Sheets**: Semua transaksi otomatis tercatat ke laporan Spreadsheet secara real-time.
- **Alarm Suara**: Notifikasi suara berbeda untuk tiap jenis console saat waktu habis.

## 💰 Struktur Harga
Aplikasi ini menggunakan perhitungan paket:
* **PS 2**: Rp 3.000/jam (Paket: 2j=5rb, 3j=8rb, 4j=10rb)
* **PS 3**: Rp 4.000/jam (Paket: 2j=8rb, 3j=12rb, 4j=15rb)
* **PS 4**: Rp 5.000/jam (Paket: 4j=20rb + Bonus 30 menit)
* **PS 5**: Rp 10.000/jam (Paket: 4j=40rb + Bonus 30 menit)

## 🚀 Cara Penggunaan
1. Masukkan **PIN Kasir** (Default: `1234`).
2. Masukkan nama pelanggan.
3. Input nominal uang di kolom "+ UANG" untuk menambah durasi secara otomatis.
4. Gunakan tombol **STOP** untuk menjeda dan **RESET** untuk mengosongkan billing.

## 🛠️ Teknologi yang Digunakan
- HTML5 & CSS3 (Bootstrap 5)
- JavaScript (Vanilla JS)
- Google Apps Script (sebagai database laporan)
