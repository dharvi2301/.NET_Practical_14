# SQL Employee Pagination & Search Demo

This SQL script demonstrates a basic Employee table setup used for implementing features like **pagination**, **search**, and **filtering** in web applications. The data inserted is purely for testing purposes.

## Database Creation and Setup

```sql
-- Create the database
CREATE DATABASE Practical14;
GO

-- Use the database
USE Practical14;
GO
```

## Create Employee Table

```sql
CREATE TABLE Employee (
    Id INT IDENTITY(1,1) PRIMARY KEY NOT NULL,
    Name VARCHAR(50) NOT NULL,
    DOB DATE NOT NULL,
    Age INT
);
```

## Insert Dummy Records for Testing

```sql
INSERT INTO Employee (Name, DOB, Age) VALUES
('Arjun', '1991-03-12', 33),
('Bhavna', '1986-09-28', 38),
('Chetan', '1993-07-19', 31),
('Deepika', '1989-11-10', 35),
('Eshan', '1996-05-05', 28),
('Fatima', '1992-02-17', 32),
('Gaurav', '1990-10-22', 34),
('Harshita', '1988-04-14', 36),
('Irfan', '1997-01-09', 27),
('Jasmine', '1995-08-30', 29),
('Karan', '1987-12-11', 37),
('Lata', '1985-03-05', 39),
('Manoj', '1994-06-01', 30),
('Nikita', '1993-09-23', 31),
('Om', '1995-11-18', 29),
('Pooja', '1991-07-04', 33),
('Ravi', '1988-01-25', 36),
('Sneha', '1997-04-15', 27),
('Tanmay', '1992-12-07', 32),
('Urvashi', '1989-06-20', 35),
('Varun', '1990-09-01', 34),
('Waseem', '1987-05-13', 37),
('Zara', '1994-03-27', 30),
('Yuvraj', '1996-02-02', 28),
('Isha', '1993-10-16', 31);
```

## Below are the output of the project
![image](https://github.com/user-attachments/assets/e99cd60b-0046-403b-973b-59c3c555c71f)
![image](https://github.com/user-attachments/assets/2d075322-833d-4500-922c-a15cf750afba)
![image](https://github.com/user-attachments/assets/988c7dbd-a78a-4840-acf5-dac8995892ee)
![image](https://github.com/user-attachments/assets/708318aa-1756-4dec-bcdc-1c57d571833f)
![image](https://github.com/user-attachments/assets/72bed5ca-1c7d-4e1f-af1a-fc4fe54a559a)
![image](https://github.com/user-attachments/assets/852666f6-08ad-4799-b3d2-fe614a458569
![image](https://github.com/user-attachments/assets/fdb041ef-67c5-4fb3-b611-7f1905e84c43)







## Purpose

This data can be used for testing:
- Pagination logic (limit-offset or page-size)
- Search functionality by name or age
- Sorting and filtering
