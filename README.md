# 🎓 Student Management System

A full-stack **Student Management Web Application** built using **Spring Boot**, **Spring MVC**, **MySQL**, and **HTML** — consolidating multiple manual student record processes into one clean, reliable system.

---

## 📌 Features

- ✅ Add new student records
- ✅ View all students in a structured list
- ✅ Edit and update student information
- ✅ Delete student records
- ✅ REST API backend with clean separation of concerns
- ✅ Responsive HTML frontend views

---

## 🛠️ Tech Stack

- **Language:** Java 8+
- **Backend Framework:** Spring Boot, Spring MVC
- **Database:** MySQL with JPA/Hibernate
- **Frontend:** HTML5, Thymeleaf
- **Build Tool:** Maven
- **Testing:** Postman, JUnit
- **Version Control:** Git / GitHub

---

## 🏗️ Architecture

Browser (HTML Views)
↓
StudentController   ← REST / MVC Controller
↓
StudentService      ← Business Logic Interface
↓
StudentServiceImpl  ← Implementation
↓
StudentRepository   ← JPA Repository
↓
MySQL Database


---

## 📁 Key Files

| File | Purpose |
|---|---|
| `Student.java` | Entity class mapped to MySQL table |
| `StudentController.java` | Handles HTTP requests and routing |
| `StudentService.java` | Service interface defining operations |
| `StudentServiceImpl.java` | Implements all business logic |
| `StudentRepository.java` | JPA repository for DB operations |
| `students.html` | View all students page |
| `create_student.html` | Add new student form |
| `edit_student.html` | Edit existing student form |
| `application.properties` | Database configuration |

---

## ⚙️ How to Run Locally





















