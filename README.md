# Student Management System

## Overview

Student Management System is a web-based application developed using ASP.NET Core MVC, Entity Framework Core, and MySQL. The application allows users to manage student records efficiently through complete CRUD (Create, Read, Update, Delete) operations.

## Features

* Add new student records
* View all student details
* Update existing student information
* Delete student records
* MySQL database integration
* Responsive user interface using Bootstrap
* MVC architecture implementation

## Technologies Used

* ASP.NET Core MVC
* C#
* Entity Framework Core
* MySQL
* HTML
* CSS
* Bootstrap
* Visual Studio 2022

## Database Structure

### Students Table

| Column | Data Type                         |
| ------ | --------------------------------- |
| Id     | INT (Primary Key, Auto Increment) |
| Name   | VARCHAR(100)                      |
| Course | VARCHAR(100)                      |
| City   | VARCHAR(100)                      |

## Installation Steps

1. Clone the repository

```bash
git clone https://github.com/your-username/student-management-system.git
```

2. Open the project in Visual Studio 2022

3. Create the MySQL database

```sql
CREATE DATABASE StudentDB;

USE StudentDB;

CREATE TABLE Students
(
    Id INT PRIMARY KEY AUTO_INCREMENT,
    Name VARCHAR(100),
    Course VARCHAR(100),
    City VARCHAR(100)
);
```

4. Configure the connection string in `appsettings.json`

```json
"ConnectionStrings": {
  "DefaultConnection": "server=localhost;database=StudentDB;user=root;password=your_password;"
}
```

5. Run the application

## Project Structure

* Models

  * Student.cs
  * AppDbContext.cs

* Controllers

  * StudentController.cs

* Views

  * Index.cshtml
  * Create.cshtml
  * Edit.cshtml

## CRUD Operations

### Create

Add new student records to the database.

### Read

Display all students in a table format.

### Update

Modify existing student information.

### Delete

Remove student records from the database.

## Learning Outcomes

* Understanding ASP.NET Core MVC architecture
* Working with Entity Framework Core
* Connecting applications with MySQL databases
* Implementing CRUD operations
* Designing responsive interfaces using Bootstrap
* Following MVC design patterns

## Author

Priyanka Panchal

GitHub: https://github.com/priyankapanchal9978
