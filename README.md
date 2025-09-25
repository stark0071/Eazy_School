# Eazy_School

**Eazy_School** is a web-based school management system built with **Spring Framework 3.4.2**, designed to help administrators, teachers, and students manage school operations efficiently. This project demonstrates core concepts of Spring MVC, JDBC, and database-driven web applications.

---

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Architecture](#architecture)  
- [Database Schema](#database-schema)  
- [Setup and Installation](#setup-and-installation)  
- [Usage](#usage)  
- [Future Enhancements](#future-enhancements)  
- [License](#license)  

---

## Features

- **Student Management**: Add, update, delete, and view student details.  
- **Teacher Management**: Manage teacher profiles and assign courses.  
- **Course Management**: CRUD operations for courses and subjects.  
- **User Authentication**: Simple login system for admins and teachers.  
- **Database Integration**: Persistent storage using MySQL.  
- **MVC Architecture**: Clear separation of concerns using Spring MVC.  

---

## Technologies Used

- **Java 8+**  
- **Spring Framework 3.4.2** (Core, MVC, JDBC)  
- **MySQL** for database  
- **JSP, HTML, CSS** for front-end views  
- **Tomcat** as the web server  
- **Git & GitHub** for version control  

---

## Architecture

Browser <-> Controller (Spring MVC) <-> Service Layer <-> DAO Layer <-> Database (MySQL)

markdown
Copy code

- **Controller**: Handles HTTP requests and maps them to service methods.  
- **Service Layer**: Contains business logic.  
- **DAO Layer**: Interacts with the database using JDBC.  
- **Database**: Stores students, teachers, courses, and login information.  

---

## Database Schema

**Tables:**

1. **students**: `id`, `name`, `age`, `class`, `email`  
2. **teachers**: `id`, `name`, `subject`, `email`  
3. **courses**: `id`, `course_name`, `description`  
4. **users**: `id`, `username`, `password`, `role`  

*You can create these tables in MySQL using the provided SQL scripts or manually.*  

---

## Setup and Installation

1. **Clone the repository:**

```bash
git clone https://github.com/stark0071/Eazy_School.git
cd Eazy_School
Import the project into your IDE (Eclipse/IntelliJ).

Configure MySQL database connection in applicationContext.xml or DAO classes.

Run the SQL scripts to create required tables.

Deploy on a local server (Tomcat 8+ recommended).

Access the application via http://localhost:8080/Eazy_School.

Usage
Log in as admin to manage students, teachers, and courses.

Use teacher account to view assigned courses and student information.

Add new students, assign them to courses, and generate reports.

Future Enhancements
Add role-based access control with Spring Security.

Integrate file uploads for student assignments.

Add REST APIs for mobile app integration.

Implement dashboard with analytics for student performance.

License
This project is licensed under the MIT License.

pgsql
Copy code

---

If you want, I can also **add a “fancy version”** with **project screenshots, badges (like Java version, build status), and a nice table of features**—this makes your GitHub repo look professional for recruiters.  

Do you want me to do that next?







Ask ChatGPT
