
# Video Access System (Laravel 12)

Sistem ini dibuat untuk mengatur **akses menonton video** bagi customer oleh admin.  
Fitur utama:

- 2 level user: **Admin** dan **Customer**  
- Admin dapat CRUD data customer & video  
- Admin memberi akses customer menonton video   
- Customer dapat request akses video dan menonton sesuai izin  
- Notifikasi request realtime di panel admin  

---

## ⚡ Persiapan Project

1. Clone repository:

```bash
git clone https://github.com/0xHamz/video-access-system.git
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

6. Uji Coba di Lokal
- Buka http://127.0.0.1:8000 / localhost
- Admin & Customer Login
```bash
| User Level | Email                | Password    |
| ----------- | ------------------- | ----------- |
| Admin       | admin@gmail.com   | 121212 |
| Customer 1  | customer1@gmail.com | 121212 |
| Customer 2  | customer2@gmail.com | 121212 |
```
