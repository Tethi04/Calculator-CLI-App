Task 1: Theory Questions & Answers
1. What is normalization?
Normalization is the process of organizing data in a database to reduce data redundancy and improve data integrity. It involves dividing large tables into smaller, related tables and defining relationships between them to ensure that data is stored logically and efficiently.
2. Explain primary vs foreign key.
Primary Key: A unique identifier for a record in a table. It cannot contain NULL values, and there can be only one primary key per table (e.g., Student_ID).
Foreign Key: A field in one table that links to the Primary Key of another table. It establishes a relationship between the two tables (e.g., Department_ID in a specific Student table linking to the Departments table).
3. What are constraints?
Constraints are rules applied to table columns to enforce data validity and integrity. Common constraints include:
NOT NULL (prevents null values)
UNIQUE (ensures all values are different)
PRIMARY KEY (uniquely identifies rows)
FOREIGN KEY (ensures referential integrity)
CHECK (ensures values satisfy a specific condition)
4. What is a surrogate key?
A surrogate key is an artificial, system-generated unique identifier for a record. It has no business meaning and is strictly used to uniquely identify a row (e.g., an auto-incrementing integer like ID = 1, 2, 3...).
5. How do you avoid data redundancy?
Data redundancy is avoided primarily through normalization. By organizing data into separate, related tables and using Foreign Keys to reference data rather than duplicating it, we ensure that a piece of information is stored in only one place.
6. What is an ER diagram?
An ER (Entity-Relationship) diagram is a visual representation of the database structure. It shows:
Entities: Objects or concepts (e.g., Student, Course).
Attributes: Properties of entities (e.g., Name, Grade).
Relationships: How entities interact with each other (e.g., Student enrolls in Course).
7. What are the types of relationships in DBMS?
One-to-One (1:1): One record in Table A relates to one record in Table B.
One-to-Many (1:N): One record in Table A relates to multiple records in Table B.
Many-to-Many (M:N): Multiple records in Table A relate to multiple records in Table B.
8. Explain the purpose of AUTO_INCREMENT.
AUTO_INCREMENT is a feature (common in MySQL) that automatically generates a unique number for a new record when it is inserted into a table. It is commonly used to generate Primary Keys without manual input.
9. What is the default storage engine in MySQL?
The default storage engine in modern MySQL versions (5.5 and later) is InnoDB. It supports transactions, row-level locking, and foreign keys.
10. What is a composite key?
A composite key is a Primary Key that consists of two or more columns. While a single column might not be unique, the combination of these columns is unique for every record (e.g., Order_ID + Product_ID in an OrderDetails table).
