# Full Stack Todo Application

## Overview
This is a Full Stack Todo Application built using Spring Boot, PostgreSQL, and React (Vite).  
The project demonstrates complete CRUD operations with proper backend-frontend integration and database persistence.

---

## Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- REST APIs
- Maven

### Frontend
- React (Vite)
- Axios
- CSS

### Database
- PostgreSQL

### Deployment
- Docker
- Render (Cloud Deployment)

---

## Features

- Create new todo
- Fetch all todos
- Update existing todo
- Delete todo
- Persistent storage using PostgreSQL
- RESTful API architecture
- Frontend connected to backend APIs

---

## Project Structure


Todo-Fullstack-app/
│
├── Backend/ → Spring Boot application
├── Frontend/ → React application
├── Dockerfile → Container configuration


---

## API Endpoints

| Method | Endpoint        | Description        |
|--------|----------------|-------------------|
| GET    | /todos         | Fetch all todos   |
| POST   | /todos         | Create new todo   |
| PUT    | /todos/{id}    | Update todo       |
| DELETE | /todos/{id}    | Delete todo       |

---

## How to Run Locally

### Backend
1. Navigate to Backend folder
2. Run:

./mvnw spring-boot:run

3. Server runs on:

http://localhost:8080


### Frontend
1. Navigate to Frontend folder
2. Install dependencies:

npm install

3. Start:

npm run dev


---

## What This Project Demonstrates

- Understanding of REST API design
- Database integration using JPA
- Frontend-Backend communication
- Full-stack architecture
- Docker-based deployment setup

---

## Conclusion

This project demonstrates a complete full-stack application workflow, including backend REST API development, database integration, frontend implementation, and containerized deployment setup.  

It reflects practical understanding of real-world application architecture and full-stack development concepts.

---

## Author
Developed by Ruchika N  
