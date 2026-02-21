# 🎓 CampusConnect

CampusConnect is a responsive web-based discussion forum designed for students to interact, ask questions, and engage in topic-based discussions. The platform supports user authentication, role-based access control, and full CRUD functionality for threads and posts.

---

## 🚀 Features

- 🔐 User Authentication (Signup/Login/Logout)
- 👥 Role-Based Access Control
- 📝 Create, Read, Update, Delete (CRUD) Threads
- 🔎 Search Functionality
- 📱 Responsive UI
- 🗄️ Optimized SQL Queries for Performance
- 🧩 PHP Structure 

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Apache (XAMPP / WAMP)

---

## 📂 Project Structure

```
CampusConnect/
│── index.php
│── thread.php
│── thread_list.php
│── search.php
│── handleLogin.php
│── handleSignup.php
│── dbconnect.php
│── header.php
│── footer.php
│── loginModal.php
│── signupModal.php
│── logout.php
│── about.php
│── contact.php
```

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/VarnikaP17/CampusConnect.git
   ```

2. Move the project folder to your `htdocs` directory (if using XAMPP).

3. Create a MySQL database (e.g., `campusconnect`).

4. Import the SQL file (if available) into your database.

5. Update database credentials inside:
   ```
   dbconnect.php
   ```

6. Start Apache & MySQL using XAMPP.

7. Open in browser:
   ```
   http://localhost/CampusConnect
   ```
---

## 📈 Key Highlights

- Implemented secure session handling
- Structured modular PHP architecture
- Optimized database queries for scalability
- Designed clean and responsive UI

---

## 👩‍💻 Author

**Varnika Pulipati**  
Computer Science Engineering Student  
