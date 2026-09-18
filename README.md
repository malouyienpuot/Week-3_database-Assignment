# Week 3 Database Assignment

## Student Database Management

This project contains the SQL solution for the Week 3 database assignment.

### Questions covered

1. Create a `student` table with:
   - `id` – integer primary key
   - `fullName` – text up to 100 characters
   - `age` – integer

2. Insert 10 student records with:
   - Name
   - Age
   - Nationality
   - Gender
   - Sample marks
   - Grade

3. Use a transaction to update the age of student ID 2 to 20.

### Grade scale

| Marks | Grade |
|---|---|
| 80–100 | Excellent |
| 60–79 | Very Good |
| 40–59 | Good |
| Below 40 | Poor |

The marks are sample values used to demonstrate SQL grading and aggregate functions.

### SQL concepts demonstrated

- CREATE DATABASE
- CREATE TABLE
- INSERT
- START TRANSACTION
- COMMIT
- UPDATE
- CASE
- ORDER BY
- COUNT()
- AVG()
- MAX()
- MIN()
- GROUP BY

## How to run

Open MySQL Workbench or the MySQL command line and run:

```sql
SOURCE answer.sql;
```

Or copy and execute the contents of `answer.sql`.
