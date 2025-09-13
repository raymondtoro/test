# 🐾 PawMart

PawMart adalah aplikasi web e-commerce yang dirancang khusus untuk mempermudah pemilik hewan peliharaan dalam membeli kebutuhan hewan secara online.  
Dengan adanya PawMart, pengguna dapat menjelajahi produk, menambahkan ke keranjang, hingga melakukan checkout dengan mudah.  
Admin juga memiliki dashboard untuk mengelola produk, kategori, dan transaksi.

---

## 🎯 Tujuan

- Mempermudah pemilik hewan membeli kebutuhan hewan peliharaan secara online.  
- Menyediakan platform penjualan produk hewan dengan sistem manajemen yang terintegrasi.  
- Memberikan pengalaman belanja yang nyaman dan efisien bagi pengguna.  
- Membantu admin mengelola produk, pesanan, dan user dalam satu sistem.  

---

## 🚀 Fitur Utama

### 👥 User
- Registrasi & Login  
- Manajemen profil  
- Jelajahi produk & detail produk  
- Keranjang belanja  
- Checkout & pembayaran  
- Riwayat pesanan  

### 🛒 Admin
- Login dashboard admin  
- CRUD Produk (Tambah/Edit/Hapus)  
- CRUD Kategori & Promo  
- Manajemen user  
- Monitoring pesanan & transaksi  

---

## 🛠️ Tech Stack
- **Backend**: Laravel 10 (PHP, MVC)  
- **Frontend**: Blade + Tailwind CSS  
- **Database**: MySQL  
- **Tools**:  
  - Figma (UI/UX Design)  
  - GitHub (Version Control)  
  - XAMPP (PHP & MySQL)  
  - Draw.io / Creately (Diagram)  
  - Google Docs (Dokumentasi)  

---

## ⚡ Instalasi

```bash
# 1. Clone repo
git clone https://github.com/raymondtoro/PawMart.git
cd PawMart

# 2. Install dependency
composer install
npm install && npm run dev

# 3. Konfigurasi .env
cp .env.example .env
php artisan key:generate

# 4. Migrasi database
php artisan migrate --seed

# 5. Jalankan server lokal
php artisan serve
