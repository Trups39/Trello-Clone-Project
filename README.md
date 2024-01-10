# Trello Clone Project

This project is a simplified version of Trello, allowing users to manage tasks in boards and lists.

## Introduction

The Trello clone project aims to replicate basic functionalities of the Trello application, enabling users to create, organize, and manage tasks within boards and lists. It utilizes Spring Boot and MySQL for backend services and provides RESTful APIs for interacting with the application.

## Usage

Once the application is running, you can access the endpoints using tools like Postman or directly through a frontend client. Here are some basic endpoints:

- `POST /demo/addtask`: Add a new task
- `PUT /demo/modifytask/{id}`: Modify an existing task
- `DELETE /demo/deletetask/{id}`: Delete a task
- `GET /demo/showalltask`: Retrieve all tasks
- `GET /demo/showtaskhistory/{id}`: Retrieve task history by ID
- ...

## Features

- Create and manage tasks
- Organize tasks in boards and lists
- View task history
- ...

## Technologies Used

- **Spring Boot**: For backend API development
- **MySQL**: Database for storing task information
- **Hibernate**: Object-relational mapping tool
- **Maven**: Dependency management and build tool
- ...

