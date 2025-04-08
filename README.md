# 📝 BlogSystem

A fully functional Blog System built using **HTML, CSS, JavaScript, PHP, and MySQL**, with essential features like user authentication, blog posting, likes, comments, a follow system, and an admin panel for management.


---

## 📌 Features

- 🔐 User Registration & Login (Secure Auth)
- ✍️ Create, Edit, Delete Blog Posts
- 🧾 Comment System (Add & Delete Comments)
- ❤️ Like/Unlike Posts
- 👥 Follow/Unfollow Other Users
- 🧑‍💼 Admin Panel (Manage Users & Posts)
- 📸 Profile Picture & Bio Update
- 🔎 View Profiles with Posts & Stats
- 📅 Timestamps on Posts & Comments
- 📱 Responsive Design (Mobile-friendly)

---

Setup Database
Open phpMyAdmin or any MySQL interface.

Create a new database, e.g., blog_system.

Import the blog_system.sql file (provided in the ZIP or repo).

Update database credentials in includes/db.php.

php
Copy
Edit
$host = 'localhost';
$dbname = 'blog_system';
$user = 'root';
$pass = '';

---

Run the Project
Use XAMPP, WAMP, or Laragon

Place the folder in the /htdocs directory

Visit: http://localhost/Blog

---

🔐 Admin Panel
Login as Admin to access admin/ dashboard.

Admins can:

View and manage all users

View and manage all blog posts

Delete inappropriate comments or posts

admin login:

email: admin@gmail.com

password: 12345678

