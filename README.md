# Sitarina's 🍰⭐

**Sitarina's** adalah marketplace berbasis web yang dibangun menggunakan Bagisto. Platform ini digunakan untuk menjual produk homemade seperti cake dan mille crepes dari brand Sitarina's.

## 💌 Fitur Utama

- Registrasi dan login untuk pengguna
- Katalog produk
- Kategori produk
- Keranjang belanja
- Checkout & pembayaran
- Manajemen produk via admin panel
- Manajemen pesanan
- Dukungan multi-bahasa dan multi-kurensi

## 🛠️ Teknologi yang Digunakan

- Laravel
- Bagisto (Laravel e-commerce framework)
- PHP
- MySQL
- Composer

## 🍭 Cara Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/zahranur4/sitarina.s.git
   cd sitarina.s
2. **Install dependency menggunakan Composer**
   ```bash
   composer install
3. **Copy file environment**
   ```bash
   cp .env.example .env
4. **Generate application key**
   ```bash
   php artisan key:generate
5. **Set konfigurasi database di file .env**
   ```makefile
   DB_DATABASE=sitarinas_db
   DB_USERNAME=root
   DB_PASSWORD=
6. **Migrasi dan seed database**
   ```bash
   php artisan migrate
   php artisan db:seed
7. **Link storage**
   ```bash
   php artisan storage:link
8. **Jalankan server**
   ```bash
   php artisan serve
9. Akses aplikasi
 - Frontend: http://localhost:8000
 - Admin panel: http://localhost:8000/admin/login
 - Default email: admin@example.com
 - Default password: admin123
