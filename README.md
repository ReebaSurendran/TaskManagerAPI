# Task Manager App

A simple task manager application built using Spring Boot and Java, with data stored in `ConcurrentHashMap` for thread safety, reducingthe need for an external DB.

## Features

- Create, read, update, and delete tasks
- Thread-safe data storage using `ConcurrentHashMap`
- RESTful API endpoints
- -useful for lesser chunks of data

## Technologies Used

- Java
- Spring Boot
- Eclipse
- ConcurrentHashMap

## Getting Started

### Prerequisites

- Java 8 or higher
- Maven
- Eclipse IDE

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/reeba-surendran/task-manager-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd task-manager-app
    ```
3. Open the project in Eclipse IDE.

4. Build the project using Maven:
    ```sh
    mvn clean install
    ```

### Running the Application

1. Run the Spring Boot application from Eclipse:
    - Right-click on the project in the Project Explorer.
    - Select `Run As` > `Spring Boot App`.

2. The application will start on `http://localhost:8080`.

### API Endpoints

- **GET /tasks**: Retrieve all tasks
- **GET /tasks/{id}**: Retrieve a task by ID
- **POST /tasks**: Create a new task
- **PUT /tasks/{id}**: Update an existing task
- **DELETE /tasks/{id}**: Delete a task by ID

### Example Task JSON

```json
{
    "title": "Sample Task",
    "description": "This is a sample task description.",
    "completed": false
}

```

### Project Structure
- Model: Task.java
- Controller: TaskController.java
- Service: TaskService.java
- Repository: TaskRepository.java

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

### Acknowledgements
- Spring Boot documentation
- Eclipse IDE documentation

Feel free to reach out to me via reebasurendran01@gmail.com or connect with me on LinkedIn - https://www.linkedin.com/in/reeba-surendran.😊
