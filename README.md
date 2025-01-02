# Avancerad-java-Sumra-shoaib-slutprojekt-todoFE
## Todo App
### java version 21
# Back-end(Spring boot)
This back-end application is a Spring Boot-based REST API for managing a simple Todo list.
It provides endpoints for CRUD (Create, Read, Update, Delete) operations
with a front-end interface.
## Features
-  Get a list of all tasks.
- Create task
-  Fetch details of task by usng ID
-  Find Task By ID
- Delete tasks By ID
- Update task by giving Id
## Structure
### Model (todo.java)
- Represent task with ID ,title an ddiscription
- encapsulation is have getter and setters
### Controller
- Defines REST API endpoints to handle HTTP requests.
- Manages an in-memory List<Todo> for storing tasks during runtime.
- Handles responses for success, failure, or invalid input.
### Main Application
- Entry point of the Spring Boot application.
- Configures the application context and starts the server.
## Dependencies
- spring-boot-starter-web: For building RESTful web services.
- spring-boot-devtools: For hot-reloading during development.
- spring-boot-starter-test: For unit and integration testing.
## Endpoints
- GET (Fetches all tasks.Response: List of tasks in JSON format.)
- GET (Fetches a task by its ID.Response: Task details or 404 if not found.)
- GET (Fetches a task by its ID.Response: Task details or 404 if not found.)
- POST(Creates a new task.Request Body: JSON object with id, title, and description.)
- PUT (Updates an existing task by ID.Request Body: JSON object with updated title and description.)
- DELETE (Deletes a task by its ID.Response: Success message or 404 if the task is not found.)

## How to run
- Run through Java 21 and maven
- clone repo.
- The API will be available at http://localhost:8090/api/todo.




