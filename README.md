# Patient Management Service

A Spring Boot application for managing patient records, built with Java, SQL, and Maven.

## Features

- RESTful API for patient CRUD operations
- Integrated H2 database (in-memory)
- Swagger UI for API documentation
- Global exception handling
- Custom logging pattern

## Technologies

- Java
- Spring Boot
- Maven
- H2 Database
- Swagger/OpenAPI

## Getting Started

### Prerequisites

- Java 17+
- Maven 3.8+
- Git

### Setup

1. Clone the repository: git clone https://github.com/christychoma75/patient_management.git cd patient_management
2. Build and run: mvn spring-boot: run
3. Access the application:
   - Swagger UI: [http://localhost:4000/swagger-ui.html](http://localhost:4000/swagger-ui.html)
   - H2 Console: [http://localhost:4000/h2-console](http://localhost:4000/h2-console)

## Configuration

Main settings are in `src/main/resources/application.properties`.

## API Documentation

See Swagger UI for interactive API docs.

## License

This project is licensed under the MIT License.
