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

1. Clone the repository
git clone https://github.com/Mohana247-svg/Student-management-system.git
cd Student-management-system
2. Create MySQL database
CREATE DATABASE student_db;
3. Update application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
4. Run the application
mvn spring-boot:run
5. Open in browser
http://localhost:8080/students

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/students` | List all students |
| GET | `/students/new` | Show create form |
| POST | `/students` | Save new student |
| GET | `/students/edit/{id}` | Show edit form |
| POST | `/students/{id}` | Update student |
| GET | `/students/delete/{id}` | Delete student |

---

## ✅ What I Learned Building This

- Implementing the full **MVC pattern** in a real Spring Boot application
- Writing clean **service layer abstractions** with interface + implementation separation
- Managing **MySQL schema** using JPA/Hibernate auto-DDL
- Connecting **HTML frontend views** to backend using Thymeleaf
- Using **Maven** for dependency management and build lifecycle
- Following **REST conventions** for clean API design

---

## 👩‍💻 Author

**Mohanachandrika Peruru**
MCA Graduate | Java Developer | Spring Boot Enthusiast
📧 p.mohanachandrika@gmail.com
🔗 LinkedIn: linkedin.com/in/peruru-mohanachandrika



















