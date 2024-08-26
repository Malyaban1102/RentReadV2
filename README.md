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

You can find the API endpoints and test them using the provided:  https://speeding-flare-905775.postman.co/workspace/rentreadV2~60effe98-05bb-4b52-8f92-a52549e9f657/collection/37911870-cc1e935a-4c34-4206-b841-0b660d58f097?action=share&source=copy-link&creator=37911870


   
