# Taxi service
This is a simple web app for simulating taxi service based on Stateful Web Service,
at first you have to pass authentication or create a new driver which login and password
will be your for authentication to the service.
## Available functions:
* Ability to create driver, manufacturer or car
* Ability to delete driver, manufacturer or car
* Ability to get all drivers, manufacturers or cars
* Ability to add driver by driver id to car by car id
* Ability to see your current cars
## Implementation details in project:
* 3 layer architecture
    - Controllers
    - Services
    - DAO
* Dependency injection and Inversion of control
## Technologies used in project:
* Apache Tomcat (v9.0.55)
* JDBC
* MySQL
* Servlet
* JSP
* JSTL
* HTML, CSS
* Maven
## Recommendations to run project:
1. Install Intellij IDEA Ultimate Edition
2. Install Apache Tomcat version 9.0.55
3. Install MySQL and MySQL Workbench
4. Create a schema in MySQL Workbench using resources/init_db.sql
5. Add your DB Properties in ConnectionUtil class
6. Edit your Tomcat configuration
7. After running tomcat go to http://localhost:your port and create a new driver
8. For using logger change full path in log4j2.xml file

![diagram](src/main/resources/join-relations-db-table.png)