🚕 taxi-service 🚕
## About
  This web application represents a simple version of a taxi service.

## Details
- registration a new driver
- log in / log out
- create, update and remove all models
- display list of all manufacturers, cars, drivers, cars of current driver

## Project Structure

In this project used the n-tire architecture

- DAO tire - allows to modify data in database using CRUD methods
- Service tire - this is where all the logic happens
- Controller tire - provides an interface to interact with application

## Technologies

- Java 11
- Maven
- MySQL
- JDBC
- JSP
- Tomcat 

## INSTRUCTIONS FOR LAUNCHING THE PROJECT

- Install MySQL, Apache Tomcat (v 9.0.*), Git, Maven, Java
- Clone the project from GitHub
- Create the necessary tables in your database from the file init_db.sql
- Set URL, USERNAME, PASSWORD, JDBC_DRIVER in /util/ConnectionUtil class
- Add Tomcat server to configuration
- Run project
