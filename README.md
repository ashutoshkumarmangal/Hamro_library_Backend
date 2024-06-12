# Hamro Library Backend

Hamro Library is a Library Management System (LMS) built using Spring Boot, Hibernate, JPA, and MySQL. It offers all the functionalities required to manage a library effectively, including book management, user management, and transaction management.

## Features

- User Registration and Authentication
- Forgot password feature
- Book Management (Add, Update, Delete, View)
- User Management (Add, Update, Delete, View)
- Borrowing and Returning Books
- Search and Filter Books
- Overdue Date
- Pdf generator of the report

## Technologies and IDE Used

- **Spring Boot** - Framework for building Java applications
- **Hibernate** - ORM framework for mapping Java objects to database tables
- **JPA (Java Persistence API)** - Specification for accessing, persisting, and managing data
- **MySQL** - Relational database management system
- **Maven** - Dependency management and build tool
- **Eclipse**
- **Postman**
- **MySQL Workbench**

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- MySQL Server
- Maven
- Git

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/hamro-library.git
   cd hamro-library
   ```
2. **Configure the Database**

   ```bash
   # Connection of mysql
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
   spring.datasource.url=jdbc:mysql://localhost:3306/lms? 
   createDatabaseIfNotExist=true&useSSL=true
   spring.datasource.username=root
   spring.datasource.password=password
   spring.jpa.show-sql = true

   # Hibernate
   spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQLDialect
   spring.jpa.hibernate.ddl-auto=update

   # Email Send via JAVA
   spring.mail.host=smtp.gmail.com
   spring.mail.port=587
   spring.mail.username=aashuakm12@gmail.com
   spring.mail.password= (generate your app password using gmail)
   spring.mail.properties.mail.smtp.auth=true
   spring.mail.properties.mail.smtp.starttls.enable=true
   ```

   # Author
   ## Ashutosh Kumar Mangal

