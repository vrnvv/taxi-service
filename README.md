# taxi-service
### Project description:
```
A simple web-application that supports authentication, registration and other CRUD operations.
```
### Available functionality
* register as a driver;
* login as driver;
* create/update/delete a driver;
* display all drivers;
* create/update/delete a car;
* display all cars;
* create/update/delete a manufacturer;
* display all manufacturers;
* add a driver to a car;
* display all cars for current login driver;

### Project structure

* Controller - responsible for handling incoming messages, interacting with the user interface, and passing data to the business layer.
* Service - responsible for performing various operations and data manipulations, such as checking access rights, data validation, calculations, etc.
* DAO - responsible for interacting with the database, reading and writing data, executing queries and processing results.
Service - accepts requests from the controller, passes them to the DAO layer, and performs all business logic
DAO - accepts requests from the service, passes them to the DB, and executes all sql queries

### Technologies:
Tomcat 9.0.76
Maven 3.1.1
Java 11
MySQL 8.0.22
Servlet Api 4.0.1
JSTL 1.2
JDBC
JSP

### Installation:
1. Clone the project
2. [Install MySQL](https://downloads.mysql.com/archives/installer/)
3. [Install Apache Tomcat](https://tomcat.apache.org/download-90.cgi)
4. Copy and run SQL script from resources/init_db.sql
5. Write your properties to ConnectionUtil class
6. Configure Apache Tomcat version: 9.0.76
7. Run the project
