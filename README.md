📌 Project Description
This is a Spring Boot application demonstrating OAuth2 authentication with basic route protection. It uses Spring Security to handle authentication and secure endpoints, making it a great foundation for adding OAuth2 login with Google or GitHub, or for learning how to secure REST APIs.

🚀 Features
OAuth2 login with configurable providers

Basic controller to test secured routes

Spring Security configuration setup

Maven-based Spring Boot project

🛠️ Technologies Used
Java 17+

Spring Boot

Spring Security

OAuth2

Maven

▶️ How to Run
Prerequisites:
Java 17 or higher

Maven installed

Steps:

```
# 1. Navigate into the project directory
cd spring-auth-main

# 2. Build the project
./mvnw clean install

# 3. Run the application
./mvnw spring-boot:run
```

The app should run at http://localhost:8080/. Configure OAuth2 client details in application.properties.
