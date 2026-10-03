CREATE DATABASE employee_db;
USE employee_db;
CREATE TABLE Employee(
    emp_id INT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    email VARCHAR(100) NOT NULL UNIQUE,
    age INT CHECK (age >= 18),
    department VARCHAR(50) NOT NULL DEFAULT 'Marketing',
    salary int NOT NULL CHECK (salary>0)
);
INSERT INTO Employee (emp_id, name, email, age, department, salary)
VALUES
(101, 'Aman', 'aman@gmail.com', 22, 'IT', 45000),
(102, 'Rahul', 'rahul@gmail.com', 25, 'HR', 38000),
(103, 'Rohan', 'rohan@gmail.com', 24, 'IT', 55000),
(104, 'Priya', 'priya@gmail.com', 27, 'Finance', 60000),
(105, 'Harkirat', 'Harkirat@gmail.com', 23, 'HR', 42000);
SELECT * FROM Employee;
SELECT * FROM Employee WHERE salary > 45000;
UPDATE Employee SET salary = 55000 WHERE department='IT';
SELECT * FROM Employee;  
DELETE FROM Employee WHERE emp_id = 105;
SELECT * FROM Employee;
ALTER TABLE Employee ADD phone VARCHAR(15);
SELECT * FROM Employee;
TRUNCATE TABLE Employee;
SELECT * FROM Employee; 