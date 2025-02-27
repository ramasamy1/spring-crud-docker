# Dog API

A RESTful API to manage Dog resources, built with Spring Boot and MongoDB.

## Features

- **CRUD Operations:** Create, retrieve, update, and delete dogs.
- **Search & Pagination:** Filter by breed; paginate results via query parameters.
- **Validation & Error Handling:** Input validation with JSR-380; standardized error responses.
- **Caching:** (Optional) Application-level caching using Spring Cache.
- **Security:** Secured using Spring Security with HTTP Basic authentication.
- **Swagger/OpenAPI:** Interactive API documentation available at `/swagger-ui/index.html`.
- **Dockerized:** Dockerfile and docker-compose configuration provided.
- **Logging:** Integrated with SLF4J for robust logging.

## Getting Started

### Prerequisites

- Java 17, Maven, Docker and Docker Compose

### Running Locally

1. **Build and Run Directly:**

   ```bash
   mvn clean package
   mvn spring-boot:run
