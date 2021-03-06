# **TAXI SERVICE**
____
Is a simple application that implements a taxi service.
____
#### STRUCTURE OF THE PROJECT:
Project based on 3-layer architecture:
* Presentation layer
* Application layer
* Data access layer
____
#### TECHNOLOGIES:
* Apache Tomcat
* MySQL
* JDBC
* Servlet
* JSP
* JSTL
* HTML, CSS
* Maven
* Maven Checkstyle Plugin
____
#### FUNCTIONALITY:
* Create and delete a car
* Create and delete production
* Get all manufacturers
* Get all the drivers
* Add a driver to the car
____
#### SETUP:
* Apache Tomcat
* Install MySQL and MySQL Workbench
* Create a schema by using the script from resources/init_db.sql in MySQL Workbench
* In the taxi/util/ConnectionUtil.java change the URL, USERNAME and PASSWORD
* Change full path in log4j.xml file if you want to use logger 