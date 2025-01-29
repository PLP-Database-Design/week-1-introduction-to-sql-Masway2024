# Components of a Database Management System (DBMS)
A **DBMS** consists of several key components:

1. **Hardware** – Physical devices such as servers, storage, and networking equipment.
2. **Software** – The DBMS software like MySQL, PostgreSQL, or Oracle DB.
3. **Data** – The actual information stored in structured tables and relationships.
4. **Query Processor** – Interprets and executes SQL queries.
5. **Transaction Management** – Ensures ACID properties (Atomicity, Consistency, Isolation, Durability).
6. **Database Engine** – Manages data storage, retrieval, and indexing.
7. **Users** – People interacting with the database, including administrators and developers.

---

# What is a Relational Database?
A **relational database** organizes data into **tables (relations)** with predefined relationships using **keys** (primary and foreign keys). Each table consists of:

- **Rows (records or tuples)** – Store individual data entries.
- **Columns (attributes)** – Define the type of data stored.

## **Examples of Relational Databases:**
1. **MySQL**
2. **PostgreSQL**
3. **Microsoft SQL Server**
4. **Oracle Database**

---

# Three Classifications of SQL
SQL is categorized into different types based on functionality:

## **1. DDL (Data Definition Language)**
Defines and manages the database schema.
- Commands: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`

## **2. DML (Data Manipulation Language)**
Handles the manipulation of data in the database.
- Commands: `INSERT`, `UPDATE`, `DELETE`, `SELECT`

## **3. DCL (Data Control Language)**
Controls user access and permissions in the database.
- Commands: `GRANT`, `REVOKE`

---

# Difference Between Primary Key and Foreign Key

| Feature       | Primary Key          | Foreign Key          |
|--------------|----------------------|----------------------|
| **Definition** | Unique identifier for a record | References a primary key in another table |
| **Uniqueness** | Must be unique for each row | Can have duplicate values |
| **Nullability** | Cannot be `NULL` | Can be `NULL` |
| **Relationship** | Defines a unique record | Establishes table relationships |
| **Example** | `Student_ID` in Students table | `Student_ID` in Enrollments table |

---

# What is an Entity-Relationship Diagram (ERD)?
An **Entity-Relationship Diagram (ERD)** is a visual representation of a database schema that shows:
- **Entities** (tables)
- **Attributes** (columns)
- **Relationships** (connections between tables)

ERDs help design and understand database structures before implementation.

---

# Advantages of Relational Databases
1. **Data Integrity and Consistency** – Enforces accuracy using constraints.
2. **Data Security** – Implements authentication and authorization.
3. **Scalability** – Efficiently handles increasing data.
4. **Easy Querying with SQL** – Provides powerful querying capabilities.
5. **Reduces Data Redundancy** – Uses normalization to avoid duplication.
6. **Concurrency Control** – Supports multiple users simultaneously.

---

# Four Types of Data Types in Tables
1. **Integer (`INT`, `BIGINT`, `SMALLINT`)** – Stores whole numbers.
2. **String (`VARCHAR`, `TEXT`, `CHAR`)** – Stores textual data.
3. **Date/Time (`DATE`, `DATETIME`, `TIMESTAMP`)** – Stores date and time values.
4. **Boolean (`BOOLEAN`)** – Stores `TRUE` or `FALSE` values.

---

# Purpose of a Database Management System (DBMS)
A **DBMS** is used to:
- Store, retrieve, and manage data efficiently.
- Ensure data security and integrity.
- Enable concurrent access by multiple users.
- Provide backup and recovery features.
- Support structured query processing.
