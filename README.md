# Voll Med

## Description

This is a REST API built with Spring Boot for managing medical appointment scheduling. It allows users to book and view appointments with doctors. The API provides robust functionalities for managing doctors, patients, and available time slots.

## Features

1. Book medical appointments
2. View appointment details
3. Manage doctor and patient records
4. Handle available time slots for appointments

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- MySQL Database
- Spring Boot Test (JUnit)
- Swagger for API documentation

## Environment Configuration

To test the application, you will need to create a file named `application.properties` in the `resources` folder and set the following properties (if you don't have environment variables, try changing the inputs itself):

```properties
resources>>application.properties

spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://${DB_HOST}:${DB_PORT}/${DB_NAME}
spring.datasource.username=${DB_USERNAME}
spring.datasource.password=${DB_PASSWORD}

spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true

server.error.include-stacktrace=never

api.security.token.secret=${JWT_SECRET}
```

## How to Run the Application

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/your-repository.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd your-repository
    ```
3. **Create and configure the `application.properties` file** as mentioned above.
4. **Run the application via terminal (it only works if you make the application properties file)**:
    ```sh
    ./mvnw spring-boot:run
    ```

## Contributions

Contributions are welcome! Feel free to open issues and submit pull requests.

---

Developed by Jamilla Lobo <♡︎/>
