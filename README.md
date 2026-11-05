# ☕ KopiNyantuy - Self Service Kiosk Web Application

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-6B8A5A?style=for-the-badge&logo=github)](https://mazg-94a150.github.io/kopinyantuy-self-service/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**KopiNyantuy Self-Service Kiosk** adalah aplikasi web interaktif yang dirancang khusus untuk memesan menu kopi secara mandiri (*self-service kiosk*). Dibuat dengan arsitektur *Single Page Application* (SPA) yang cepat, modern, dan responsif dengan integrasi pengiriman pesanan langsung ke WhatsApp Kasir.

---

## 👥 Profil Kelompok & Tugas

**Mata Kuliah:** Antar Muka Komputer  
**Kelompok:** 2  

| No. | Nama Anggota | NIM |
| :---: | :--- | :---: |
| 1 | **Cahya Heryana** | 2503321094 |
| 2 | **Ghaisan Adiend Fathan Al adli** | 2503321067 |
| 3 | **Muhammad Rahsya Erlangga** | 2503321084 |

---

## 🔗 Live Demo Web
🌐 **Coba Aplikasi Kiosk Langsung:** [https://mazg-94a150.github.io/kopinyantuy-self-service/](https://mazg-94a150.github.io/kopinyantuy-self-service/)

---

## 📸 Tampilan Antarmuka Aplikasi

### 1. Layar Selamat Datang (Welcome Screen)
Halaman awal kiosk yang ramah pengguna untuk memulai pesanan.
![Layar Selamat Datang](https://raw.githubusercontent.com/mazg-94a150/kopinyantuy-self-service/main/welcome-screen.png)

### 2. Layar Pemilihan Menu (Menu Screen)
Daftar pilihan kopi & snack lengkap dengan filter kategori, harga, dan tombol pemicu keranjang.
![Layar Pemilihan Menu](https://raw.githubusercontent.com/mazg-94a150/kopinyantuy-self-service/main/menu-screen.png)

### 3. Layar Metode Pembayaran & Form Pelanggan (Payment Screen)
Form pengisian nama pemesan, nomor meja/keterangan, serta pilihan metode pembayaran.
![Layar Pembayaran](https://raw.githubusercontent.com/mazg-94a150/kopinyantuy-self-service/main/payment-screen.png)

---

## 🌟 Fitur Utama

- **📱 Single Page Application (SPA):** Perubahan layar yang cepat dari *Welcome Screen*, *Menu Selection*, hingga *Payment Method* tanpa memuat ulang halaman.
- **🎨 Sage & Cream Color Palette:** Desain visual yang estetik dan menenangkan sesuai *branding* cafe kekinian (`#6B8A5A` Sage Green & `#EEF3E5` Cream).
- **🛒 Dynamic Cart & Price Calculation:** Menghitung total belanja secara otomatis beserta rekapitulasi jumlah item pesanan dalam format Rupiah (IDR).
- **👤 Input Data Pelanggan:** Menyediakan form pengisian Nama Pemesan dan Nomor Meja / Status Pesanan (Dine-in / Takeaway).
- **💬 Direct WhatsApp Notification:** Integrasi langsung dengan API WhatsApp (`wa.me`) untuk mengirim rincian nota pesanan secara otomatis ke HP Kasir.

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Fungsi |
| :--- | :--- |
| **HTML5** | Struktur elemen UI dan pembagian layar SPA |
| **CSS3** | Penataan tata letak (Flexbox & Grid), variabel warna (`:root`), dan efek interaktif |
| **Vanilla JavaScript** | Logika keranjang belanja, manipulasi DOM, kalkulasi harga, dan pemformatan URL WhatsApp |

---

## 📋 Alur Pemesanan (User Flow)

1. **Layar Utama:** Pelanggan menekan tombol *"Pesan Sekarang"* untuk masuk ke antarmuka menu.
2. **Pilih Menu:** Pelanggan memilih berbagai varian kopi atau pastry favorit.
3. **Form Pembayaran & Data:** Pelanggan menginput **Nama Pemesan**, **Nomor Meja**, dan memilih **Metode Pembayaran** (QRIS, Kartu, atau Cash).
4. **Checkout:** Pelanggan menekan tombol *"Selesaikan Pembayaran"* dan pesanan akan terkirim dalam bentuk nota teks otomatis ke WhatsApp Kasir.

---

## 📁 Struktur Repositori

```text
kopinyantuy-self-service/
├── index.html          # Kode utama antarmuka & logika JS
├── style.css           # File stylesheet desain visual
├── welcome-screen.png  # Gambar preview layar utama
├── menu-screen.png     # Gambar preview daftar menu
├── payment-screen.png  # Gambar preview pembayaran
└── README.md           # Dokumentasi resmi proyek
