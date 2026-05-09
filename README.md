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
```
### For Online Hosting (InfinityFree/ByetHost):
Replace these values with the database details provided in your hosting control panel.

### InfinityFree Deployment
* **Create** an InfinityFree account.
* **Create** a free subdomain (e.g., `ziad-ezzat-web`).
* **Open** the control panel and create a MySQL database.
* **Open** phpMyAdmin and import `database.sql`.
* **Edit** `config.php` using your InfinityFree database host, name, username, and password.
* **Upload** all website files to the `htdocs` folder.

### ByetHost Deployment (Second Hosting)
* **Create** a ByetHost account and activate via email.
* **Open** the VistaPanel control panel.
* **Create** a MySQL database (e.g., `b14_41876932_loginsystem`).
* **Import** `database.sql` using phpMyAdmin.
* **Edit** `config.php` with ByetHost credentials:
  * **Host:** `sql301.byethost14.com`
  * **User:** `b14_41876932`
* **Upload** all files into the `htdocs` folder using Online File Manager.

### Deployment Links
* **InfinityFree Live URL:** [https://technomindblog.lovestoblog.com/](https://technomindblog.lovestoblog.com/)
* **ByetHost Live URL:** [http://dynamicproject.byethost14.com/](http://dynamicproject.byethost14.com/)

### Screenshots
* Screenshots of the deployment process, database setup, and the live website are located in the `screenshots` folder.

 
