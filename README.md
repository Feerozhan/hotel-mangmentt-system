<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<h1 align="center">🏨 Hotel Management System</h1>

<p align="center">
A Laravel 10 based hotel booking & room management system with full admin panel, room availability filter, and secure booking flow.
</p>

---

## 📚 Overview

This system allows guests to check room availability based on dates, view facilities, and make reservations.  
Admin can manage rooms, bookings, and room visibility using a dedicated dashboard.

---

## 🛠 Technology Stack

| Technology | Usage |
|-----------|--------|
| Laravel 10 | Backend Framework |
| Blade Templates | UI Templates |
| Eloquent ORM | Database Handling |
| MySQL | Database |
| Authentication (Laravel Breeze/Default) | Secure Login System |
| Migrations & Seeders | DB Setup |

---

## ✨ Features

### 👤 User Side
- Register/Login system
- Check room availability by check-in & check-out date
- View room details, pricing, facilities
- Book room & track via **My Bookings**
- Update profile
- Input validation & error handling

### 🔐 Admin Side
- Secure Admin Login
- Dashboard with:
  - Add / Edit / Delete Rooms
  - Set Room Visibility (Show/Hide)
  - View all bookings
- Room inventory management

---

## 📸 Demo Screens

### Reservation Page
![userside](https://github.com/ramezcode1/hotelManagement/assets/135148978/fc2feeb3-c21c-4dc4-83b8-2dc115225386)

### Admin Dashboard
![dashboard](https://github.com/ramezcode1/hotelManagement/assets/135148978/f876a480-efb4-4482-b78f-bbc9859d4e53)

---

## 🔌 Installation Guide

```bash
git clone <your-repo-url>
cd project-folder
composer install
cp .env.example .env   # Update DB credentials
php artisan key:generate
php artisan migrate --seed
php artisan serve
---

<p align="center">Made with ❤️ by <strong>Feeroz Khan</strong></p>

---

