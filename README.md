# Overview
A RESTful API service built using Spring Boot to manage an online Book Rental System while using MySQL to persist the data.

# Features
* Authentication and Authorization : Implemented using Basic Auth with two roles: USER and ADMIN.
* User management:
  + User registration with email, password (encrypted using BCrypt), first name, last name, and role.
  + User login using email and password.
* Book management:
  + Store and manage book details such as title, author, genre, and availability status.
  + Create, update and delete books.
* Rental management:
  + Rent a book with book id and user id.
  + Return rented book.

# Getting Started:
## Prerequisites:
* Java 17 or higher
* MySql
* Postman for API Testing

## Configuration:
1. Open the application.properties file located in src/main/resources directory.
2. Configure the MySQL database connection settings:
   
   spring.datasource.url = jdbc:mysql://localhost:3306/rentread
   
   spring.datasource.username = root
   
   spring.datasource.password = password

   Replace localhost, 3306, root and password with your MySQL host, port, username and password respectively.

   Save the changes to the application.properties file.

## Running the application:
Run the application using Gradle:
./gradlew bootrun

# API Endpoints

You can find the API endpoints and test them using the provided:  https://elements.getpostman.com/redirect?entityId=36793359-e2ba3dad-40a3-4f24-8fbd-699d1a75be8b&entityType=collection



   
