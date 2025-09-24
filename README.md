# 🎓 Student Attendance Management System

A **full-stack student attendance tracker** built with **Spring Boot (Java)** and **React (TypeScript)**.  
This system enables role-based attendance management with real-time analytics and reporting.

---

## 🚀 Tech Stack
- **Backend:** Spring Boot 3.3, Java 17, Spring Data JPA, Spring Security (JWT)
- **Frontend:** React 18, TypeScript, React Bootstrap, Chart.js
- **Database:** MySQL 8.0
- **Others:** Axios, React Router, Maven, Swagger/OpenAPI

---

## 📂 Features
✅ Student, Faculty & Course Management (CRUD)  
✅ Attendance Tracking (Individual & Bulk)  
✅ Role-based Access (Admin, Faculty, Student)  
✅ Real-time Analytics & Dashboard  
✅ Reports & Charts with Chart.js  
✅ Responsive UI with Bootstrap  
✅ Secure Authentication (JWT)  
✅ Error Handling & Validation  

---

## ⚙️ Installation

### Database
```bash
mysql -u root -p student_attendance_db < attendance_database_schema.sql


Backend(SpringBoot)
cd backend
mvn spring-boot:run
# Runs at: http://localhost:8080

Frontend(React + Typescript)
cd frontend
npm install
npm start
# Runs at: http://localhost:3000

📊 Roles

* Admin → Manage students, faculty, and courses.

* Faculty → Mark attendance, view statistics.

* Student → View personal attendance record.

🖼️ UI/UX Highlights

* Responsive layout with animations

* Interactive dashboard with charts

* Data tables with search, filter, pagination

* Toast notifications for feedback

🔮 Future Enhancements

* Email/SMS notifications

* Biometric/RFID integration

* AI-based attendance prediction


