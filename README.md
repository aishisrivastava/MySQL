# MySQL
My SQL learning from basic to advanced.

Structured Query Language is a standard database language used to create, delete, maintain, update, retrieve data from relational databaseslike MySQL, Oracle, SQL Server, PostgreSQL.

1. CREATING DATABASE:
   CREATE command in SQL is used to define new databases and tables. A database acts as container that holds different objects like tables, views, procedures, while a table stores data in the form of rows and columns.
   No spaces between database names (underscore can be used).

2. VERIFYING DATABASE CREATION:
   To confirm that a new database has been created: SHOW DATABASES;

3. SWITCHING TO A DATABASE: Once the database is created, we can switch to that database to begin adding tables, inserting data and performing queries. To switch to new database we use the USE command.allows you to work within the scope of the newly created database.

4. DELETING A DATABASE: permanently deletes the database.

5. CREATING TABLES: Column names, Data Types, Constraints are defined.
   CREATE TABLE table_name (
    column1 datatype constraint,
    column2 datatype constraint,
    ...

);   

6. VERIFYING TABLE CREATION: display all the tables created inside the database.

SQL CREATE TABLE

Creating a table is one of the first and most important steps in building a database. The CREATE TABLE command in SQL defines how your data will be stored, including the table name, column names, data types, and rules (constraints) such as NOT NULL, PRIMARY KEY, and CHECK.

Defines a new table in the database.
Specifies columns, their data types, and sizes.
Applies constraints such as NOT NULL, PRIMARY KEY, and CHECK.
Ensures accuracy, consistency, and organized data storage.

Inserting Data into the Table: After creating the table, you can use INSERT INTO command to add data into it.

