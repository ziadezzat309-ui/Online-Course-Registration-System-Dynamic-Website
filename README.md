# Course Registration System

### Purpose
This is a dynamic management website for the Internet Computing project. It uses PHP and MySQL to manage student enrollments.

### Technologies Used
* PHP
* MySQL
* HTML
* CSS
* JS
* InfinityFree Hosting
* 000webhost Hosting

### Features
* Secure login system
* Student enrollment
* Admin dashboard
* Manage courses
* Manage sessions
* MySQL database connection

### Local Setup Using XAMPP
1. Install and open XAMPP.
2. Start Apache and MySQL.
3. Copy this folder into: `E:\xampp\htdocs\loginsystem`
4. Open phpMyAdmin: http://localhost/phpmyadmin
5. Import SQL File.
6. Open: http://localhost/loginsystem/

### Important Database Config
The database connection is inside `includes/config.php`.

For local XAMPP:
* `define('DB_HOST', 'localhost');`
* `define('DB_NAME', 'onlinecourse');`
* `define('DB_USER', 'root');`
* `define('DB_PASS', '');`

For InfinityFree or 000webhost, replace these values with the database details from the hosting control panel.

### InfinityFree Deployment
1. Create an InfinityFree account.
2. Create a free hosting account/subdomain.
3. Open the control panel.
4. Create a MySQL database.
5. Open phpMyAdmin and import SQL File.
6. Edit `config.php` using your hosting database host, name, username, and password.
7. Upload all website files to the hosting folder, usually `htdocs`.
8. Open your live URL and test the site.

### 000webhost Deployment
1. Create a 000webhost free account.
2. Create a free website name.
3. Create a MySQL database from the control panel.
4. Import SQL File using phpMyAdmin.
5. Edit `config.php` with the 000webhost database credentials.
6. Upload the website files using File Manager to `public_html`.
7. Open your live URL and test the site.

### Deployment Links
* InfinityFree Live URL: [https://course-system-fcai.infinityfree.me/]
* 000webhost Live URL: [Pending]

### Screenshots
Add screenshots of deployment steps inside the screenshots folder.
