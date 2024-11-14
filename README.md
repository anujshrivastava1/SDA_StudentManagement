# Honors 7th Sem Project Assignment - Anuj Shrivastava
# Student Management System

This is a RESTful Spring Boot application that manages student data, allowing users to register, log in, and retrieve or update their information. The application enforces unique email registration and provides basic user management operations.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Registration**: Register a new student with unique email verification.
- **User Login**: Authenticate a user with email and password.
- **Information Management**: Update and retrieve student information.
- **Validation**: Prevent duplicate account creation with the same email.

## Screenshots
### Registration
![Screenshot (436)](https://github.com/user-attachments/assets/afd18851-cf47-45a9-8eb2-99dc5208f6fc)


### Login
![Screenshot (438)](https://github.com/user-attachments/assets/bfc00370-508d-4e3c-8330-0a8830a63298)


### Retrieve Info
![Screenshot (439)](https://github.com/user-attachments/assets/893c9595-34e4-409f-bf0a-2f8b9780a20a)


### Update Info
![Screenshot (440)](https://github.com/user-attachments/assets/67dde012-6d24-4d95-a167-08da9c468620)

![Screenshot (441)](https://github.com/user-attachments/assets/eb58f689-86a7-4e8a-b41c-aede108d94cf)

### No Duplicate mails
![Screenshot (442)](https://github.com/user-attachments/assets/8a4ce11c-312a-4752-a08b-b30f8c00fd22)


## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```

2. **Build the application**:
   ```bash
   mvn clean package
   ```

3. **Run the application**:
   ```bash
   java -jar target/student-management-system-0.0.1-SNAPSHOT.jar
   ```

### Alternatively, Run with Maven
```bash
mvn spring-boot:run
```

## Usage

After starting the application, you can use tools like **Postman** or **curl** to interact with the API.

## API Endpoints

| Method | Endpoint               | Description                     |
|--------|-------------------------|---------------------------------|
| POST   | `/students/register`    | Register a new student          |
| POST   | `/students/login`       | Authenticate a student          |
| GET    | `/students/{id}`        | Retrieve student info by ID     |
| PUT    | `/students/{id}`        | Update student information      |

## Technologies Used
- **Java 17**
- **Spring Boot**
- **Maven**
- **PostgreSQL** (or specify your database choice)
- **Postman** (for testing APIs)
- **Jenkins**

