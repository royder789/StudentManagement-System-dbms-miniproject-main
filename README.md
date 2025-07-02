**Student Management System (DBMS Mini Project)** 🚀


The **Student Management System** is a comprehensive web application designed to streamline and automate administrative tasks in educational institutions. Built as a Database Management Systems (DBMS) mini-project, it offers functionalities for managing student records, courses, attendance, and more—all in a user-friendly dashboard.

## ⭐ Features

* ✅ **User Authentication:** Secure login for administrators and staff.
* ✅ **Student CRUD Operations:** Create, Read, Update, and Delete student profiles.
* ✅ **Course Management:** Add and manage courses and subjects.
* ✅ **Attendance Tracking:** Mark and review daily attendance.
* ✅ **Search & Filter:** Quickly locate student records.
* ✅ **Responsive UI:** Clean dashboard interface for desktop and tablet.

## 🛠️ Technology Stack

| Component          | Technology         |
| ------------------ | ------------------ |
| Front-End          | HTML5, CSS3, JS    |
| Back-End           | PHP 7.x            |
| Database           | MySQL (phpMyAdmin) |
| Server Environment | XAMPP              |

## 🏗️ System Architecture

1. **Client Browser** submits HTTP requests via the dashboard UI.
2. **Apache Server** (XAMPP) processes PHP scripts.
3. **PHP Application** executes business logic and queries the **MySQL** database.
4. **MySQL Database** stores tables for students, courses, attendance, etc.
5. **Responses** are rendered back to the client as dynamic HTML pages.

## ⚙️ Installation & Setup

### Prerequisites

* Windows/Mac/Linux OS
* XAMPP installed (Apache & MySQL modules)
* Basic knowledge of PHP & MySQL

### XAMPP Configuration

1. **Start Modules:** Launch XAMPP Control Panel and start **Apache** and **MySQL** modules.
2. **Project Directory:** Copy the project folder `StudentManagement-System-dbms-miniproject-main` into `\xampp\htdocs\` (Windows) or `/Applications/XAMPP/htdocs/` (macOS).
3. **Folder Permissions:** Ensure the folder has read/write permissions.

### Database Import

1. Open your browser and go to `http://localhost/phpmyadmin/`.
2. Click **Import** and choose `database/student_management.sql` from the project directory.
3. Click **Go** to import the schema and seed data.

### Running the Application

1. Navigate to `http://localhost/StudentManagement-System-dbms-miniproject-main/`.
2. Log in with the default credentials:

   * **Username:** `admin`
   * **Password:** `admin123`
3. You will be redirected to the dashboard upon successful login.

## 📂 Folder Structure

```
StudentManagement-System-dbms-miniproject-main/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── database/
│   └── student_management.sql
├── includes/
│   ├── config.php
│   ├── header.php
│   └── footer.php
├── index.php
├── login.php
├── dashboard.php
├── students.php
├── courses.php
├── attendance.php
└── README.md
```

## 💡 Usage

1. **Login:** Access the login page and enter credentials.
2. **Dashboard:** View summary statistics (total students, courses, attendance percentage).
3. **Manage Students:** Add new students or edit existing profiles.
4. **Manage Courses:** Define courses and assign to students.
5. **Track Attendance:** Mark attendance for each class session.
6. **Logout:** Securely end your session.

## 📸 Screenshots

> *Place your screenshots in `assets/images/` and update paths below.*

![Dashboard Overview](assets/images/dashboard_overview.png)

![Student List](assets/images/student_list.png)

![Add New Student](assets/images/add_student.png)

## 🚀 Future Enhancements

* 🔒 Implement role-based access control (teachers, students).
* 📧 Email notifications for attendance alerts.
* 📊 Advanced reporting & analytics.
* 📱 Mobile-responsive redesign.

## 🛠️ Contributors

* **Mihir Kumar Roy** – *Project Lead & Developer*
* **Your Name** – *UI/UX Designer*

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

*\*Thank you for exploring the Student Management System!* 😊
