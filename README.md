# Final_Project_SQL

University Database Management System

📌 Project Overview

The University Database Management System is a MySQL-based database project designed to manage university information such as departments, students, courses, instructors, and student enrollments.

This project demonstrates important SQL concepts including DDL, DML, CRUD operations, JOINs, aggregate functions, GROUP BY, subqueries, and CASE expressions.

⸻

🎯 Project Objectives

* Manage university departments
* Store student information
* Manage courses and departments
* Store instructor information and salaries
* Manage student course enrollments
* Perform CRUD operations
* Retrieve data using SQL queries
* Use JOIN operations between multiple tables
* Perform aggregate calculations
* Demonstrate subqueries
* Use CASE expressions for student classification

⸻

🗄️ Database Name

UniversityDB

⸻

📊 Database Tables

The project contains the following tables:

1. Departments

Stores information about university departments.

Columns:

* DepartmentID
* DepartmentName

2. Students

Stores student personal and enrollment information.

Columns:

* StudentID
* FirstName
* LastName
* Email
* BirthDate
* EnrollmentDate

3. Courses

Stores information about courses offered by departments.

Columns:

* CourseID
* CourseName
* DepartmentID
* Credits

4. Instructors

Stores instructor information and salary details.

Columns:

* InstructorID
* FirstName
* LastName
* Email
* DepartmentID
* Salary

5. Enrollments

Stores student course enrollment information.

Columns:

* EnrollmentID
* StudentID
* CourseID
* EnrollmentDate

⸻

🔗 Relationships

The database uses Primary Keys and Foreign Keys to maintain relationships between tables.

* Courses.DepartmentID → Departments.DepartmentID
* Instructors.DepartmentID → Departments.DepartmentID
* Enrollments.StudentID → Students.StudentID
* Enrollments.CourseID → Courses.CourseID

⸻

🛠️ SQL Concepts Used

This project demonstrates:

* CREATE DATABASE
* DROP DATABASE
* CREATE TABLE
* INSERT
* SELECT
* UPDATE
* DELETE
* WHERE
* INNER JOIN
* LEFT JOIN
* GROUP BY
* HAVING
* LIMIT
* Aggregate Functions
    * AVG()
    * MAX()
    * COUNT()
* Subqueries
* CASE Expression
* Foreign Keys
* Primary Keys
* Date Functions
* YEAR()
* CURDATE()

⸻

🔍 Queries Included

CRUD Operations

The project demonstrates basic CRUD operations:

* Create – Insert records
* Read – Select records
* Update – Update student email
* Delete – Delete a student record

Student Filtering

Finds students enrolled after 2022.

Department-Based Course Search

Finds Mathematics department courses using JOIN.

Average Course Credits

Calculates the average number of credits offered by courses.

Maximum Instructor Salary

Finds the highest instructor salary.

Student and Course Details

Displays students along with their enrolled courses using INNER JOIN.

All Students and Courses

Displays all students and their courses using LEFT JOIN.

Course-Wise Student Count

Counts the number of students enrolled in each course.

Subquery

Finds students enrolled in courses having more than one student.

CASE Expression

Classifies students as Senior or Junior based on their enrollment duration.

⸻

▶️ How to Run the Project

1. Open MySQL Workbench or another MySQL-compatible SQL editor.
2. Open the SQL file.
3. Copy and execute the complete SQL script.
4. The existing UniversityDB database will be removed automatically.
5. A new UniversityDB database will be created.
6. Tables and sample data will be inserted.
7. Execute the queries to view the results.

⸻

📁 Project Structure

UniversityDB/
│
├── UniversityDB.sql
└── README.md

⸻

👩‍💻 Author

Janvi

⸻

📚 Purpose

This project was created for learning and practicing MySQL Database Management and SQL concepts.
