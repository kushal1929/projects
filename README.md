# Online Railway Reservation System

## Overview
The Online Railway Reservation System is a web-based application that allows users to book railway tickets online. The system is built using **PHP, JavaScript, HTML, and CSS** and requires **XAMPP** to run.

---

## Features
- User Registration & Login
- Train Search & Booking
- Ticket Management
- Payment Integration (if applicable)
- Admin Panel for Managing Trains & Bookings
- Responsive UI

---

## Requirements
- **XAMPP** (Apache, MySQL, PHP)
- A Web Browser (Chrome, Firefox, Edge, etc.)

---

## Installation & Setup Guide

### Step 1: Download & Extract the Project
1. Download the project files from the repository.
2. Extract the project folder.
3. Rename the folder to `orrs` (Optional but recommended).

### Step 2: Move Files to XAMPP htdocs
1. Copy the entire `orrs` folder.
2. Navigate to `C:\xampp\htdocs`.
3. Paste the `orrs` folder inside `htdocs`.

### Step 3: Start XAMPP Server
1. Open **XAMPP Control Panel**.
2. Start **Apache** and **MySQL** services.

### Step 4: Setup Database
1. Open a browser and go to `http://localhost/phpmyadmin/`.
2. Click on **Databases** and create a new database named **orrs**.
3. Import the provided **database.sql** file:
   - Click on the **orrs** database.
   - Go to the **Import** tab.
   - Choose the `database.sql` file from the project folder.
   - Click **Go** to import the database.

### Step 5: Run the Application
1. Open a browser.
2. Go to `http://localhost/orrs/`
3. The application should now be running.

---

## Default Credentials (if applicable)
- **Admin Login:**
  - Username: `admin`
  - Password: `admin123`
- **User Login:** (You can register a new account)

---

## Troubleshooting
- If the page does not load, ensure **Apache** and **MySQL** services are running in XAMPP.
- If the database is not connected, check `config.php` to ensure correct database credentials.
- If any errors occur, check the **XAMPP error log** in `C:\xampp\apache\logs\error.log`.

---

## Contributors
-B N KUSHAL
-BINDU G

-----

