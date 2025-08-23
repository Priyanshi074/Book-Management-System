# 📚 Book Management System
![Java](https://img.shields.io/badge/Java-17-blue.svg)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-brightgreen.svg)
![Maven](https://img.shields.io/badge/Build-Maven-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![GitHub issues](https://img.shields.io/github/issues/Priyanshi074/Book-Management)
![GitHub stars](https://img.shields.io/github/stars/Priyanshi074/Book-Management?style=social)
A robust Spring Boot web application for managing library books with CRUD operations and role-based authentication. Ideal for educational institutes and small libraries to manage book collections efficiently.

---

## 🌟Features
- Add new books with details like title, author, genre, and publication date
- Update existing book information
- Delete books from the collection
- View all books in a structured format
- Persistent storage using a database

---

## 🛠Technologies Used
- **Backend:** Java, Spring Boot
- **Frontend:** HTML5, CSS, Bootstrap 5, Thymeleaf
- **Database:** MySQL
- **Build Tool:** Maven
- **Version Control:** Git & GitHub

---

## ⚙️Prerequisites
- Java 17+
- Maven 3+
- MySQL / SQLite
- Git

---

## 🚀Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/your-username/book-management.git
cd book-management
```
2. **Setup Database**
- Create a database named book_management (or as configured in application.properties)
- Update database credentials in src/main/resources/application.properties

3. **Build and Run the Project**
```bash
mvn clean install
mvn spring-boot:run
```

4. **Access the Application**
- Open your browser and go to http://localhost:8080

## 🗂Project Structure
```bash
book-management/
├── src/
│   ├── main/java/com/book/bookmanagement/   # Java source code
│   ├── main/resources/                     # Configuration files
│   └── main/resources/static/              # Frontend assets (HTML, CSS, JS)
├── pom.xml                                 # Maven dependencies
└── README.md
```
---

## 📄Usage
- Launch the application
- Navigate to the Books section
- Perform operations like Add, Update, Delete, or View books
- All changes are saved automatically to the database

---

## 🎬 Demo / Screenshots

A quick look at the **Book Management System** in action.

---

### 🔐 Authentication

#### Login Page
Role-based login for **Admin** and **Student**.  
![Login Page](screenshots/login%20page.jpg)

#### Register Page
New users can register into the system.  
![Register Page](screenshots/Register%20page.jpg)

---

### 👩‍💻 Admin Mode

#### 📊 Admin Dashboard
Overview for admin after login.  
![Admin Dashboard](screenshots/admin%20dashboard.jpg)

#### 📖 Book List (Admin View)
View all books with **Edit** and **Delete** options.  
![Admin Book List](screenshots/admin%20book%20list.jpg)

#### ➕ Add New Book
Form to add a new book.  
![Add Book](screenshots/add%20new%20book.jpg)

#### ✏️ Edit Book
Update details of an existing book.  
![Edit Book](screenshots/edit%20book.jpg)

---

### 👩‍🎓 Student Mode

#### 📊 Student Dashboard
Student view after login.  
![Student Dashboard](screenshots/student%20dashboard.jpg)

#### 📚 Available Books
List of books students can browse/borrow.  
![Available Books](screenshots/available%20book%20list.jpg)

#### 📖 Request Book
Students can request a book from the library.  
![Request Book](screenshots/student%20request%20book.jpg)

---

## 🚀Future Enhancements
- User authentication and authorization
- Book search and filter functionality
- Borrow and return system for libraries
- Integration with notification system (email alerts)
---

## 🤝Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository
2. Create a new branch: git checkout -b feature/your-feature
3. Commit your changes: git commit -m "Add some feature"
4. Push to the branch: git push origin feature/your-feature
5. Open a Pull Request
---

## 📄License
This project is licensed under the MIT License.

