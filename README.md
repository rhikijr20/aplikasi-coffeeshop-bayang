# ☕ Aplikasi Coffee Shop (Laravel)

Aplikasi Coffee Shop berbasis web yang dibangun menggunakan Laravel untuk mengelola pemesanan, produk, dan operasional toko secara digital.
Project ini dibuat sebagai bagian dari pengembangan skill backend dan fullstack web development.

---

## ✨ Fitur Utama

* 🔐 Sistem Login & Autentikasi
* 🛒 Manajemen Produk (Menu Coffee & Non-Coffee)
* 📦 Sistem Pemesanan / Order
* 📊 Dashboard Admin
* 👥 Manajemen User
* 💰 Pengelolaan Transaksi

---

## 🛠️ Tech Stack

* **Backend:** Laravel (PHP)
* **Frontend:** Blade, Bootstrap
* **Database:** MySQL
* **Tools:** Git & GitHub

---

## ⚙️ Cara Menjalankan Project

1. Clone repository

```bash id="1aa2b3"
git clone https://github.com/rhikijr20/aplikasi-coffeeshop-bayang.git
```

2. Masuk ke folder project

```bash id="4cc5d6"
cd aplikasi-coffeeshop-bayang
```

3. Install dependency

```bash id="7ee8f9"
composer install
```

4. Copy file environment

```bash id="0gg1h2"
cp .env.example .env
```

5. Generate application key

```bash id="3ii4j5"
php artisan key:generate
```

6. Setup database di `.env`, lalu jalankan:

```bash id="6kk7l8"
php artisan migrate
```

7. Jalankan server

```bash id="9mm0n1"
php artisan serve
```

8. Buka di browser:

```id="2oo3p4"
http://127.0.0.1:8000
```

---

## 📂 Struktur Fitur

* Authentication
* Dashboard Admin
* Manajemen Produk
* Sistem Order
* Manajemen User

---

## 🚀 Pengembangan Selanjutnya

* 📱 Tampilan mobile friendly
* 💳 Integrasi pembayaran (Midtrans / dll)
* 📊 Laporan penjualan
* 🧾 Cetak struk
* 📦 Manajemen stok otomatis

---

## 👨‍💻 Author

**Rhiki Yama Pratama**

* GitHub: https://github.com/rhikijr20

