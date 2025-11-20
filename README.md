# SAMS Track – Staff Activity Management System

SAMS Track is a Spring Boot–based Staff Activity Management System designed to manage staff details, activities, and daily operations efficiently. It provides full CRUD functionality using REST APIs and follows a structured MVC architecture for clean and scalable development. This project is ideal for learning backend development, understanding Spring Boot fundamentals, and building real-world API-based applications.

## 🚀 Features
- Add, update, view, and delete staff records  
- REST API-based backend  
- MySQL database integration  
- Spring Data JPA for simplified database operations  
- Validation and exception handling  
- Clean MVC architecture  
- Easily testable using Postman  
- Light and scalable code structure  

## 🛠️ Technologies Used
- Java  
- Spring Boot  
- Spring MVC  
- Spring Data JPA / Hibernate  
- MySQL  
- Maven  
- REST APIs  
- Eclipse IDE  
- Git & GitHub  

## 📂 Project Structure
SAMS Track
 ├── src
 │   ├── main
 │   │   ├── java
 │   │   └── resources
 │   └── test
 ├── pom.xml
 ├── README.md
 └── application.properties

## 🔌 API Endpoints
| Method | Endpoint               | Description                  |
|--------|------------------------|------------------------------|
| POST   | /staff/add             | Add new staff                |
| GET    | /staff/getAll          | Get all staff records        |
| GET    | /staff/{id}            | Get staff by ID              |
| PUT    | /staff/update/{id}     | Update staff details         |
| DELETE | /staff/delete/{id}     | Delete staff by ID           |

## 🗄️ Database Configuration
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/sams
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## ▶️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/atharvaraut43/Samstrack.git
   ```
2. Open the project in Spring Tool Suite or Eclipse  
3. Configure MySQL and update application.properties  
4. Run the Spring Boot application  
5. Test APIs using Postman  

## 📧 Contact
Developer: Atharva Raut  
GitHub: https://github.com/atharvaraut43
