<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=150&section=header&text=%20Book%20Store&fontSize=38&fontColor=fff&animation=fadeIn&fontAlignY=40&desc=Library%20Management%20System&descAlignY=62&descSize=16" width="100%"/>

[![Laravel](https://img.shields.io/badge/Laravel-1a1a2e?style=for-the-badge&logo=laravel&logoColor=FF2D20)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-1a1a2e?style=for-the-badge&logo=php&logoColor=c9b8ff)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-1a1a2e?style=for-the-badge&logo=mysql&logoColor=4479A1)](https://mysql.com)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-1a1a2e?style=for-the-badge&logo=bootstrap&logoColor=7952B3)
![Sanctum](https://img.shields.io/badge/Sanctum-1a1a2e?style=for-the-badge&logo=laravel&logoColor=FF2D20)

</div>

---

## About

**Book Store** is a web application for library management built with **Laravel** and **Bootstrap 5**.

It offers two sides — a **user interface** for browsing books, searching titles, and managing borrowings, and an **admin dashboard** for managing books, authors, categories, and tracking borrowing records.

---

## Features

-  **Books** — CRUD · cover image · availability status
-  **Authors** — CRUD · biography · nationality
-  **Borrowings** — CRUD · status tracking · export PDF & Excel
-  **Authentication** — Sign up · Login · powered by **Laravel Breeze** with token-based auth

---

## Tech Stack

<div align="center">

![Laravel](https://img.shields.io/badge/Laravel-1a1a2e?style=for-the-badge&logo=laravel&logoColor=FF2D20)
![PHP](https://img.shields.io/badge/PHP-1a1a2e?style=for-the-badge&logo=php&logoColor=c9b8ff)
![MySQL](https://img.shields.io/badge/MySQL-1a1a2e?style=for-the-badge&logo=mysql&logoColor=4479A1)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-1a1a2e?style=for-the-badge&logo=bootstrap&logoColor=7952B3)
![JavaScript](https://img.shields.io/badge/JavaScript-1a1a2e?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Git](https://img.shields.io/badge/Git-1a1a2e?style=for-the-badge&logo=git&logoColor=F05032)

</div>

---

## Installation

```bash
# 1. Clone the repository
git clone https://github.com/sahlinour/Book-Store.git

# 2. Navigate to the project
cd Book-Store

# 3. Install dependencies
composer install

# 4. Copy environment file
cp .env.example .env

# 5. Generate app key
php artisan key:generate

# 6. Configure your database in .env
DB_DATABASE=book_store
DB_USERNAME=root
DB_PASSWORD=

# 7. Run migrations
php artisan migrate

# 8. Link storage
php artisan storage:link

# 9. Start the server
php artisan serve
```

---

## Database Structure

| Table | Description |
|-------|-------------|
| `users` | Library users |
| `auteurs` | Book authors |
| `livres` | Book catalogue |
| `emprunts` | Borrowing records |
| `personal_access_tokens` | Sanctum API tokens |

---

<div align="center">

developed by [Nour El Houda Sahli](https://github.com/sahlinour)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
