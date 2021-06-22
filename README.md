<h1>Taxi Service</h1>
This project is the implementation of online service for internal usage of taxi company, whose functions are adding, deleting and editing information about cars at the cabstand and their manufacturers and drivers.

<h3>Project Structure</h3>

* The project has an N-tier structure and consists of the database layer, the DAO layer for interaction with the database, the service layer which contains the business logic, and the presentation layer.
* The DAO layer is built with the JDBC API.
* Servlets are used to receive and respond to client requests.
* Filters control access to the service's functionality.
* The presentation layer is implemented with JSP pages.
* This project also includes custom-made annotations and an injector, which utilizes Reflection API.

<h3>Technologies used</h3>

* Backend: Java, JDBC, Servlets
* Frontend: HTML, CSS, JSP and JSTL
* Databases: RDBMS MySQL
* Web-server: Apache Tomcat
* Packaging: Apache Maven

<h3>Configuration</h3>

1. Clone this project into your local folder and open the project in an IDE.

2. Configure Tomcat Server and set up the MySQL RDBMS on your machine.

3. Replicate the database from the project by copying the script from init_db.sql into the MySQL Workbench query editor window.

4. Insert your own MySQL username and login in dbProperties in the ConnectionUtil class.

5. Setup new connection with:

    * user: "your username"
    * password: "your password"
    * url: jdbc:mysql://xxxx:yyyy/kkkk?serverTimezone=UTC , where:
      * xxxx - host name,
      * yyyy - port,
      * kkkk - database name
6. Run a project
