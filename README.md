# 📚 Library Management System (LMS)

Welcome to my **Library Management System** project! This system is designed to convert manual, paper-based library operations into a more **efficient, web-based application**.

While I explored some open-source LMS projects for inspiration and learning, I have **significantly improved and extended the functionality** to better suit practical needs. The system supports managing books, students, and issuing records, and includes enhanced features like:

- 🔐 Captcha Verification  
- 🔒 Password Encryption  
- 📊 Report Generation (including Overdue and User-wise reports)  
- 💸 Fine Management  
- 📦 Book Category & Publication Management  
- 📁 Organized Admin & Student Dashboards  

---

## 🚀 Features I Implemented / Enhanced

- Redesigned user flows and admin dashboard UI
- Added **advanced reporting** features for overdue and user-based summaries
- Improved the **book issue/return logic** to include real-time fine calculation
- Included security features like **password hashing** and **captcha**
- Set up proper **data validation and error handling** in forms
- Optimized SQL queries and added relationships to improve efficiency
- Worked on the **frontend styling** using HTML5 & CSS
- Cleaned and documented the PHP backend logic for maintainability

---

## 🛠 Getting Started (Local Setup)

### Prerequisites
- Basic understanding of PHP, MySQL, HTML/CSS
- [XAMPP](https://www.apachefriends.org/download.html) (or any local server)

### Steps:
1. Clone/download this repository and extract it.
2. Move the folder to `C:\xampp\htdocs\your-folder-name`
3. Start Apache and MySQL using XAMPP Control Panel
4. Go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin) and:
   - Create a new database named `library`
   - Import the `.sql` file provided
5. Open `config.php` and update DB credentials if needed
6. Launch the site: `http://localhost/your-folder-name`
7. Use credentials from the database (password: `Test@123` by default)

---

## 📸 Screenshots

- 🔐 Login Page  
- 📂 Admin Dashboard  
- 📚 Add/Manage Books  
- 🧑‍🎓 Add/Manage Students  
- 🏷️ Manage Categories & Publications  
- 🗓️ Issue/Return Book + Fine  
- 📈 Report Section (Overdue/UserWise)

---

## 📌 Note

This is a learning-based project that I have enhanced through hands-on work. I've focused on **understanding full-stack integration (HTML, CSS, PHP, MySQL)** and practicing features common in real-world systems like user roles, session handling, and report generation.

---

Feel free to explore the code and contribute or fork if you'd like to build on top of it!

