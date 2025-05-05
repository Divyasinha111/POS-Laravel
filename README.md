# POS-Laravel Project
# 🛒 POS and Inventory Management System (Laravel)

A fully functional Point of Sale (POS) and Inventory Management System built with **Laravel** framework. This project is ideal for learning and demonstration purposes, especially for IT students and beginner developers. It supports user roles (Admin, Clerk, Cashier), sales reporting, inventory control, and a real-time POS interface.

---

## 📦 Features

- ✅ Admin Panel
- 🧾 Point of Sale (POS) System
- 📦 Inventory Management
- 🗂 Category Management
- 📊 Daily/Weekly/Monthly/Yearly Sales Reports
- 👤 User Management (Admin, Clerk, Cashier roles)
- 🔐 Role-Based Access Control
- 🎨 Clean UI with Bootstrap 4

---

## 🛠️ Tech Stack

- **Backend:** PHP (Laravel Framework)
- **Frontend:** Blade Templating + Bootstrap
- **Database:** MySQL
- **Version:** Laravel 8 / 9 (Compatible)
- **Optional:** Laravel Mix for asset compilation

---

## 🚀 Installation

### 1. Clone the Repository

bash
1. git clone https://github.com/Divyasinha111/POS-Laravel
cd pos-laravel

2. Install PHP Dependencies
   composer install
   
4. Install JavaScript Dependencies
   npm install && npm run dev
   
5. Configure Environment
   cp .env.example .env
   php artisan key:generate

Update .env with your database credentials:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password

6. Run Migrations and Seeders
   php artisan migrate --seed

7.  Serve the Application
    php artisan serve

    

👤 User Roles & Access
Role	 Username	 Password	    Permissions
Admin	 admin	     admin123	    Full access
Clerk	 clerk	     clerk123	    Manage inventory and view reports
Cashier	 cashier	 cashier123	    Access POS only

You can edit these in the seeders or Users table directly.









