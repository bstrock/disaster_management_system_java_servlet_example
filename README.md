<h1>Java Servlet Example: Disaster Management System</h1>
This is a fully functional full-stack web app designed to allow for reporting of disasters and requests related to disaster recovery, written for a class in Geospatial Web and Mobile Programming.  The lab assignment was designed to provide a basic overview of Java class/project structure, Servlets, Apache Tomcat, JSP, and JDBC.  I completed the assignment by rewriting the application in order to improve the security implementation and provide for a more flexible codebase.<br><br>

<h2>Tech Stack</h2>

* Java/JavaEE
* HTTPServlet
* Apache Tomcat
* JDBC
* Java PostGIS and GeoJSON packages
* Maven
* HTML5
* CSS
* Bootstrap
* Javascript
* JQuery

<h2>Project Features</h2>

**Back end:**

* Java HTTPServlet provides API interface between frontend JSP and database using JDBC
* Business logic utilizes Prepared Statements instead of raw SQL exectution
* Programmatic approach to database operations by using metadata objects to perform CRUD operations using type inference
* Fully implements Java PostGIS objects interface for geospatial database operations, rather than relying on SQL strings
* Commenting and logging throughout provides clarity and informs efficient debugging

**Front end:**

* Web interface initializes with a map of all reports currently active in the database
* Uses Google Maps API to provide basemap, POI interface, and address autocompletion
* User-submitted reports represented by map pins with callouts containing detailed report information
* Offers users a Query tab to allow filtering the underlying database
* Offers users an intake form to allow for user report submissions
* Successful submission will zoom to report location and display map pin for the report
* Seperate test script to assist with debugging and refactoring
