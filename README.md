# 🗂️ Sistem Informasi Project Monitoring Sederhana

[![Laravel](https://img.shields.io/badge/Laravel-10-red?logo=laravel)](https://laravel.com/)
[![PHP](https://img.shields.io/badge/PHP-8.1-blue?logo=php)](https://www.php.net/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

Website Laravel sederhana yang digunakan untuk mengelola data proyek seperti judul, project leader, tanggal mulai dan berakhir, nama klien, serta progress dan foto proyek.

---

## 👩‍💻 Dibuat oleh

**RIDHAWATI**  
D3 Teknik Informatika  
Politeknik Hasnur

---

## 📌 Fitur Aplikasi

- ✅ Menambahkan data proyek (judul, leader, tanggal, klien, progress)
- 📤 Upload foto proyek
- ✏️ Edit & 🗑️ hapus data proyek
- 📊 Tampilan tabel monitoring yang rapi
- 🎨 Desain dengan Tailwind CSS (nilai plus!)
- 🚫 Tanpa login (langsung akses)

---

## 🛠️ Teknologi yang Digunakan

- ⚙️ Laravel 10
- 🗄️ MySQL
- 💅 Tailwind CSS
- 🗃️ Laravel File Storage

---

## 📷 Screenshot Tampilan

### 📋 Daftar Project
![Daftar Project](screenshots/daftar_project.png)

### ➕ Tambah Project
![Tambah Project](screenshots/tambah_project.png)

### ✏️ Edit Project
![Edit Project](screenshots/edit_project.png)

---

## 🚀 Cara Menjalankan Project Secara Lokal

```bash
# 1. Clone repository
git clone https://github.com/Ridhaawati/Sistem-Monitoring.git

# 2. Masuk ke folder project
cd project-monitoring-sederhana

# 3. Install dependency Laravel
composer install

# 4. Salin file .env dan buat key aplikasi
cp .env.example .env
php artisan key:generate

# 5. Atur konfigurasi database di file .env

# 6. Jalankan migrasi database
php artisan migrate

# 7. Jalankan server lokal
php artisan serve
