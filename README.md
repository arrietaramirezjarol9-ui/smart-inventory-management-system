<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

---

## 💼 About This Project

**Smart Inventory Management System (SIGIV)** is a web application built with Laravel and MySQL for managing products, categories, and inventory efficiently.

This system includes authentication, role-based access (admin/user), dashboard analytics, and PDF report generation.

## 🎯 Project Objective

The main objective of this system is to provide an efficient and centralized solution for inventory management, allowing better control of products, categories, and stock levels in real time.

It aims to improve decision-making through data visualization and automated reports.

## ⚡ Features

- 🔐 Authentication system (Login/Register)
- 👑 Role-based access (Admin / User)
- 📦 Product management (CRUD)
- 🏷 Category management (CRUD)
- 📊 Dashboard with charts (Chart.js)
- ⚠️ Low stock alerts
- 📄 PDF export of products
- 🗃 MySQL database integration (phpMyAdmin)

## 👥 User Roles

### 👑 Administrator
- Manage products and categories
- Access dashboard analytics
- Export PDF reports
- Full system control

### 👤 Regular User
- View products
- View categories
- Access limited dashboard information

## 🛠 Tech Stack

- Laravel 12
- PHP 8+
- MySQL
- Bootstrap 5
- JavaScript
- Chart.js
- Blade Templates

## ⚙️ Requirements

- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL or MariaDB
- Laravel 12

## 🚀 Future Improvements

- Advanced user roles and permissions
- Email notifications for low stock
- Advanced analytics dashboard
- API integration for mobile app
- Multi-language support

## 📸 Capturas del sistema SIGIV

### 🔐 Login
![Login](https://github.com/arrietaramirezjarol9-ui/smart-inventory-management-system/blob/main/login.png?raw=true)

### 📊 Dashboard
![Dashboard](https://github.com/arrietaramirezjarol9-ui/smart-inventory-management-system/blob/main/dashboard.png?raw=true)

### 📦 Productos
![Products](https://github.com/arrietaramirezjarol9-ui/smart-inventory-management-system/blob/main/products.png?raw=true)

### 🏷 Categorías
![Categories](https://github.com/arrietaramirezjarol9-ui/smart-inventory-management-system/blob/main/categories.png?raw=true)

## 🚀 Installation

```bash
git clone https://github.com/arrietaramirezjarol9-ui/smart-inventory-management-system.git
cd smart-inventory-management-system
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
