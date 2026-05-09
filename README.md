Course Registration System
Purpose
This is a dynamic management website for the Internet Computing project. It uses PHP and MySQL to manage student enrollments.

Technologies Used
PHP

MySQL

HTML

CSS

InfinityFree Hosting

000webhost Hosting

Features
Secure login system

Student enrollment

Admin dashboard

Manage courses

Manage sessions

MySQL database connection

Local Setup Using XAMPP
Install and open XAMPP.

Start Apache and MySQL.

Copy this folder into: C:\xampp\htdocs\course-registration

Open phpMyAdmin: http://localhost/phpmyadmin

Import SQL File.

Open: http://localhost/course-registration

Important Database Config
The database connection is inside includes/config.php.
For local XAMPP:
define('DB_HOST', 'localhost');
define('DB_NAME', 'onlinecourse');
define('DB_USER', 'root');
define('DB_PASS', '');

For InfinityFree or 000webhost, replace these values with the database details from the hosting control panel.

InfinityFree Deployment
Create an InfinityFree account.

Create a free hosting account/subdomain.

Open the control panel.

Create a MySQL database.

Open phpMyAdmin and import SQL File.

Edit config.php using your hosting database host, name, username, and password.

Upload all website files to the hosting folder, usually htdocs.

Open your live URL and test the site.

000webhost Deployment
Create a 000webhost free account.

Create a free website name.

Create a MySQL database from the control panel.

Import SQL File using phpMyAdmin.

Edit config.php with the 000webhost database credentials.

Upload the website files using File Manager to public_html.

Open your live URL and test the site.

Deployment Links
InfinityFree Live URL: [Pending]

000webhost Live URL: [Pending]
