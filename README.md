# Spring MVC Employee Manager

## Description
A traditional web application built using the Spring Web MVC framework and Java Server Pages (JSP). It allows users to perform CRUD operations on an employee database using Spring's `JdbcTemplate`.

## Concepts Demonstrated
* **Spring MVC:** Utilizing `DispatcherServlet`, Controllers, and View Resolvers.
* **JdbcTemplate:** Writing safe, boilerplate-free SQL queries in Spring.
* **JSP Views:** Generating dynamic HTML using Spring Form tags and JSTL.
* **XML Configuration:** Configuring beans and data sources via `spring-servlet.xml`.

## Features
* **Employee Forms:** Add new employees or edit existing ones.
* **Employee List:** View a complete tabular list of all employees (Name, Salary, Designation).
* **Database Operations:** Add, Update, and Delete actions persist directly to the database.

## Setup & Configuration
1. **Database:** Run MySQL. Create a database `test` and a table `Emp99` (id, name, salary, designation).
2. **Tomcat:** This is a dynamic web project. You will need Apache Tomcat installed.
3. **Deployment:** Add the project to your Tomcat server within your IDE (Eclipse/IntelliJ) and ensure the Spring libraries and MySQL Connector are in the `WEB-INF/lib` folder (or handled via Maven).

## How to Run
Start the Tomcat server. Navigate to `http://localhost:8080/YourProjectName/` to access the `index.jsp` welcome page.
