# Student Management System

## Overview
This project is a simple Student Management System designed using SQL. It includes operations to manage student details, courses, and grades.

## Database Schema
1. **Students**: Stores student details.
2. **Courses**: Stores course details.
3. **Grades**: Stores student grades for courses.

## How to Run
1. Create a database in your SQL server.
2. Run the `schema.sql` script to create tables.
3. Run the `data.sql` script to insert sample data.
4. Use the `queries.sql` script for basic operations.

## Example Queries
- Get all students:
```sql
SELECT * FROM Students;
