# Account Service

## Overview
Account Service is a backend application responsible for managing user accounts and their associated data. It provides APIs for account creation, management, authentication, and profile updates, serving as the foundation for user-related operations in a system.

## Features
- **User Account Management:** Create, update, and delete user accounts.
- **Authentication:** Handle user login and token-based authentication.
- **Profile Management:** Update and retrieve user profile information.
- **Role Management:** Assign and manage user roles.
- **Swagger Documentation:** Automatically generated API documentation.

## Getting Started

### Prerequisites
- Java 17
- Docker (optional for containerized deployment)
- Gradle

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/IvanMatiko/account_service.git
   cd account_service
   
2. Build the project:
   ```bash
   ./gradlew build

3. Run the application:
   ```bash
   ./gradlew bootRun

 # API Endpoints
 
POST /accounts: Create a new user account.

GET /accounts/{id}: Retrieve account details by ID.

PUT /accounts/{id}: Update account information.

DELETE /accounts/{id}: Delete a user account.

POST /login: Authenticate a user and provide a token.

GET /accounts: Retrieve a list of all accounts with filtering options.

For detailed API specifications, refer to the Swagger documentation.

# Technologies Used

Java: Core programming language.

Spring Boot: Framework for backend development.

Gradle: Build and dependency management tool.

JWT (JSON Web Tokens): For user authentication.

Swagger: API documentation.

Docker: For containerized deployment.
   
