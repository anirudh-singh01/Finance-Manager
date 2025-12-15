# Finance Manager

A Spring Boot application for managing personal finances.

## Prerequisites
- Java 21
- Maven
- MySQL

## Setup

1. **Database**: Create a MySQL database named `finance_manager`.
2. **Environment Variables**: Create a `.env` file in the root directory (see `.env.example` or properties file) and set the following:
   ```
   MAIL_USERNAME=your_email
   MAIL_PASSWORD=your_password
   ```

## Running the Application

To run locally with the development profile:

```bash
mvn spring-boot:run
```

The application will start on port 8080 (default).
