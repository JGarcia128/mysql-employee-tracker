# 12 SQL: Employee Tracker

## Your Task

creating an interface that allow non-developers to easily view and interact with information stored in databases.Building a command-line application from scratch to manage a company's employee database, using Node.js, Inquirer, and MySQL.
I will be creating a walkthrough video that demonstrates the functionality and all of the following acceptance criteria being met.

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
THEN I am presented with the following options: view all employees, view all employees by department, add an employee, add a role, and update an employee role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to view all employees by department
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 