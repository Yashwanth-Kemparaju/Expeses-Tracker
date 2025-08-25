Expense Tracker Web Application
## Project Description
The Expense Tracker is a full-stack web application designed to help users manage their personal finances. It provides a secure and intuitive platform for tracking expenses, categorizing spending, and gaining insights into financial habits. This project was built using a modern Java technology stack to create a robust and scalable solution.

## Core Features
User Authentication: Secure user registration and login system using Spring Security.

CRUD Operations: Users can Create, Read, Update, and Delete their personal expenses.

Expense Categorization: Ability to assign a category to each expense for better organization.

Data Filtering: Functionality to filter and search through expenses.

## Technology Stack
Backend: Spring Boot, Spring MVC, Spring Data JPA, Spring Security

Frontend: Thymeleaf, HTML, CSS, Bootstrap

Database: MySQL

Build Tool: Maven

## Setup and Installation
To run this project locally, follow these steps:

Prerequisites:

Java JDK 21 or later

Apache Maven

MySQL Server

Clone the Repository:

Bash

git clone https://github.com/Yashwanth-Kemparaju/Expeses-Tracker.git
Database Configuration:

In MySQL, create a new database: CREATE DATABASE expenses_tracker;

Open src/main/resources/application.properties.

Update the spring.datasource.url, spring.datasource.username, and spring.datasource.password properties with your local MySQL credentials.

Run the Application:

Navigate to the project directory and run: mvn spring-boot:run

The application will be accessible at http://localhost:8081.
