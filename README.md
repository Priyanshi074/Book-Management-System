# 📚 Book Management System

A complete Spring Boot web application for managing library books with role-based authentication.
# Book Management System

## Overview
The **Book Management System** is a web-based application for managing books in a library or personal collection. It allows users to add, update, delete, and view books efficiently, providing a simple and organized way to track book inventory.

---

## Features
- Add new books with details like title, author, genre, and publication date
- Update existing book information
- Delete books from the collection
- View all books in a structured format
- Persistent storage using a database

---

## Technologies Used
- **Backend:** Java, Spring Boot
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MySQL / SQLite
- **Build Tool:** Maven
- **Version Control:** Git & GitHub

---

## Installation & Setup

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

## Project Structure
```bash
book-management/
├── src/
│   ├── main/java/com/book/bookmanagement/   # Java source code
│   ├── main/resources/                     # Configuration files
│   └── main/resources/static/              # Frontend assets (HTML, CSS, JS)
├── pom.xml                                 # Maven dependencies
└── README.md
```
## Usage
- Launch the application
- Navigate to the Books section
- Perform operations like Add, Update, Delete, or View books
- All changes are saved automatically to the database

## Future Enhancements
- User authentication and authorization
- Book search and filter functionality
- Borrow and return system for libraries
- Integration with notification system (email alerts)

## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## License
This project is licensed under the MIT License.

