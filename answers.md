1. Components of a DBMS (Database Management System)
A DBMS consists of several key components that work together to manage and organize data effectively. These components include:
1.	Database Engine:
o	Core service for storing, retrieving, and managing data.
o	Handles query execution and transaction processing.
2.	Database Schema:
o	Defines the structure of the database, such as tables, relationships, views, and indexes.
3.	Query Processor:
o	Interprets and executes SQL queries.
o	Converts high-level queries into low-level instructions.
4.	Transaction Management:
o	Ensures data consistency and integrity during simultaneous data access.
o	Implements ACID (Atomicity, Consistency, Isolation, Durability) properties.
5.	Data Storage:
o	Manages the physical storage of data on disk or other media.
o	Includes indexing and data compression for efficiency.
6.	Metadata Catalog:
o	Stores information about the structure of the database, such as table names, column types, and relationships.
7.	User Interface:
o	Allows users to interact with the database via graphical interfaces or command-line tools.
________________________________________
2. What is a Relational Database? Provide 4 Examples.
A relational database organizes data into structured tables with rows and columns. Each table has a unique identifier, called a primary key, and tables can be linked through relationships.
Examples:
1.	MySQL
2.	PostgreSQL
3.	Oracle Database
4.	Microsoft SQL Server
________________________________________
3. Three Classifications of SQL
1.	Data Definition Language (DDL):
o	Used to define and manage the structure of the database.
o	Commands: CREATE, ALTER, DROP, TRUNCATE.
o	Example: CREATE TABLE students (id INT, name VARCHAR(50));
2.	Data Manipulation Language (DML):
o	Used to manipulate the data stored in the database.
o	Commands: SELECT, INSERT, UPDATE, DELETE.
o	Example: INSERT INTO students VALUES (1, 'Alice');
3.	Data Control Language (DCL):
o	Used to control access to data and manage database permissions.
o	Commands: GRANT, REVOKE.
o	Example: GRANT SELECT ON students TO user1;
________________________________________
4. Difference Between a Primary Key and a Foreign Key
Primary Key	Foreign Key
Uniquely identifies each row in a table.	Refers to the primary key of another table.
Cannot contain duplicate or NULL values.	Can contain duplicate and NULL values.
Defines entity integrity.	Defines referential integrity.
Example: id column in a students table.	Example: student_id in a grades table referencing id in students.
________________________________________
5. What is an Entity-Relationship Diagram (ERD)?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities (e.g., tables) in a database and their relationships.
•	Entities: Represent objects or tables, such as "Students" or "Courses".
•	Attributes: Represent fields or columns within the entities, like "Name" or "ID".
•	Relationships: Define how entities are related (e.g., one-to-many, many-to-many).
________________________________________
6. Advantages of Relational Databases
1.	Data Integrity: Ensures consistency through constraints like primary and foreign keys.
2.	Scalability: Can handle large datasets efficiently.
3.	Flexibility: Easy to modify structure with DDL commands.
4.	Support for Complex Queries: SQL enables powerful data retrieval operations.
5.	Security: Role-based access control with permissions.
________________________________________
7. Four Types of Data Types Used in Tables
1.	Integer (INT): Stores whole numbers.
2.	Character/String (VARCHAR, TEXT): Stores text or string data.
3.	Date/Time (DATE, DATETIME, TIMESTAMP): Stores date and time values.
4.	Decimal (DECIMAL, FLOAT): Stores floating-point numbers or precise decimal values.
________________________________________
8. Purpose of a Database Management System (DBMS)
The primary purpose of a DBMS is to provide an efficient, secure, and reliable way to manage and store data.
Key Objectives:
1.	Data Storage and Retrieval: Facilitate fast and accurate data access.
2.	Data Integrity: Ensure accuracy and consistency of data.
3.	Data Security: Restrict unauthorized access.
4.	Concurrency: Enable multiple users to access data simultaneously without conflicts.
5.	Backup and Recovery: Prevent data loss through regular backups and recovery mechanisms.
6.	Data Abstraction: Hide the complexity of data storage from users.

