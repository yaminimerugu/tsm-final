# Task Management Web Application

This is a comprehensive task management system that empowers users to efficiently organize their tasks. This full-stack application combines the robustness of Spring Boot on the backend, the responsiveness of React.js on the frontend, and the reliability of MySQL as the database.

## Features 
### User Authentication 
Users can register and log in to access the system securely.
Authentication ensures that only authorized users can perform operations.

### Task Operations 

- **Add Tasks :** Users can effortlessly add new tasks to the system.
- **View Tasks  :** A user-friendly interface displays all tasks for quick and easy reference.
- **Edit Tasks :** Users have the flexibility to modify task details as needed.
- **Delete Tasks  :** Unwanted tasks can be removed to keep the task list organized.
- **Mark as Complete :** Users can mark tasks as complete for effective progress tracking.


## Tech Stack 
**Client:** React, ViteJS, BootStrap
**Server:** Java, Spring Boot
**Database:** MySQL

## Architecture
The Task Management System follows a client-server architecture, with a backend built using Java and Spring Boot serving as the server-side application. The frontend is developed using React, providing a user-friendly interface for interacting with the system. MySQL is used as the database to store task-related data.

## Modules
- Backend: Contains the Java and Spring Boot application responsible for handling business logic and database operations.
- Frontend: Includes the React application responsible for providing a user interface for interacting with the system.
- Database: Contains the MySQL database schema and scripts for creating and managing the database.

## Project Setup
## Backend Setup
- Clone the repository.
- Navigate to the backend directory.
- Configure the MySQL database connection in application.properties.
- Run the Spring Boot application using your IDE or the command line.
## Frontend Setup
- Navigate to the frontend directory.
- Install dependencies using npm install.
- Start the React application using npm run dev.
 ## Database Setup
- Create a MySQL database.
- Execute the database schema script provided in the database directory to create the necessary tables.
- Update the database connection details in the backend application properties.

## API Endpoints Documentation

### 1. Create Task

- **Endpoint:** `POST http://localhost:8080/api/v1/tasks/user/1`
- **Description:** Creates a new task for the specified user.


### 2. Get Task by ID
- **Endpoint**: GET- `http://localhost:8080/api/v1/tasks/1`
- **Description**: Retrieves a task by its ID.


### 3. Get All Tasks for User
- **Endpoint**: GET- `http://localhost:8080/api/v1/tasks/user/1`
- **Description**: Retrieves all tasks for the specified user.

### 4. Update Task
- **Endpoint**: PUT- `http://localhost:8080/api/v1/tasks/1`
- **Description**: Updates the details of a task.
- Request Body:


### 5. Delete Task
- **Endpoint**: DELETE- `http://localhost:8080/api/v1/tasks/1`
- **Description**: Deletes a task by its ID.
- Response Body:
```json

{
  "message": "Task deleted successfully"
}

```
