# Book Store MVC Application

This is a Book Store application developed using Spring Boot for the backend and React for the frontend. It implements a simple MVC architecture, allowing users to view books and admins to manage the inventory.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Jenkins CI/CD](#jenkins-cicd)

## Features
- **User Role**: Browse books and add them to the shopping cart.
- **Admin Role**: Add, edit, or delete books from the inventory.
- **Responsive UI**: Built with React for a modern user experience.
- **Dockerized**: Containerized frontend and backend for easy deployment.

## Technologies
- **Frontend**: React
- **Backend**: Spring Boot
- **Database**: In-memory data storage using JpaRepository
- **Testing**: JUnit for backend testing
- **CI/CD**: Jenkins for automated build and deployment
- **Containerization**: Docker

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Manafmakkah/Book-Store-MVC.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Book-Store-MVC
   ```
3. For the **backend**:
   - Navigate to the backend directory and run:
     ```bash
     ./mvnw spring-boot:run
     ```
4. For the **frontend**:
   - Navigate to the frontend directory and run:
     ```bash
     npm install
     npm start
     ```

## Usage
- Open your browser and visit `http://localhost:3000` to access the application.
- Navigate through the site using the provided links in the navigation bar.

## Testing
- Run JUnit tests for the Spring Boot application:
  ```bash
  ./mvnw test
  ```

## Jenkins CI/CD
- The Jenkins pipeline automates the build, test, and deployment processes. It sends notifications upon build success or failure.

```
