# CRUD Example of Spring5 MVC with JdbcTemplate and MariaDB From Scratch
Sometime we waste our time to create a new project from scratch. Just clone this project. Run on your local machine.
Smile and happy Coding.

## Project Requirements
- Java 9
- Tomcat 9
- Maven 3.5
- Intellij Idea (Editor)

### Set up MySQL
```
mysql -u root -p 
> CREATE USER 'crud_mis'@'localhost' IDENTIFIED BY 'm1$4PASS';
> GRANT ALL PRIVILEGES ON *.* TO 'crud_mis'@'localhost';
> FLUSH PRIVILEGES;
>
> CREATE DATABASE db_crudMis;
```

Now we need to import schema to database.

```
mysql -u regUsers -p db_crudMis < project/location/CRUD/schema/schema-initial.sql
```
### Run
Run with your editor.
check 'project/location/CRUD/schema/schema-initial.sql' for username and password.

#### -- THANK YOU
