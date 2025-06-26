# HR Schema and Database (MySQL)

This project implements a comprehensive HR (Human Resources) database schema using MySQL. It includes table definitions, data insertion scripts, and analytical SQL queries. The project demonstrates proficiency in relational database design, DDL/DML scripting, and query writing for real-world HR data management scenarios.


## Technologies Used

- **Database:** MySQL
- **Language:** SQL (DDL & DML)
- **Concepts:** Primary & Foreign Keys, Constraints, Joins, Aggregations

## Description

This database models an HR system, covering key entities such as regions, countries, locations, departments, jobs, employees, and job history. It provides a realistic data model for managing employee records and historical job data within an organization.

### Schema Features

- Normalized structure with referential integrity
- Use of `DATE` data types for temporal tracking
- Composite primary keys in job history
- Hierarchical relationships (e.g., managers referencing employees)

### Data Inserted

- 2 regions  
- 3 countries  
- 5 different locations  
- 6 departments  
- 10+ employees with realistic roles and salaries  
- 8+ distinct job positions  
- Job history records with at least 2 employees having more than 2 records

## SQL Queries

**1. List all employees whose salary is greater than 10,000, sorted from highest to lowest.**  
**2. List all departments located in the state "Ha Noi".**  
**3. List all employees who have two or more job history records.**  
**4. List all employees who have worked in two or more departments.**  
