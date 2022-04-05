Simple application to check my skills. Used SOLID principles. Authentication made with filter and sessions. Every logging attempt is added to the .log file. Registration of new drivers, managing the relations between cars, drivers, and manufacturers, all the CRUD operations are implemented. The program has the following functionality:

Functional:

- Display all Drivers
- Display all Cars
- Display All Current Cars
- Display all Manufacturers
- Create new Driver
- Create new Car
- Create new Manufacturer 
- Add driver to car

--------------------------
3-layer architecture:

- DAO - Data access layer
- Service - Application layer
- Controllers - Presentation layer

----------------------------
Technologies:

- Java 17
- Apache Tomcat - v.9
- MySQL
- Servlet
- JSTL
- JSP

-----------------------------
To run the program :

- Install MySQL and Apache Tomcat version 9.
- Configure Apache Tomcat for your IDE.
- Use "/resources/init_db.sql" for creating a schema and tables.
- Configure "/util/ConnectionUtil.java" with your URL, USERNAME, PASSWORD, JDBC_DRIVER.
- For logging: change the fileName value: "ABSOLUTE_PATH" in the "resources/log4j2.xml" file with an absolute path to your log file.
- Configure the tomcat library path in the startup settings.

------------------------------
Author

Ihor [telegram](https://t.me/iddqdd42)

Mail: <b>lugburz.hr</b> on google's mail.