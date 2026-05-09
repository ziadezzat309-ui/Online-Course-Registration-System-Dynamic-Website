# Website 2 - Dynamic PHP & MySQL Login System

## Purpose
This is a dynamic User Management and Login System for the Faculty of Computers and Artificial Intelligence (FCAI) project. It uses PHP and MySQL to manage user registration, authentication, and profile management.

---

## Technologies Used
* **PHP** (Server-side scripting)
* **MySQL** (Database management)
* **HTML & CSS** (UI/UX Design)
* **InfinityFree** (Main Hosting)
* **ByetHost** (Second Hosting)

---

## Features
* User Registration & Secure Login System
* Password Recovery
* Profile Management (View & Edit)
* Secure Logout
* Dynamic MySQL database connection

---

## Local Setup Using XAMPP
1. Install and open **XAMPP**.
2. Start **Apache** and **MySQL**.
3. Copy the project folder into: `C:\xampp\htdocs\dynamic-login-system`
4. Open phpMyAdmin: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
5. Import your `database.sql` file.
6. Access the project: [http://localhost/dynamic-login-system](http://localhost/dynamic-login-system)

---

## Important Database Config
The database connection is managed inside `config.php`.

### **For Local XAMPP:**
```php
define('DB_SERVER', 'localhost');
define('DB_NAME', 'loginsystem');
define('DB_USER', 'root');
define('DB_PASS', '');
