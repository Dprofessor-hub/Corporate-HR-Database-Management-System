# Corporate HR Database Management System

## Overview

This project is a MySQL-based Corporate HR Database Management System designed to manage employee, department, and project information. The database simulates a real-world corporate environment where employees belong to departments, work on projects, and contribute hours toward project completion.

The project demonstrates database design, data manipulation, reporting, automation, and advanced SQL concepts through a structured HR management system.

---

## Project Objective

Organizations require efficient systems to manage employee records, departmental information, project assignments, and workforce reporting.

This project aims to:

* Design a relational database from scratch.
* Manage employee and department data.
* Track employee project assignments.
* Generate business reports using SQL queries.
* Automate database operations using procedures and functions.
* Perform advanced analytics using window functions.

---

## Database Structure

### Department Table

Stores department information.

Fields:

* Department ID
* Department Name

### Employee Table

Stores employee details.

Fields:

* Employee ID
* Employee Name
* Department ID
* Designation
* Salary
* Hire Date

### Project Table

Stores project information.

Fields:

* Project ID
* Project Name
* Department ID
* Budget

### Employee Project Table

Stores project assignments.

Fields:

* Assignment ID
* Employee ID
* Project ID
* Hours Worked

---

## SQL Concepts Implemented

### Database Design (DDL)

* Database Creation
* Table Creation
* Primary Keys
* Foreign Keys
* Constraints
* Index Creation

### Data Manipulation (DML)

* Insert Records
* Update Records
* Delete Records

### Data Querying (DQL)

* Employee Analysis
* Department Salary Analysis
* Project Hours Tracking
* Highest Paid Employee Identification

### Joins

* Employee and Department Mapping
* Project Assignment Reporting
* Unassigned Employee Detection

### Views

* Department-wise Salary Expense
* Above-Average Salary Employees

### Stored Procedures

* Retrieve Employees by Department
* Salary Increment Automation

### Functions

* Annual Salary Calculation

### Window Functions

* Employee Salary Ranking
* Second Highest Salary by Department
* Running Salary Totals

---

## Dataset Information

The project uses:

* 100 Employee Records
* 5 Departments
* 20 Projects
* 200 Employee-Project Assignments

---

## Technologies Used

* MySQL
* SQL
* Relational Database Design
* CSV Data Import

---

## Key Business Reports

* Average Salary by Department
* Total Hours Worked per Project
* Highest Paid Employee by Department
* Department-wise Salary Expense
* Employee Salary Rankings
* Project Resource Allocation

---

## Skills Demonstrated

* Database Design
* Data Modeling
* SQL Query Writing
* Joins
* Views
* Stored Procedures
* User Defined Functions
* Window Functions
* Data Management

---

## Business Value

This project demonstrates how relational databases can be used to manage workforce information, track project assignments, monitor salary expenses, and generate business reports that support organizational decision-making.

---

## Author

Developed as a SQL and Database Management portfolio project to demonstrate database design, query optimization, reporting, and advanced MySQL concepts.
