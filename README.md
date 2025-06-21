# Gym-Management-Master


# 💻 Login PHP, MySQL, HTML, CSS, Bootstrap, and JavaScript

A complete full-stack web-based built using:

* PHP for backend logic
* MySQL for database handling
* HTML, CSS, Bootstrap for frontend design
* JavaScript for interactivity and validation



## 🌐 Features

### 🔐 User Authentication

* Admin login panel
* Username and password management
* MySQL-based credential validation

### 📝 Appointment Booking

* Submit appointment details (name, email, contact)
* Store in `doctorapp` table
* Dynamic booking linked to doctor IDs

### 💳 Payment Handling

* Record payments with method (cash/card/cheque)
* Relational mapping between customer and payment via `customer_id`

### 🏋️ Trainer & Package Management

* View available fitness packages
* Trainer directory with contact info
* Link appointments to specific packages and trainers

### 📄 Database Design (MySQL)

Included SQL file creates and populates the following tables:

* `logintb` – Admin credentials
* `doctorapp` – Appointment details
* `Package` – Fitness programs
* `Payment` – Payment logs
* `Trainer` – Trainer info

---

## 🧱 Technology Stack

| Layer         | Technology               |
| ------------- | ------------------------ |
| Frontend      | HTML5, CSS3, Bootstrap 4 |
| Interactivity | JavaScript               |
| Backend       | PHP 7+                   |
| Database      | MySQL / MariaDB          |
| Tools         | phpMyAdmin               |

---

## 📂 Project Structure

```
/project-root
│
├── /css/
│   └── style.css
├── /js/
│   └── script.js
├── /php/
│   ├── login.php
│   ├── appointment.php
│   └── process_payment.php
├── index.html
├── dashboard.php
├── README.md
└── loginsystem.sql    ← DATABASE IMPORT FILE
```

---

## 🧪 Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/project-name.git
   ```

2. **Import the Database**

   * Open phpMyAdmin
   * Create a database named `loginsystem`
   * Import `loginsystem.sql`

3. **Configure Localhost**

   * Place project folder inside `htdocs` (for XAMPP) or `www` (for WAMP)
   * Start Apache & MySQL from control panel

4. **Open in Browser**

   ```
   http://localhost/project-folder-name/
   ```

---

## 📊 Sample Admin Credentials

* **Username**: `admin`
* **Password**: `pass`

---

## 🎯 Use Cases

* Gym or clinic management system
* Admin dashboard and customer handling
* Beginner-level full-stack practice
* College/university semester project

---

## 📃 License

This project is open-source under the [MIT License](LICENSE).

---

Let me know if you'd like a [ER diagram for database](f), [live demo setup guide](f), or [screenshots for your GitHub README](f).
