INASTORE: Web Penjualan Buku dengan Laravel

INASTORE adalah platform e-commerce berbasis web untuk penjualan buku online yang dibangun dengan Laravel. Dengan INASTORE, pengguna dapat dengan mudah membeli buku, dan admin dapat mengelola koleksi buku, transaksi, serta pengguna.

Fitur Utama:
- Pengelolaan Buku: Menambah, mengedit, dan menghapus buku dengan detail seperti judul, penulis, harga, dan stok.
- Sistem Pembayaran: Pengguna dapat melakukan pembelian buku dengan berbagai metode pembayaran.
- Autentikasi Pengguna: Login dan registrasi pengguna dengan sistem Laravel Auth yang aman.
- Membaca Buku : Pengguna bisa membaca yang sudah di beli di halaman buku saya.

Teknologi yang Digunakan:
- Backend: Laravel (PHP Framework)
- Frontend: Blade Templating, Bootstrap (CSS Framework)
- Database: MySQL

Instalasi:
1. Clone Repository:
   git clone https://github.com/Andisaster/INATECHNOSTORE.git

2. Install Dependensi:
   Pindah ke direktori proyek dan install dependensi menggunakan Composer:
   cd inastore
   composer install

3. Konfigurasi Lingkungan:
   Salin file .env.example menjadi .env dan sesuaikan konfigurasi basis data:
   cp .env.example .env
   php artisan key:generate

4. Migrasi Database:
   Jalankan migrasi untuk membuat tabel-tabel di database:
   php artisan migrate

5. Jalankan Aplikasi:
   Jalankan aplikasi menggunakan Artisan server:
   php artisan serve
   Akses aplikasi di http://localhost:8000

Kontribusi:
Jika Anda tertarik untuk berkontribusi, silakan fork repository ini dan buat pull request dengan perubahan Anda. Pastikan untuk mengikuti pedoman kontribusi dan menulis deskripsi perubahan yang jelas.
