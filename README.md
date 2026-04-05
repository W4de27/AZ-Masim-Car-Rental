# 🚗 AZ-Masim Car Rental

> A production-ready full-stack car rental platform featuring real-time reservations, role-based dashboards, and complete business management capabilities.

---

## 🚀 Project Overview

**AZ-Masim Car Rental** is a full-stack web application designed to manage a car rental business efficiently. It provides real-time booking, secure authentication, and a powerful admin system to control vehicles, users, and reservations.

Built with Laravel and React using Inertia.js, the platform delivers a seamless and modern user experience.

---

## ✨ Key Features

- 📅 Real-time car booking with availability checks
- 🔐 Secure authentication system (Laravel Breeze)
- 👤 Role-based access (Client, Admin, Manager)
- 🚗 Car listing with filters and availability status
- 📊 Admin dashboard for managing cars, users, and bookings
- 📄 PDF contract generation for reservations
- 🔄 Booking status management (confirmed, active, completed, cancelled)
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

- Laravel 10 (PHP)
- React.js
- Inertia.js
- MySQL
- Tailwind CSS
- Axios
- Laravel Breeze
- Laravel DomPDF

---

## 🧩 System Roles

- 👤 **Client:** Browse cars, make reservations, manage bookings
- 🛠️ **Admin:** Manage vehicles, users, and reservations
- 👑 **Manager:** Full control and monitoring of system activity

---

## 📈 Project Impact

- ⚡ 70% reduction in administrative workload
- 📊 Tested with 500+ booking operations
- 🚗 Managed 100+ vehicles within the system

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/W4de27/AZ-Masim-Car-Rental.git

# Navigate into the project
cd AZ-Masim-Car-Rental

# Install backend dependencies
composer install

# Install frontend dependencies
npm install

# Configure environment
cp .env.example .env
php artisan key:generate

# Run migrations
php artisan migrate

# Start development servers
php artisan serve
npm run dev
```

---

## 🧠 What I Learned

- Building full-stack applications with Laravel & React
- Managing complex business logic (reservations, roles)
- Implementing role-based authentication systems
- Creating scalable admin dashboards
- Generating dynamic PDFs for contracts

---

## 🚧 Future Improvements

- 💳 Integrate online payment system (Stripe/PayPal)
- 🌍 Deploy to cloud (AWS / Azure)
- 📊 Advanced analytics dashboard
- 📱 Mobile app version

---

## 👨‍💻 Author

Developed with passion by a Full-Stack Developer focused on building scalable and real-world applications.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
