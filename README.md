# Smart Clinic Management System

## Overview
Smart Clinic Management System is a comprehensive, responsive web application that digitizes clinic operations. It provides secure portal access for Admins, Doctors, and Patients to handle registrations, book appointments, manage schedules, and store medical records. 

## Features
- **Patient Portal:** Register accounts, view available doctors by specialization, book and manage appointments, and view electronic prescriptions.
- **Doctor Dashboard:** Manage daily schedules, accept/cancel appointments, conduct electronic consultations, and attach digital prescriptions.
- **Admin Panel:** Complete oversight of the platform, including user administration (patients and doctors), analytics, and system settings.
- **Responsive Design:** A seamless, mobile-friendly experience across desktop and mobile devices.
- **Security:** Role-Based Access Control (RBAC), hashed passwords, and protection against common Web security vulnerabilities.

## Tech Stack
- **Frontend:** HTML5, CSS3, ES6 JavaScript
- **Backend:** PHP (7.4/8.x)
- **Database:** MySQL / MariaDB
- **Server:** Apache HTTP Server (via XAMPP)

## Installation Guide
1. **Prerequisites:** Install [XAMPP](https://www.apachefriends.org/index.html) (or any equivalent LAMP/WAMP stack).
2. **Setup Directory:** Clone or copy the project folder into your server's public directory (e.g., `C:\xampp\htdocs\` for XAMPP).
3. **Database Configuration:**
   - Open your local PHPMyAdmin (`http://localhost/phpmyadmin/`).
   - Create a new, empty database named `smart_clinic_db`.
   - Import the provided `.sql` dump file located within the `/database/` folder of the project.
4. **Launch:** Start the Apache and MySQL modules from the XAMPP Control Panel.
5. **Access the App:** Open your web browser and navigate to `http://localhost/Smart Clinic/index.php` (adjust path if your folder name is different).

## Default Admin Credentials (For Testing)
- **Portal URL:** `http://localhost/Smart Clinic/admin-login.php`
- **Email:** `admin@smartclinic.com`
- **Password:** `admin123`

> **Note:** Ensure you change these default credentials immediately before migrating to a production environment. 
