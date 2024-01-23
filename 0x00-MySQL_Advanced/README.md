How to create tables with constraints
---------------------------------------------------------------

SQL is short for Structured Query Language, is used to store, manipulate, and retrieve data from a database. It is an ANSI (American National Standards Institute) standard language. Several RDMS (Relational Database Management System) use SQL to allow users to work with data. 

Since you work with data using SQL, it is essential to handle and describe it. That’s where constraints in SQL come into the picture.

-------------------------------------------------------

SQL constraints are rules that you can imply on the data in a table. It allows you to restrict only specific data that meets the regulations to go to a table. To put it simply, only if the data meets the constraint’s rules, the insert operation will be successful, or else it will be aborted.

Constraints in SQL helps to maintain the accuracy, integrity, and reliability of a table’s data. It can create them at a column or table level. If you declare constraints at the column level, it will apply them to a single column. On the other hand, if you declare them at the table level, it will implement them in more than one column. You can create constraints in SQL while creating a table using the CREATE TABLE command or later using the ALTER TABLE command. If you make a constraint with the ALTER TABLE command, the creation will only be successful if all the existing data meets the constraint rules.


-------------------------------------------------------------------------------------

How to Create Constraints in SQL
-------------------------------------------------------

As mentioned, you can create constraints in SQL using the CREATE TABLE command while creating a new table or ALTER TABLE command while altering an existing table. The basic syntax of creating an SQL constraint using the CREATE TABLE command is:

CREATE TABLE table_name(

column_name1 data_type(size) constraint_name,

column_name2 data_type(size) constraint_name,

….

);

-------------------------------------------------------
In the above syntax:

table_name: Name of the table you want to create
column_name: Name of the column you want to create
data_type: Data type of the value you want to add to the column
size: Maximum size (length) of the column
constraint_name: Name of the constraint you want to create and implement
You can also create a constraint in SQL using the ALTER TABLE command through the following syntax:

ALTER TABLE table_name ALTER COLUMN column_name data_type(size) constraint_name

--------------------------------------------------


Types of Constraints in SQL
-----------------------------------------

Not Null Constraint in SQL
--------------------------------------

By default, SQL tables can accept null values. But if you want to restrict columns from taking null values, you can use the NOT NULL constraint in SQL. Using this constraint will simply prohibit anyone from inserting a new row in the table while keeping the field for this column null. This is useful in scenarios where you need the user to put input for something necessarily. For instance, if you want to check age restriction, the user must input age. Thus, you can use the NOT NULL constraint to the age column.

---------------------------------------------

UNIQUE Constraint in SQL
---------------------------------------

As the name gives out, the UNIQUE constraint prohibits any duplicate values in a column. If a column has a UNIQUE constraint, it will not allow any similar row entry for that field. You can declare more than one column as UNIQUE in a table. 

----------------------------------

PRIMARY KEY Constraint in SQL
---------------------------------

The PRIMARY KEY constraint is a combination of both NOT NULL and UNIQUE constraints. This means that when you define a column with PRIMARY KEY, it will not accept any null or duplicate values.

-------------------------------

FOREIGN KEY Constraint in SQL
-----------------------------------------------

The FOREIGN KEY constraint in SQL is usually used to build relationships between tables in a database. It handles foreign affairs by connecting to the PRIMARY KEY values of another table. But to create this connection, you need to pass a command, which is:

FOREIGN KEY (column_name_first_table) REFERENCES (column_name_second_table)

------------------------------------------------------

CHECK Constraint in SQL
-------------------------------

The CHECK constraint allows you to specify a condition that needs to be met to insert data into a table successfully. A simple example will be to create a table for the voting list. It is evident that a person needs to be above 18 years of age to qualify for voting. Thus, with the CHECK constraint’s help, the administrator will only enter the list of people above 18 years of age.

--------------------

DEFAULT Constraint in SQL
---------------------------------

The DEFAULT constraint in SQL is used to assign a default value to the left empty fields. Thus, if you neither want a user to enter empty fields nor want to implement the NOT NULL constraint, DEFAULT constraint can come in handy. It is also helpful to provide a default value to a field if set to NOT NULL. This will prevent the constraint error, as the field will be given the default value and will not remain NULL.

---------------------------------------------

CREATE INDEX Constraint in SQL
------------------------------------------

The CREATE INDEX constraint in SQL helps in retrieving the results more quickly. It is like a book’s index. Like the book’s index helps us find a chapter soon, the table’s index allows the system to retrieve results quickly. The CREATE INDEX constraint is not visible or of any use to the user; it is only helpful to the backend or the system. The syntax for creating an index is:

CREATE INDEX index_name

ON table_name (col1, col2, col3, ...)

--------------------------------------------
