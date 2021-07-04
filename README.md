<h1>:oncoming_taxi:Taxi Service </h1>

<h3>:book:Description</h3>
This is a pet-project gives us an opportunity to manage taxi company. Project has such functions: adding, deleting and editing information about drivers, cars and cars manufacturers.

<h3>:hammer_and_wrench:Project Structure</h3>

:one: **DAO layer** - responsible for connetction to database, build with JDBC API, based on CRUD.

:two: **Service layer** - includes all businness logic. Authentication and authentication filter invoked, which controls access to service functionality.

:three: **Presentation layer** - for displaying application, based on JSP pages, HTML, CSS, JSTL, servlets - responsible for receiving and responding client requests.


<h3>:gear:Technologies used</h3>

* Backend: Java, JDBC, Servlets
* Frontend: HTML, CSS, JSP and JSTL
* Databases: RDBMS MySQL
* Web-server: Apache Tomcat
* Packaging: Apache Maven

<h3>:smiley:Try it by yourself</h3>

1. Clone this project into your local folder and open the project in an IDE.

2. Configure Tomcat Server and set up the MySQL RDBMS on your computer.

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
