Q: What is an entity in the context of databases?
A: An item of interest about which information is stored.

---

Q: What is a relational database?
A: A database that recognises the differences between entities by creating different tables for each entity.

---

Q: What is a flat file database?
A: A database that consists of a single file, typically based around a single entity and its attributes.

---

Q: How is a flat file typically represented in notation?
A: Entity(Attribute1, Attribute2, Attribute3 ...)

---

Q: What is a primary key?
A: A unique identifier for each record in a database table.

---

Q: How is a primary key typically denoted in database notation?
A: By underlining it.

---

Q: What term describes a unique identifier for each record in a database table?
A: Primary key.

---

Q: What is a foreign key?
A: An attribute that links two tables together, existing as a primary key in one table and acting as a foreign key in another.

---

Q: How is a foreign key typically denoted in database notation?
A: Using an asterisk.

---

Q: What term describes an attribute that links two tables together, being a primary key in one table and a foreign key in another?
A: Foreign key.

---

Q: What is a secondary key?
A: An attribute that allows a database to be searched quickly, often by creating a secondary index on a memorable attribute like a surname.

---

Q: Why are secondary keys used in databases?
A: To make it easier and faster to order and search for specific records using memorable attributes, since primary keys are rarely remembered by users.

---

Q: What is a one-to-one relationship in entity relationship modelling?
A: A relationship where each entity can only be linked to one other entity.

---

Q: How is a one-to-one relationship represented in an entity relationship diagram?
A: Using a single line connecting two entities.

---

Q: What is a one-to-many relationship in entity relationship modelling?
A: A relationship where one table can be associated with many other tables.

---

Q: How is a one-to-many relationship represented in an entity relationship diagram?
A: Using a branch on one side of the connecting line.

---

Q: What is a many-to-many relationship in entity relationship modelling?
A: A relationship where one entity can be associated with many other entities, and vice versa.

---

Q: How is a many-to-many relationship represented in an entity relationship diagram?
A: Using branches on both sides of the connecting line.

---

Q: What is normalisation in database design?
A: The process of coming up with the best possible layout for a relational database.

---

Q: What are the main goals of normalisation?
A: The goals are eliminating redundancy, ensuring consistent data throughout linked tables, allowing records to be added and removed without issues, and enabling complex queries to be carried out.

---

Q: What is the requirement for a database to be in First Normal Form?
A: There must be no attribute that contains more than a single value.

---

Q: What is the requirement for a database to be in Second Normal Form?
A: It must be in First Normal Form and have no partial dependencies, meaning no attributes can depend on part of a composite key.

---

Q: What is the requirement for a database to be in Third Normal Form?
A: It must be in Second Normal Form and contain no non-key dependencies, meaning every attribute depends only on the primary key and nothing else.

---

Q: What does it mean for a database to have no partial dependencies?
A: No attributes can depend on part of a composite key, which is a requirement for Second Normal Form.

---

Q: What does it mean for a database to have no non-key dependencies?
A: Every attribute depends only on the value of the primary key and nothing else, which is a requirement for Third Normal Form.

---

Q: What is indexing in a database?
A: A method used to store the position of each record ordered by a certain attribute, allowing data to be looked up and accessed quickly.

---

Q: Which key is automatically indexed in a relational database?
A: The primary key.

---

Q: Why are secondary keys indexed in a database?
A: To make the table easier and faster to search through on particular attributes that users are more likely to query than the primary key.

---

Q: What is MICR and what is it used for?
A: Magnetic Ink Character Recognition, used by banks to scan cheques by reading details printed in special magnetic ink.

---

Q: What is OMR and what is it used for?
A: Optical Mark Recognition, used for capturing data from multiple choice questions on a test.

---

Q: What is OCR and what is it used for?
A: Optical Character Recognition, used for capturing data from forms.

---

Q: What is the purpose of selecting data during data preprocessing?
A: To reduce the volume of input by only selecting data that fits certain criteria.

---

