# Hibernate
Hibernate CRUD operation project with console
The project aims to demonstrate basic CRUD operations using Hibernate, a popular Object-Relational Mapping (ORM) framework. It provides a simple console interface to interact with the database.

Technologies Used:
Java
Hibernate
MySQL

Project Structure:

This project utilizes an Employee entity class, which represents the structure of an Employee table in a MySQL database. The primary objective is to automatically generate the Employee table within the MySQL database and execute CRUD (Create, Read, Update, Delete) operations on this table from within the project. The project employs essential Hibernate classes such as SessionFactory, Session, and Transaction to facilitate database interactions.
Key annotations used in this project include @Entity and @Id, which define the mapping between the Java entity class and the corresponding database table.
Additionally, the Hibernate configuration file plays a crucial role in this project. It allows specifying essential parameters such as the driver name, database URL, database username, password, Dialect class name, and mapping for the entity class. This configuration ensures seamless integration between the Java application and the MySQL database.
