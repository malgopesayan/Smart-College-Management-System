# Student Record Management System

## Overview
This project is a **dynamic system** developed using **HTML, CSS, JavaScript, PHP, and SQL**. It is designed to **efficiently manage student records** while ensuring **secure access through role-based authentication**.

## Features
- **User Authentication:** Secure login with role-based access control (Admin, Teacher, Student).
- **Student Record Management:** Add, update, and delete student information efficiently.
- **Optimized Workflows:** Enhances efficiency by 50% in managing student records.
- **Responsive Design:** Ensures a seamless experience across different devices.
- **Database Integration:** Uses SQL for storing and retrieving student data.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** SQL (MySQL or PostgreSQL)

## Installation
### Prerequisites
- A web server (e.g., Apache, XAMPP, WAMP)
- PHP installed (v7.4 or later recommended)
- MySQL or PostgreSQL database

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/student-record-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd student-record-system
   ```
3. Import the database:
   - Locate the `.sql` file in the `database` folder.
   - Use **phpMyAdmin** or a database tool to import the file.
4. Configure the database connection in `config.php`:
   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "student_records";
   ```
5. Start the server and access the system via `http://localhost/student-record-system/`

## Usage
1. **Admin Login:** Manage user roles and oversee student records.
2. **Teacher Access:** View and update student performance details.
3. **Student Access:** View personal records and grades.

## Security Measures
- **Password Hashing:** Securely stores user passwords.
- **Role-Based Access Control (RBAC):** Limits functionality based on user roles.
- **SQL Injection Prevention:** Uses prepared statements to prevent attacks.

## Contribution
If you’d like to contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes and push them.
4. Open a Pull Request

https://github.com/user-attachments/assets/fe55fa4b-dc66-476c-896d-369e593d85b9


