1. State and Explain the components of a DBMS(Database Management System)
* Components of a DBMS:
 * 1. **Database Engine**: The core service for accessing and processing data. It provides mechanisms for data storage, retrieval, and update.
 * 2. **Database Schema**: Defines the logical structure of the database, including tables, views, indexes, and relationships.
 * 3. **Query Processor**: Interprets and executes database queries written in SQL. It optimizes query performance and ensures efficient data retrieval.
 * 4. **Transaction Management**: Ensures that all database transactions are processed reliably and adhere to ACID (Atomicity, Consistency, Isolation, Durability) properties.
 * 5. **Storage Management**: Manages the physical storage of data on disk, including data files, indexes, and logs.
 * 6. **Database Manager**: Provides tools for database administration, including backup, recovery, and performance monitoring.
 * 7. **User Interface**: Allows users to interact with the database, typically through a graphical user interface (GUI) or command-line interface (CLI).
 * 8. **Security Management**: Controls access to the database, ensuring that only authorized users can perform specific actions.
 * 9. **Data Integrity Management**: Ensures the accuracy and consistency of data within the database through constraints and validation rules.

2. What is a relational database? Give 4 examples.

A relational database is a type of database that stores and provides access to data points that are related to one another. Data in a relational database is organized into tables (also known as relations), which consist of rows and columns. Each row represents a unique record, and each column represents a field within the record. Relational databases use Structured Query Language (SQL) for defining and manipulating data.

Examples of relational databases:
1. **MySQL**
2. **PostgreSQL**
3. **Oracle Database**
4. **Microsoft SQL Server**



3. State and Explain three classifications of SQL?

* **Data Definition Language (DDL)**: DDL statements are used to define and manage database structures such as tables, indexes, and views. Common DDL commands include:
    * `CREATE`: Creates a new table, view, or other database object.
    * `ALTER`: Modifies an existing database object.
    * `DROP`: Deletes an existing database object.

* **Data Manipulation Language (DML)**: DML statements are used to retrieve, insert, update, and delete data within database tables. Common DML commands include:
    * `SELECT`: Retrieves data from one or more tables.
    * `INSERT`: Adds new rows of data to a table.
    * `UPDATE`: Modifies existing data within a table.
    * `DELETE`: Removes rows of data from a table.

* **Data Control Language (DCL)**: DCL statements are used to control access to data within the database. Common DCL commands include:
    * `GRANT`: Gives a user permission to perform specific actions on database objects.
    * `REVOKE`: Removes a user's permission to perform specific actions on database objects.
    
4. What is the difference between a Primary Key and a Foreign Key?

    * **Primary Key**: A primary key is a unique identifier for a record in a database table. It ensures that each record can be uniquely identified and prevents duplicate records. A primary key must contain unique values and cannot contain NULL values.

    * **Foreign Key**: A foreign key is a field (or a collection of fields) in one table that uniquely identifies a row of another table. The foreign key establishes a relationship between the two tables, enforcing referential integrity. It ensures that the value in the foreign key column corresponds to a valid primary key value in the related table.

5. What is an Entity-Relationship Diagram?

    An Entity-Relationship Diagram (ERD) is a visual representation of the entities within a system and the relationships between those entities. It is used in database design to illustrate the logical structure of databases. ERDs help in understanding the data requirements and the relationships among data entities, making it easier to design and implement a database.

    Components of an ERD:
    * **Entities**: Objects or concepts that can have data stored about them. Examples include `Customer`, `Order`, and `Product`.
    * **Attributes**: Properties or details about an entity. For example, a `Customer` entity might have attributes such as `CustomerID`, `Name`, and `Email`.
    * **Relationships**: Connections between entities that show how they interact with each other. Relationships can be one-to-one, one-to-many, or many-to-many.

    ERDs use symbols like rectangles to represent entities, ovals for attributes, and diamonds for relationships. Lines are used to connect these symbols, indicating the associations between them.

6. What are the advantages of relational databases?

    * **Data Integrity**: Relational databases enforce data integrity through constraints and validation rules, ensuring that the data is accurate and consistent.
    * **Flexibility**: They allow for complex queries and data manipulation using SQL, making it easy to retrieve and update data.
    * **Scalability**: Relational databases can handle large amounts of data and can be scaled horizontally or vertically to accommodate growth.
    * **Security**: They provide robust security features, including user authentication, authorization, and encryption, to protect sensitive data.
    * **Data Relationships**: Relational databases efficiently manage relationships between data points, making it easy to link and retrieve related data across different tables.
    * **Standardization**: SQL is a standardized language for managing relational databases, ensuring compatibility and interoperability across different systems and platforms.
    * **Transaction Management**: They support ACID properties (Atomicity, Consistency, Isolation, Durability), ensuring reliable and secure transaction processing.

7. State four types of data type used to store data in tables?

    * **Integer**: Used to store whole numbers without decimal points. Examples include `INT`, `SMALLINT`, and `BIGINT`.
    * **Character/String**: Used to store text data. Examples include `CHAR`, `VARCHAR`, and `TEXT`.
    * **Date/Time**: Used to store date and time values. Examples include `DATE`, `TIME`, and `DATETIME`.
    * **Boolean**: Used to store binary values, typically `TRUE` or `FALSE`. The `BOOLEAN` data type is commonly used for this purpose.

8. What is the purpose of a database management system (DBMS)?

    A Database Management System (DBMS) serves several key purposes:

    * **Data Storage and Retrieval**: It provides a systematic way to store, manage, and retrieve data efficiently.
    * **Data Integrity**: Ensures the accuracy and consistency of data through constraints and validation rules.
    * **Data Security**: Controls access to data, ensuring that only authorized users can perform specific actions.
    * **Data Administration**: Offers tools for database administration, including backup, recovery, and performance monitoring.
    * **Transaction Management**: Manages database transactions to ensure they are processed reliably and adhere to ACID properties.
    * **Concurrency Control**: Manages concurrent data access to ensure data consistency and integrity.
    * **Data Abstraction**: Provides a level of abstraction between the physical data storage and the logical data model, making it easier for users to interact with the data.

    Overall, a DBMS simplifies the process of managing large amounts of data, ensuring that it is stored securely, retrieved efficiently, and maintained consistently.