Q: What is EDI in the context of data exchange?
A: Electronic Data Interchange, a method of transferring data from one computer to another without requiring human interaction.

---

Q: What does SQL stand for?
A: Structured Query Language.

---

Q: What type of language is SQL?
A: A declarative language used to manipulate databases.

---

Q: What is the purpose of the SELECT statement in SQL?
A: To collect fields from a given table.

---

Q: What is the purpose of the FROM statement in SQL?
A: To specify which table or tables the information will come from.

---

Q: What is the purpose of the WHERE statement in SQL?
A: To specify the search criteria for a query.

---

Q: What is the default ordering of results when using the ORDER BY clause in SQL?
A: Ascending order.

---

Q: How do you specify descending order in an SQL ORDER BY clause?
A: By adding DESC to the end of the statement.

---

Q: What is the purpose of the JOIN clause in SQL?
A: To combine rows from multiple tables based on a common field between them.

---

Q: What is the purpose of the CREATE statement in SQL?
A: To make new databases or tables.

---

Q: What three details must be specified for each attribute when creating a table in SQL?
A: You must specify whether it is the primary key, its data type, and whether it must be filled in using NOT NULL.

---

Q: What SQL data type represents a string of fixed length n?
A: CHAR(n)

---

Q: What SQL data type represents a string of variable length with an upper limit n?
A: VARCHAR(n)

---

Q: What SQL data type represents TRUE or FALSE values?
A: BOOLEAN

---

Q: What SQL data type represents a number with a floating decimal point?
A: FLOAT

---

Q: What SQL data type represents a monetary amount?
A: CURRENCY

---

Q: What is the purpose of the ALTER statement in SQL?
A: To add, delete, or modify columns in a table.

---

Q: What SQL command is used to add a column to an existing table?
A: ALTER TABLE TableName ADD AttributeX DataType

---

Q: What SQL command is used to delete a column from an existing table?
A: ALTER TABLE TableName DROP COLUMN AttributeX

---

Q: What SQL command is used to modify the data type of an existing column?
A: ALTER TABLE TableName MODIFY COLUMN AttributeX NewDataType

---

Q: What is the purpose of the INSERT INTO statement in SQL?
A: To insert a new record into a database table.

---

Q: What is the purpose of the UPDATE statement in SQL?
A: To update an existing record in a database table.

---

Q: What is the purpose of the DELETE statement in SQL?
A: To delete a record from a database table.

---

Q: What is referential integrity?
A: The process of ensuring consistency so that information is not removed if it is required elsewhere in a linked database.

---

Q: What happens if you try to delete a table that is required by another linked table?
A: The deletion is prevented to maintain referential integrity.

---

Q: What is a transaction in database processing?
A: A single operation, or a collection of operations, executed on data.

---

Q: What does the acronym ACID stand for in transaction processing?
A: Atomicity, Consistency, Isolation, Durability.

---

Q: What does Atomicity mean in the context of ACID properties?
A: A transaction must be processed in its entirety or not at all.

---

Q: What does Consistency mean in the context of ACID properties?
A: A transaction must maintain the referential integrity rules between linked tables.

---

Q: What does Isolation mean in the context of ACID properties?
A: Simultaneous executions of transactions should lead to the same result as if they were executed one after the other.

---

Q: What does Durability mean in the context of ACID properties?
A: Once a transaction has been executed, it will remain so regardless of the circumstances, such as a power cut.

---

Q: What is record locking?
A: The process of preventing simultaneous access to records in a database to prevent inconsistencies or a loss of updates.

---

Q: What is a deadlock in the context of record locking?
A: A situation where two or more users are waiting for each other to release locked records, resulting in no progress.

---

Q: What is data redundancy in the context of data protection?
A: The process of having one or more copies of data in physically different locations to ensure recovery if one copy is damaged.

---

Q: Why is data redundancy important for companies?
A: It ensures that important information can be recovered if one copy is damaged or lost, as other copies remain unaffected in different locations.