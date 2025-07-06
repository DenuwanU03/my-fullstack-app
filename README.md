# Fullstack User Management Application

This is a simple fullstack CRUD (Create, Read, Update, Delete) application built with:

-  **Spring Boot** (Java) for backend REST API
-  **React.js** for frontend user interface
-  **MySQL** for database

## Features

- View all users
- Add new user
- Edit existing user
- View user details
- Delete user


## 📁 Project Structure

fullstack/
├── backend/ # Spring Boot backend
│ ├── src/main/java/...
│ ├── src/main/resources/application.properties
│ └── pom.xml
├── frontend/ # React frontend
│ ├── public/
│ ├── src/
│ └── package.json
├── README.md
└── .gitignore

---

## ⚙️ Setup Instructions

### Prerequisites
- Java 17 or higher
- MySQL installed and running
- Node.js + npm installed
- IntelliJ IDEA or VS Code

---

## 🔧 Backend Setup (Spring Boot)

1. **Create MySQL database:**

2. **Update `application.properties`:**

Go to:  
`src/main/resources/application.properties`
     ```properties
    spring.jpa.hibernate.ddl-auto=update
    spring.datasource.url=jdbc:mysql://localhost:3306/YOUR_DATABASE_NAME
    spring.datasource.username=YOUR_USERNAME
    spring.datasource.password=YOUR_PASSWORD
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

3. **Run backend:**
    using the green run button in FullstackApplication.java.
    Backend will run at:
    http://localhost:8080

## 🖥️ Frontend Setup (React)

## Technologies Used
- React.js
- React Router
- Axios
- Bootstrap 5

##  Getting Started

1. **cd my-fullstack-app/frontend**
2.**Install dependencies and Run the Frontend App**
  npm install
  npm start

This will start the app on: http://localhost:3000
⚠️ Make sure the backend server (Spring Boot) is running at http://localhost:8080.
