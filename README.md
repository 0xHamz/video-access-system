<p align="center">
  <a href="https://github.com/username/video-access-system" target="_blank">
    <img src="https://via.placeholder.com/150x150.png?text=Logo" width="150" alt="Project Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/username/video-access-system/actions"><img src="https://img.shields.io/github/workflow/status/username/video-access-system/CI" alt="Build Status"></a>
  <a href="https://github.com/username/video-access-system"><img src="https://img.shields.io/github/issues/username/video-access-system" alt="Issues"></a>
  <a href="https://github.com/username/video-access-system"><img src="https://img.shields.io/github/license/username/video-access-system" alt="License"></a>
</p>

# Video Access System (Laravel 12)

Sistem ini dibuat untuk mengatur **akses menonton video** bagi customer oleh admin.  
Fitur utama:

- 2 level user: **Admin** dan **Customer**  
- Admin dapat CRUD data customer & video  
- Admin memberi akses customer menonton video dengan durasi tertentu  
- Customer dapat request akses video dan menonton sesuai izin  
- Notifikasi request realtime di panel admin  

---

## 📂 Struktur Repository
app/
Http/
Controllers/
Admin/
Customer/
Models/
database/
migrations/
seeders/
dumps/ <- file SQL database
resources/
views/
admin/
customer/
routes/
.env.example
README.md


---

## ⚡ Persiapan Project

1. Clone repository:

```bash
git clone https://github.com/username/video-access-system.git
cd video-access-system
```

2. Install dependencies:

```bash
composer install
npm install && npm run dev
```

3. Copy .env.example
```bash
cp .env.example .env
```

4. Edit .env sesuai environment lokal:
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_role_auth
DB_USERNAME=root
DB_PASSWORD=
```

5. Jalankan server lokal:
```bash
php artisan serve
```
