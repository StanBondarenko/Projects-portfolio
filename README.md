# Projects

A curated list of my software development projects, organized by area and purpose.

This repository serves as a portfolio entry point with links to my main work.

---

## Backend Projects

### Library Management System (Java, JDBC, PostgreSQL)
Console-based Java backend application focused on clean architecture and database interaction.

Key aspects:
- JDBC integration with PostgreSQL
- DAO pattern for data access abstraction
- Layered architecture (domain, DAO, system layers)
- Console-based navigation and input validation

Repository:
https://github.com/StanBondarenko/library-management-system

### Picture Gallery API (Java, Spring Boot, JDBC, PostgreSQL)

Backend REST API for managing and exploring a picture gallery domain.

The project was built with a database-first approach and focuses on backend architecture, data access, and security.  
It provides endpoints for working with pictures, authors, eras, techniques, plots, and users.

Key highlights:
- Spring Boot REST API
- JDBC / JdbcTemplate with DAO pattern
- Clear separation between controllers, DAO interfaces, and JDBC implementations
- RowMapper-based mapping from ResultSet to POJOs
- JWT-based authentication and role-based authorization
- Many-to-many relationships (user favorite authors and pictures)
- API testing with Postman
- ERD and UML diagrams included for database and architecture overview

The project is intentionally backend-only.  
A client application will be implemented as a separate final project.

Repository:  
https://github.com/StanBondarenko/picture-gallery-api

---

## Frontend Projects

### Tetris (Vanilla JavaScript)

Browser-based implementation of the classic Tetris game built with **HTML, CSS, and Vanilla JavaScript**, without using any frameworks.

The project focuses on core frontend fundamentals:
- game state management
- grid-based algorithms
- collision detection
- keyboard input handling
- DOM rendering without external libraries

Key highlights:
- Separate logic matrix and visual (DOM) matrix
- Manual collision detection and figure rotation logic
- Line clearing and scoring system
- Dynamic speed increase based on cleared lines
- Next figure preview
- ES Modules–based project structure

The game is currently implemented using plain JavaScript to demonstrate low-level control over game logic and rendering.  
A future iteration of the project will include a rewritten version using **React**.

Repository:  
https://github.com/StanBondarenko/tetris-game-frontend

---
## Fullstack Projects

### Home Recipe Organizer

A full-stack web application designed to help users decide what to cook based on the ingredients they already have at home.

The project combines a **React-based frontend** with a **Java Spring Boot backend** and a **PostgreSQL** database.  
It focuses on real-world business logic, clean architecture, and clear separation of concerns between client and server.

#### Core functionality:
- user registration and authentication (JWT)
- ingredient management (add, update, delete, unit conversion)
- recipe browsing and filtering
- recipe matching based on available ingredients
- favorite recipes per user
- step-by-step cooking instructions

#### Backend highlights:
- RESTful API built with Java and Spring Boot
- layered architecture (controllers, services, DAO)
- JDBC (`JdbcTemplate`) with explicit SQL for core domain logic
- Spring Data JPA for reference data
- JWT-based stateless authentication
- role-based authorization
- centralized exception handling

#### Frontend highlights:
- single-page application built with React
- client-side routing with React Router
- state management using React Hooks
- authenticated API communication via Axios
- dynamic UI updates based on backend responses
- reusable components and form-based workflows

The project is implemented as a portfolio-grade application and reflects real full-stack development workflows, from database design to UI interaction.

Repository:  
[https://github.com/StanBondarenko/home-recipe-organizer](https://github.com/StanBondarenko/home-recipe-organizer)

---

## Practice Repositories

These repositories are used for learning, experimentation, and skill development.

- Java practice:  
https://github.com/StanBondarenko/java/tree/main/classes-practice (or current `java` repo)

- Frontend practice:  
  (link will be added)
