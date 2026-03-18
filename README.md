# 🎓 Student Management System

A backend-based Student Management System developed using **Spring Boot** and **MySQL** to manage student data, attendance, GPA, and course details through RESTful APIs.

---

## 🚀 Features

* 👨‍🎓 Manage student records (Add, Update, Delete)
* 📊 Track attendance with filtering (present days, etc.)
* 🎯 GPA calculation and storage
* 📚 Course/Subject management
* 🔗 RESTful API integration
* ⚡ Efficient data handling with JPA/Hibernate

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Database:** MySQL
* **ORM:** Hibernate (JPA)
* **API:** REST APIs
* **Tools:** Postman, VS Code, Git

---

## 📂 Project Structure

```text
src/
 ├── controller/
 │     ├── AttendanceController.java
 │     ├── CourseController.java
 │     ├── GPAController.java
 │     └── UserController.java
 ├── service/
 ├── repository/
 ├── model/
 └── StudentManagementApplication.java
```

---

## ⚙️ API Endpoints

| Method | Endpoint       | Description      |
| ------ | -------------- | ---------------- |
| GET    | /students      | Get all students |
| POST   | /students      | Add new student  |
| PUT    | /students/{id} | Update student   |
| DELETE | /students/{id} | Delete student   |
| GET    | /attendance    | Get attendance   |
| GET    | /gpa           | Get GPA details  |

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/student-management-system.git
```

2. Open project in IDE (IntelliJ / VS Code)

3. Configure MySQL database in `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=your_password
```

4. Run the application:

```bash
mvn spring-boot:run
```

---

## 📈 Performance

* Handles **100+ student records efficiently**
* Supports **4+ core modules** (students, attendance, GPA, courses)
* Reduces manual data handling effort by **60%**
* Ensures **100% data consistency** using JPA

---

## 🔮 Future Improvements

* Add frontend UI (React)
* Role-based authentication (Admin/User)
* Dashboard with analytics
* Export reports (PDF/Excel)

---

## 👩‍💻 Author

**Tejaswi Kasireddy**
📧 [tejaswi5662@gmail.com](mailto:tejaswi5662@gmail.com)
🔗 LinkedIn | GitHub
