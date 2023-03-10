# SQL Employee Tracker

## Module-12 SQL: 
```md
A command-line application that manages a company's employee database using Node.js, Inquirer, and MySQL.
```

## Table of Contents

 * [User-Story](#user-story)
 * [Acceptance-Criteria](#acceptance-criteria)
 * [Installation](#installation)
 * [Application-Demonstration](#application-demonstration)
 * [Application-Link](#application-link)

## User Story

```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database
```
## Installation

```md
Right click on the SQL-Employee-Tracker folder and click "Open in integrated terminal"
Execute the following commands: 
"npm i" 
"npm i mysql2"
"npm i inquirer"
"npm i console.table"
right click on the db folder and click on "Open in integrated terminal" and execute the following:
"mysql -u root -p" then enter your password
"source schema.sql"
"source seed.sql"
Then type "exit" to terminate mysql
type "cd .." to return to the previous directory
type "npm start" to start the database
```

## Application Demonstration

![](./assets/images/demo.png)


## Video Demonstration

https://drive.google.com/file/d/1BiBChx3bHtXeXsJw-BDefr9d-0ji0fFr/view?usp=share_link