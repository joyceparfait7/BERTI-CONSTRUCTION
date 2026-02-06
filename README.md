🏗️ BERTI CONSTRUCTION – Learning E‑commerce Project
📌 Project Overview

BERTI CONSTRUCTION is a small web project I built as a learning exercise while studying web development and cybersecurity.

The goal of this project is not to be a full production‑ready e‑commerce platform, but to:

Practice HTML, CSS, JavaScript, PHP, and MySQL

Understand authentication basics (login & registration)

Learn client‑side vs server‑side security limits

Experiment safely with common web vulnerabilities and defenses

🧰 Technologies Used

Frontend

HTML5

CSS3

Vanilla JavaScript

Backend

PHP (procedural)

MySQL (via MySQLi + prepared statements)

Environment

XAMPP (Apache + MySQL)

Git & GitHub for version control

✨ Features

Product listing page (static products)

Client‑side shopping cart (JavaScript + localStorage)

User registration with password hashing

User login with session handling

WhatsApp order redirection

Basic search functionality

⚠️ Security Notice (Important)

This project is intentionally simple and not production‑ready.

What this project does NOT include:

❌ Real payment gateway

❌ Server‑side cart validation

❌ CSRF protection

❌ Rate limiting

❌ Advanced access control

Why?

Because this project is used to learn how attacks work and why defenses are necessary.

🔐 Database & Configuration

Sensitive files are excluded from version control.

Ignored files include:

db_connect.php

.env

Example database config

Create your own db_connect.php locally:

<?php
$conn = new mysqli("localhost", "root", "", "berti_db");
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>

⚠️ Never upload real credentials to GitHub

🧪 Educational Focus (Cybersecurity)

This project helped me understand:

Why JavaScript cannot be trusted for security

How SQL injection works and how bind_param() prevents it

Why password hashing is mandatory

How attackers abuse:

Client‑side logic

Public repositories

Weak authentication flows

🚀 How to Run Locally

Install XAMPP

Clone the repository

Place the project in:

htdocs/

Create a MySQL database

Create db_connect.php locally

Start Apache & MySQL

Open:

http://localhost/berti-construction
📚 Disclaimer

This project is:

For learning and experimentation only

Not intended for real commercial use

Built while exploring web security fundamentals

👤 Author

Built by a cybersecurity student exploring:

Web security

Backend vulnerabilities

Secure coding practices

🧠 Final Note

If you are reviewing this project:

Assume educational intent

Security weaknesses are intentional learning points

Feedback is welcome 🙌