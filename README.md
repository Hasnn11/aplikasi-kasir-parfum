# 📊 Ar-Razak Parfume - Point of Sales (POS) & Dashboard

Aplikasi kasir (Point of Sales) dan dashboard analitik berbasis web yang dibuat khusus untuk manajemen penjualan toko parfum. 

## ✨ Fitur Utama
* **Sistem Autentikasi:** Login aman untuk admin/kasir menggunakan Firebase Authentication.
* **Dashboard Analitik:** Visualisasi data omset harian dan parfum terlaris secara *real-time* menggunakan **Chart.js**.
* **Manajemen Transaksi (Kasir):** Perhitungan harga dinamis berdasarkan ukuran botol (5ml, 10ml, Full) dan fitur tambahan botol kosong.
* **Manajemen Master Data:** CRUD (Create, Read, Update, Delete) data produk parfum beserta variasi harganya.
* **Cetak Laporan PDF:** Export riwayat penjualan ke format PDF menggunakan **jsPDF**.
* **Real-time Database:** Sinkronisasi data instan menggunakan **Firebase Firestore**.

## 🛠️ Teknologi yang Digunakan
* **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN)
* **Backend/BaaS:** Firebase (Firestore & Authentication)
* **Library Eksternal:** Chart.js (Grafik), jsPDF (Export PDF)

## 🚀 Cara Menjalankan Project (Local)
Karena project ini tidak menggunakan *bundler*, Anda bisa langsung menjalankannya dengan cara:
1. Clone repositori ini: `git clone https://github.com/username-anda/aplikasi-kasir-parfum.git`
2. Buka file `index.html` di browser Anda.
3. *Catatan:* Masukkan konfigurasi Firebase Anda sendiri di bagian `firebaseConfig` pada file `index.html` agar database dapat terhubung.
