<center><h1>Simple Taxi Service</h1></center>

![main_logo](http://royaltaxi247.com/upload/logo.png)

There is simple representation of web application like taxi service 
with authentication for drivers.
It based on 3-tier design architecture, that displayed in DAO, 
Service and Representation levels.

## :clipboard: Functional possibilities

* Login/registration for drivers before start using
* Creating car's manufacturers, cars without drivers, drivers
* Adding drivers to cars
* Updating car's manufacturers, cars without drivers, drivers
* Soft-deleting car's manufacturers, cars, drivers
* Displaying all car's manufacturers, cars, drivers
* Displaying cars for current driver
* Support to logout from service

TIPS: all data store at relative DB.

## :electric_plug: Technologies

* [X] JDK 11
* [X] Maven 3.8.1
* [X] WAR 3.3.2
* [X] MySQL 8.0.22
* [X] JDBC API
* [X] Servlet API 4.0.1
* [X] JSP pages
* [X] HTML/CSS
* [X] JSTL 1.2
* [X] Tomcat 9.0.50/9.0.69
* [X] Field injection

## :computer: Examples

![login_page](https://i.paste.pics/fcb47fbc106e9c4e71fbd7a7320d08ad.png)

![main_page](https://i.paste.pics/3886bf7cf5c8c477787ddc7edfd4d5a8.png)

## How to run application

1. Create fork at Github
2. Clone the project to your work space
3. Install MySQL 8
   * create connection to DB
4. Create schema using [init_db](https://github.com/apc10bbe/taxi-service/blob/first-version/src/main/resources/init_db.sql)
5. Create connection to DB
   * use [ConnectionUtil](https://github.com/apc10bbe/taxi-service/blob/first-version/src/main/java/taxi/util/ConnectionUtil.java) to connect to your DB
   * change URL to yours
   * change USERNAME to yours
   * change PASSWORD to yours
   * change JDBC DRIVER to yours
6. Install [Tomcat 9.0.50/9.0.69](https://tomcat.apache.org/download-90.cgi)
7. Setup configurations on Tomcat and run application