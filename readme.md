1. Components of a DBMS (Database Management System)
A DBMS is a software system that manages databases and allows users to interact with data. The main components of a DBMS include:

Database Engine: This is the core service of the DBMS. It handles tasks like data storage, retrieval, and manipulation.

Database Schema: The schema defines the structure of the database, including tables, relationships, constraints, and other elements.

Query Processor: This component translates user queries (usually written in SQL) into executable operations that the database engine can perform.

Transaction Management: It ensures that transactions are processed reliably and adheres to ACID properties (Atomicity, Consistency, Isolation, Durability).

Data Dictionary: A collection of metadata that stores information about the structure of the database (e.g., table names, column types, constraints).

User Interface: Provides users with a way to interact with the DBMS, either through command-line interfaces, graphical user interfaces (GUI), or web-based interfaces.

Security Management: Controls access to the database, ensuring that only authorized users can view or manipulate data.

2. What is a Relational Database? Give 4 Examples
A relational database is a type of database that stores data in tables (also called relations), with rows representing records and columns representing attributes. It uses Structured Query Language (SQL) for data manipulation and supports relationships between different tables.

Examples of Relational Databases:
MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database
3. Three Classifications of SQL
SQL can be classified into three main categories based on the operations performed:

Data Query Language (DQL): Deals with retrieving data from the database.

Example: SELECT
Data Definition Language (DDL): Deals with defining the structure of database objects like tables, indexes, and views.

Examples: CREATE, ALTER, DROP
Data Manipulation Language (DML): Involves manipulating the data in the database (insert, update, delete).

Examples: INSERT, UPDATE, DELETE
Data Control Language (DCL): Deals with the permissions and access control of the database.

Examples: GRANT, REVOKE
4. Difference Between Primary Key and Foreign Key
Primary Key:

A primary key uniquely identifies each record in a table. It cannot contain NULL values and must be unique for every row.
Example: In a Customers table, CustomerID can be the primary key.
Foreign Key:

A foreign key is a field in one table that links to the primary key in another table. It establishes a relationship between two tables.
Example: In an Orders table, CustomerID can be a foreign key that references the primary key CustomerID in the Customers table.
5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities (tables) in a database and their relationships to each other. It helps in designing the database structure and shows how tables are interconnected.

Entities: Represented by rectangles (usually tables).
Relationships: Represented by diamonds, showing how entities are related (e.g., one-to-many, many-to-many).
Attributes: Represented by ovals, showing properties of entities (e.g., name, age).
6. Advantages of Relational Databases
Data Integrity: Relational databases support constraints like primary keys, foreign keys, and unique constraints, ensuring data integrity.

Flexibility: Tables can be added or altered with ease, and queries can combine data from multiple tables.

Scalability: Relational databases can efficiently handle large amounts of data and support complex queries.

Data Security: Permissions and access control can be implemented, ensuring only authorized users can access or modify certain data.

ACID Compliance: Relational databases provide transaction management with ACID properties, ensuring reliable data processing.

7. Four Types of Data Types Used to Store Data in Tables
Integer: Stores whole numbers. Example: INT, BIGINT.
Varchar: Stores variable-length text strings. Example: VARCHAR(255).
Date/Time: Stores date and time values. Example: DATE, TIME, DATETIME.
Boolean: Stores TRUE or FALSE values. Example: BOOLEAN.
8. Purpose of a Database Management System (DBMS)
The purpose of a DBMS is to provide a systematic and efficient way to manage, store, retrieve, and manipulate data. It offers the following benefits:

Data Management: Helps in organizing and managing large amounts of data efficiently.

Data Security: Controls who has access to the data and ensures data integrity.

Data Consistency: Ensures that data is accurate and consistent across the database.

Ease of Access: Simplifies data retrieval through structured queries (SQL).

Backup and Recovery: Ensures that data is backed up and can be restored in case of failure.