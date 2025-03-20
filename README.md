# API Cart

The **API Cart** is a microservice designed to manage shopping carts. This API allows you to add items to a cart, remove items from a cart, and view all items in a cart. Additionally, the API implements robust security validation with Spring Security, where access to certain functionalities is controlled via token-based authentication and user roles. This microservice also makes requests to the Stock microservice to validate whether the quantity requested by the user is available. The API is documented with OpenAPI and Swagger, which facilitates easy exploration and testing of endpoints.

## Features

- **Cart Management:** Add items to the cart, remove items from the cart, and list all items currently in the cart.
- **Inventory Validation:** Communicates with the Stock microservice to verify item availability before adding them to the cart.
- **Authentication and Authorization:** Secure access using Spring Security, with token-based validation and role-based access control.
- **API Documentation:** Interactive OpenAPI documentation integrated with Swagger.
- **Microservices Architecture:** Designed as a scalable microservice for effective cart management.
- **Local URL:** [http://localhost:6060](http://localhost:6060)

## Technologies

- Java
- Spring Boot
- Spring Security
- RESTful API
- Microservices Architecture
- OpenAPI / Swagger
- Gradle

## Getting Started

### Prerequisites

- Java 17 or higher
- Gradle
- A compatible SQL Database

## API Endpoints

Access the interactive documentation via Swagger UI: **[http://localhost:6060/swagger-ui.html](http://localhost:6060/swagger-ui.html)**  
This interface provides interactive documentation for all available endpoints, making it easy to understand and test the API.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/EstebanRCarmona/Api-Cart-emazon.git
