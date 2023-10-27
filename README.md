# Laravel Student Management Application

This is a Laravel-based application for managing student records. It provides API endpoints for listing, creating, updating, and deleting student records.

## Installation

1. Create a new Laravel project:
   ```shell
   composer create-project laravel/laravel lbs-app
Configure the database in the .env file

Run database migrations to create the students table:
  ```shell
  php artisan migrate
  ```


Run the application:
 ```shell
 php artisan serve
 ```

  

  
Access the API endpoints provided by the StudentController for student management.

API Endpoints
GET /api/student: List all students.


POST /api/student: Create a new student.


GET /api/student/{id}: Get a student by ID.


PUT /api/student/{id}: Update a student.

DELETE /api/student/{id}: Delete a student.   


# Angular front end code for this app:
https://github.com/krishnarajj/frontend-
