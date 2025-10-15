# 🌐 Karthik's Portfolio Website

A modern and responsive personal portfolio website built using **HTML, TaiwindCSS, CSS, PHP, and PHPMailer**.  
It showcases my projects, skills, and includes a working **contact form** that sends emails securely using Gmail SMTP.

---

## 🚀 Features

- 🖥️ Fully responsive design (works on mobile, tablet, and desktop)
- 💼 Portfolio showcase with project cards
- 📬 Contact form integrated with **PHPMailer** for email delivery
- 🔐 Environment variables using `.env` for secure credentials
- 🎨 Clean dark theme with teal highlights

---

## 🛠️ Tech Stack

**Frontend:**
- HTML5
- Tailwind CSS 
- CSS3 (Custom styling, modern UI)

**Backend:**
- PHP  
- PHPMailer (SMTP mail integration)

**Tools:**
- XAMPP (Apache + PHP)
- Composer (dependency manager)
- Gmail SMTP (for sending messages)

---
## 📁 Folder Structure
Karthik_Portfolio/
│
├── assets/ # Images, icons, etc.
├── vendor/ # Composer dependencies (PHPMailer, Dotenv)
├── .env # Stores email credentials (not committed)
├── composer.json # PHP dependencies
├── contact.php # Contact form backend
├── portfolio.html # Main portfolio page
└── style.css # Styling for the entire website

## ⚙️ Setup Instructions
1 Clone the repository
git clone https://github.com/yourusername/Karthik_Portfolio.git
cd Karthik_Portfolio

2 Install Dependencies
composer install

3 Configure environment variables(Create a .env file in the root directory:)
GMAIL_USER=your_email@gmail.com
GMAIL_PASS=your_app_password

4 Run locally using XAMPP
Move the folder to C:\xampp\htdocs\
Start Apache in XAMPP Control Panel
Visit in your browser:
👉 http://localhost/Karthik_Portfolio/portfolio.html

5️ Test Contact Form
Fill the contact form — if configured correctly, you’ll receive an email at your Gmail inbox 🎉

🖼️ Screenshots:
<img width="1886" height="855" alt="Screenshot 2025-10-15 122453" src="https://github.com/user-attachments/assets/c43f9563-fc7a-474b-a50c-5d51aeb1f2a4" />
<img width="1888" height="618" alt="Screenshot 2025-10-15 122438" src="https://github.com/user-attachments/assets/9458822d-130b-4965-8efa-7c18fe62d031" />
<img width="1895" height="860" alt="Screenshot 2025-10-15 122421" src="https://github.com/user-attachments/assets/496accfa-27bb-4c46-987d-dcc2ca887518" />
<img width="1894" height="868" alt="Screenshot 2025-10-15 121443" src="https://github.com/user-attachments/assets/f551f064-ccf6-4581-965c-1275c9af5132" />
<img width="1885" height="864" alt="Screenshot 2025-10-15 121420" src="https://github.com/user-attachments/assets/5cf46145-8d25-4a72-b9a0-b1a8f016c307" />
