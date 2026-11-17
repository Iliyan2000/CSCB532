# School Organization System

## Stack

- Java 21 and Gradle 9.4
- Spring Boot 4.0.4
- Spring MVC, Thymeleaf, Spring Data JPA, Validation
- Spring Security and OAuth2 Resource Server
- MySQL (primary database) and H2 Console
- Lombok and JUnit 5

## Database

The application creates and uses the MySQL database `School_Organization_System_Db`:

```text
jdbc:mysql://localhost:3306/School_Organization_System_Db?createDatabaseIfNotExist=true&useSSL=true
```

## Run

```bash
./gradlew bootRun
```
