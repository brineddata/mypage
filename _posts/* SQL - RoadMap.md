# Database and SQL Roadmap:

## Table of Contents:
- [Database Basics](https://www.databasestar.com/sql-roadmap/#Database_Basics "Database Basics")
- [Basic Select Query](https://www.databasestar.com/sql-roadmap/#Basic_Select_Query "Basic Select Query")
- [Modifying Data](https://www.databasestar.com/sql-roadmap/#Modifying_Data "Modifying Data")
- [Working with Tables](https://www.databasestar.com/sql-roadmap/#Working_with_Tables "Working with Tables")
- [Improving Your Queries](https://www.databasestar.com/sql-roadmap/#Improving_Your_Queries "Improving Your Queries")
- [Database Design](https://www.databasestar.com/sql-roadmap/#Database_Design "Database Design")
- [Intermediate SQL](https://www.databasestar.com/sql-roadmap/#Intermediate_SQL "Intermediate SQL")
- [Advanced SQL](https://www.databasestar.com/sql-roadmap/#Advanced_SQL "Advanced SQL")
- [Procedural Language](https://www.databasestar.com/sql-roadmap/#Procedural_Language "Procedural Language")
- [Database Objects](https://www.databasestar.com/sql-roadmap/#Database_Objects "Database Objects")
- [Database Administration](https://www.databasestar.com/sql-roadmap/#Database_Administration "Database Administration")

## Database Basics

### What is a database?

The first step is to understand what a database is: a tool that’s used to store and manage data.

Learn more: [Wikipedia](https://en.wikipedia.org/wiki/Database), [JavaTPoint](https://www.javatpoint.com/what-is-database)

### What is SQL?

SQL stands for Structured Query Language and is the language used to interact with databases.

Learn more: [Wikipedia](https://en.wikipedia.org/wiki/SQL), [Learn To Code With Me](https://learntocodewith.me/posts/sql-guide/), [SQL vs MySQL vs SQL Server: What’s the Difference?](https://www.databasestar.com/sql-vs-mysql/)

## Basic Select Query

### SELECT Statement

Learn how to use the Select keyword to view data, including all columns or only some columns.

Learn more: [SQL SELECT Statement](https://www.databasestar.com/sql-select-statement/), DUAL Table in Oracle

### WHERE Clause

The WHERE clause lets you filter data out of your Select query, and also works with Update and Delete statements.

Learn more: [SQL WHERE Clause](https://www.databasestar.com/sql-where/)

### ORDER BY Clause

This clause allows you to order the results of your Select query,

Learn more: [SQL ORDER BY](https://www.databasestar.com/sql-order-by/)

### Aggregate Functions

Aggregate functions allow you to combine multiple rows into one, such as counting records or adding numbers.

Learn more: [SQL Aggregate Functions](https://www.databasestar.com/sql-aggregate-functions/)

### GROUP BY Clause

The GROUP BY clause allows you to group data by values in a column and use aggregate functions.

Learn more: [SQL Group By Clause](https://www.databasestar.com/sql-group-by/)

### HAVING Clause

The HAVING clause allows you to filter data after a group has been applied.

Learn More: [SQL Having Clause](https://www.databasestar.com/sql-group-by/), [Difference Between Where and Having](https://www.databasestar.com/difference-between-where-and-having-clause/)

### Joins

A join is where you combine data from two or more tables into one query.

Learn more: [SQL Joins](https://www.databasestar.com/sql-joins/)

## Modifying Data

### UPDATE Statement

The Update statement allows you to make changes to data in a table.

Learn more: [SQL Update Statement](https://www.databasestar.com/sql-update/)

### DELETE Statement

The Delete statement allows you to remove records from a table.

Learn more: [SQL Delete Statement](https://www.databasestar.com/sql-delete/)

### INSERT Statement

The Insert statement allows you to add new records to a table.

Learn more: [SQL Insert Statement](https://www.databasestar.com/sql-insert-into/), [Inserting Multiple Rows](https://www.databasestar.com/sql-insert-multiple-rows/)

### Truncate Table

The Truncate Table statement lets you remove all data from a table.

Learn more: [SQL Truncate Table](https://www.databasestar.com/sql-truncate-table/)

## Working with Tables

### Create Table

Create new tables in your database with the Create Table statement.

Learn more: [SQL Create Table](https://www.databasestar.com/sql-create-table/), [Create a Database in SQL](https://www.databasestar.com/sql-create-database/)

### Alter Table

Make changes to your table, such as adding or removing columns, with the Alter Table statement.

Learn more: [SQL Alter Table](https://www.databasestar.com/sql-alter-table/), [SQL Add Column](https://www.databasestar.com/sql-add-column/),

### Drop Table

Remove a table from your database with the Drop Table command.

Learn more: [SQL Drop Table](https://www.databasestar.com/drop-table/)

### Data Types

There are many data types available in each database, each of which have their pros and cons.

Learn more: [SQL Data Types](https://www.databasestar.com/sql-data-types/), [SQL INT Data Types](https://www.databasestar.com/sql-int-data-types/)

## Improving Your Queries

### Indexes

Indexes are objects that help the performance of your queries.

Learn more: [SQL Indexes](https://www.databasestar.com/sql-indexes/)

### Primary Keys

A primary key is a way of uniquely identifying a record in a table.

Learn more: [Database Keys](https://www.databasestar.com/database-keys/)

### Foreign Keys

A foreign key is how a record in one table is related to a record in another table.

Learn more: [Database Keys](https://www.databasestar.com/database-keys/)

### Constraints

Constraints are rules that can be added to tables to improve the quality of data.

Learn more: [Constraints](https://www.databasestar.com/sql-constraints/)

### Column and Table Aliases

Aliases are names given to tables or columns in your query.

Learn more: [Aliases in SQL](https://www.databasestar.com/sql-alias/)

## Database Design

### Normalisation (First to Third)

Normalisation is the process of transforming a database design using a set of rules to improve its efficiency and quality.

Learn more: [Database Normalisation: A Step-By-Step Guide](https://www.databasestar.com/database-normalization/)

### ERDs

ERD stands for Entity Relationship Diagram and it is a way that database designs are shown and created.

Learn more: [A Guide to the ERD](https://www.databasestar.com/entity-relationship-diagram/)

### Further Normal Forms (3.5 to 5)

There are more steps, or normal forms, that occur after Third Normal Form. They aren’t used very often but can be handy to know.

Learn more:

- [BCNF (Boyce-Codd Normal Form), or 3.5 NF](https://en.wikipedia.org/wiki/Boyce%E2%80%93Codd_normal_form)
- [Fourth Normal Form](https://www.studytonight.com/dbms/fourth-normal-form.php#)
- [Fifth Normal Form](https://en.wikipedia.org/wiki/Fifth_normal_form)

### Data Warehouse

A data warehouse is a type of database that focuses on fast reading of data and is often used to generate reports.

Learn more: [Ultimate Guide to Data Warehouses](https://www.databasestar.com/data-warehouse/)

### Auto-Increment

Auto-increment is a feature that lets you automatically specify a value for a column to ensure it is unique.

Learn more: [Auto-Increment in Different Databases](https://www.databasestar.com/sql-auto-increment/)

## Intermediate SQL

### Temporary Tables

A temporary table is an object that lets you store results for easier and faster processing of a larger query.

Learn more: [SQL Temp Tables](https://www.databasestar.com/sql-temp-table/)

### Transactions

A transaction is a single unit of work that can be used to improve data integrity in your database.

Learn more: [SQL Transactions](https://www.databasestar.com/sql-transactions/)

### Using Functions

A function is a predefined set of code that can be used in your SQL statements.

Learn more:

- [Oracle SQL Functions](https://www.databasestar.com/oracle-sql-functions/)
- [SQL Server Functions](https://docs.microsoft.com/en-us/sql/t-sql/functions/functions?view=sql-server-ver15)
- [MySQL Functions](https://dev.mysql.com/doc/refman/8.0/en/functions.html)
- [PostgreSQL Functions](https://www.postgresql.org/docs/current/functions.html)
- [Analytic Functions](https://www.databasestar.com/sql-window-functions/)
- [Aggregate Functions](https://www.databasestar.com/sql-aggregate-functions/)

### Types of Commands

SQL statements fall into several different categories of commands, such as DML, DDL, and TCL.

Learn more: [SQL Commands](https://www.databasestar.com/sql-commands/)

### Operators (IN, EXISTS)

There are several keywords that let you filter your data in other ways, such as IN and EXISTS.

Learn more: [SQL Operators](https://www.databasestar.com/sql-operators/)

### Subqueries

A subquery is a query inside another query. They can help you solve problems that can’t otherwise be solved in a single query.

Learn more: [SQL Subqueries](https://www.databasestar.com/sql-subqueries/)

### Bind Variables

A bind variable is a feature that lets you provide the values for a query when it is run, improving performance and security.

Learn more: [Bind Variables in SQL](https://use-the-index-luke.com/sql/where-clause/bind-parameters)

### Limiting Rows

SQL allows you to limit the number of rows returned by your query, and this is done in several ways.

Learn more: [SQL Limit: The Complete Guide to SQL Row Limiting and Top-N Queries](https://www.databasestar.com/sql-limit/)

### CTEs and With Clause

A Common Table Expression uses the With clause and can be used to simplify your queries.

Learn more: [SQL CTE (WITH Clause)](https://www.databasestar.com/sql-cte-with/)

### Set Operators

A set operator, such as Union, allows you to combine two queries into one.

Learn more: [SQL Set Operators](https://www.databasestar.com/sql-set-operators/)

### Execution Plans

Execution plans allow you to see how the database will run your query, and are a helpful step in improving the performance of your query.

Learn more: [Ultimate Guide to Execution Plans](https://www.databasestar.com/sql-execution-plan/)

### Comments on Objects

Databases allow you to add comments to different objects, which can help you and others understand more about them.

Learn more: [SQL Comments](https://www.databasestar.com/sql-comments/)

### Importing Data

There are many ways to import data from external files (e.g. CSV, spreadsheets, log files) into a database.

Learn more:

- [MySQL Workbench Import CSV](https://www.databasestar.com/mysql-workbench-import-csv/)
- [SSMS Import](https://docs.microsoft.com/en-us/sql/integration-services/import-export-data/start-the-sql-server-import-and-export-wizard?view=sql-server-ver15)
- [SQL Developer Import](https://www.thatjeffsmith.com/archive/2012/04/how-to-import-from-excel-to-oracle-with-sql-developer/)

### JSON in SQL

JSON, pronounced like “jason”, stands for JavaScript Object Notation, and is a format for storing data. Recent versions of databases include features for storing JSON data and functions for working with it.

Learn More:

- [JSON in Oracle](https://blogs.oracle.com/sql/how-to-store-query-and-create-json-documents-in-oracle-database)
- [JSON in SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/json/json-data-sql-server?view=sql-server-ver15)
- [JSON in MySQL](https://www.databasestar.com/mysql-json/)
- [JSON in PostgreSQL](https://www.postgresql.org/docs/9.3/functions-json.html)

## Advanced SQL

### Pivot and Unpivot

Pivot and Unpivot are database features that let you transpose row data to columns, to analyse data in a different way. It’s common in Excel but can be done in SQL as well.

Learn More:

- [Oracle PIVOT and UNPIVOT](https://www.databasestar.com/oracle-sql-pivot/)
- [SQL Server Pivot](https://docs.microsoft.com/en-us/sql/t-sql/queries/from-using-pivot-and-unpivot?view=sql-server-ver15)
- [MySQL Pivot](https://codingsight.com/pivot-tables-in-mysql/)
- [PostgreSQL Pivot](https://www.postgresql.org/docs/current/tablefunc.html)
- [Modern SQL Pivot article](https://modern-sql.com/use-case/pivot)

### Regular Expressions

Regular expressions are a programming concept that let you search and match text files based on specific structures.

Learn More:

- [Definition (Wikipedia)](https://en.wikipedia.org/wiki/Regular_expression)
- [RegExr – tool to build regular expressions](https://regexr.com/)
- [Oracle REGEXP Functions](https://www.databasestar.com/oracle-regexp-functions/)
- [SQL Server Regular Expressions](https://docs.microsoft.com/en-us/sql/ssms/scripting/search-text-with-regular-expressions?view=sql-server-ver15)
- [MySQL Regular Expressions](https://dev.mysql.com/doc/refman/8.0/en/regexp.html)
- [PostgreSQL Regular Expressions](https://www.postgresql.org/docs/current/functions-matching.html)

### Isolation Levels

Isolation levels in databases allow you to define how and when data can be accessed in different situations.

Learn more: [SQL Transactions and Isolation Levels](https://www.databasestar.com/sql-transactions/)

### Continuous Integration and Delivery

Continuous Integration (CI) is the concept of regularly runnings tests on your code to ensure it still works. Continuous Delivery (CD) is the ability to always be able to deliver working software.

These techniques can be applied to databases as well.

Learn more: [The Ultimate Guide to Database Version Control, CI/CD, and Deployment](https://www.databasestar.com/database-version-control-deployment/)

### Hierarchical Data in SQL

Hierarchical data is the ability to store multiple levels of data in a single table, such as employees and managers, or categories of products.

Learn more: [Hierarchical Data in SQL: The Ultimate Guide](https://www.databasestar.com/hierarchical-data-sql/)

### Analytic Functions

Analytic functions, or window functions, allow you to perform calculations on sets of rows within a result. They can be powerful and can simplify your queries.

Learn more: [SQL Window Functions: The Ultimate Guide](https://www.databasestar.com/sql-window-functions/)

### Character Sets

A character set is a defined list of characters accepted by computers.

Learn more: [Oracle Characters Sets](https://www.databasestar.com/oracle-character-sets/)

### Merge Command

The Merge command lets you insert or update data in one query based on a condition.

Learn more:

- [Merge: Oracle, SQL Server](https://www.databasestar.com/sql-merge/)
- [MySQL Insert On Duplicate Key](https://dev.mysql.com/doc/refman/8.0/en/insert-on-duplicate.html)
- [PostgreSQL Upsert](https://wiki.postgresql.org/wiki/UPSERT)

### External Tables

An external table is the ability to create a table linked to an external file (e.g. a CSV file).

Learn more:

- [Oracle external tables](https://oracle-base.com/articles/9i/external-tables-9i)
- [SQL Server external tables](https://docs.microsoft.com/en-us/sql/t-sql/statements/create-external-table-transact-sql?view=sql-server-ver15&tabs=dedicated)
- [MySQL external tables](https://dev.mysql.com/doc/refman/8.0/en/innodb-create-table-external.html)
- [PostgreSQL foreign tables](https://www.postgresql.org/docs/10/sql-createforeigntable.html)

### Dynamic SQL

Dynamic SQL is a handy feature of a database that lets you construct SQL statements in a different way.

Learn more: [Dynamic SQL: A Guide](https://www.databasestar.com/dynamic-sql/)

### SQL Injection

SQL Injection is a technique that allows users to run malicious commands on your database. Protecting against it is an important thing to do for developers.

Learn more: [SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection)

## Procedural Language

### Oracle PL/SQL

PL/SQL stands for Procedural Language Structured Query Language, and is the language of the Oracle database that allows for procedural concepts (such as If statements and variables) to be used with SQL.

Learn More:

- [PL/SQL Tutorial](https://www.databasestar.com/plsql-tutorial/)
- [A Beginner’s Guide to Cursors](https://www.databasestar.com/sql-cursor/)
- [Oracle Triggers](https://www.databasestar.com/oracle-triggers/)
- [Stored Procedures](https://www.databasestar.com/sql-stored-procedures/)

### SQL Server T-SQL

T-SQL is SQL Server’s procedural programming language.

Learn More:

- [T-SQL Tutorial and Stored Procedures](https://docs.microsoft.com/en-us/sql/relational-databases/stored-procedures/create-a-stored-procedure?view=sql-server-ver15)
- [A Beginner’s Guide to Cursors](https://www.databasestar.com/sql-cursor/)
- [Stored Procedures](https://www.databasestar.com/sql-stored-procedures/)

### MySQL Stored Procedures

Stored procedures can be created in MySQL using their procedural language.

Learn More:

- [A Beginner’s Guide to Cursors](https://www.databasestar.com/sql-cursor/)
- [Stored Procedures](https://www.databasestar.com/sql-stored-procedures/)

### PostgreSQL pl/pgSQL

PL/pgSQL is the PostgreSQL version of a procedural language.

Learn More:

- [pgSQL Tutorial](https://www.postgresqltutorial.com/postgresql-plpgsql/)
- [A Beginner’s Guide to Cursors](https://www.databasestar.com/sql-cursor/)
- [Stored Procedures](https://www.databasestar.com/sql-stored-procedures/)

## Database Objects

### Views

Views are objects that store a saved SQL statement, and offer several benefits including query simplification, code reuse, and security.

Learn more: [SQL Views](https://www.databasestar.com/sql-views/)

### Oracle Synonyms

A synonym is an object that refers to another object. This is often done for security or to allow for easier database changes.

Learn more: [Synonyms in Oracle](https://www.databasestar.com/oracle-synonym/)

## Database Administration

### Privileges

Privileges are different activities or functions that can be made available to users. They are added or removed from users or roles.

Learn more:

- [Privileges in Oracle](https://docs.oracle.com/cd/A97630_01/server.920/a96524/c24privs.htm)
- [Permissions in SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/security/permissions-database-engine?view=sql-server-ver15)
- [Privileges in MySQL](https://dev.mysql.com/doc/refman/8.0/en/privileges-provided.html)
- [Privileges in PostgreSQL](https://www.postgresql.org/docs/13/ddl-priv.html)

### Roles

A role is something that can be applied to a set of users that share the same characteristics. Privileges or permissions can be applied to the role, making it easier to work with.

Learn more:

- [Roles in Oracle](https://docs.oracle.com/cd/A97630_01/server.920/a96521/privs.htm)
- [Roles in SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/database-level-roles?view=sql-server-ver15)
- [Roles in MySQL](https://dev.mysql.com/doc/refman/8.0/en/roles.html)
- [Roles in PostgreSQL](https://www.postgresql.org/docs/current/database-roles.html)

### User Management

Creating and removing users is another required task on a database.

Learn more:

- [Creating users in Oracle](https://chartio.com/resources/tutorials/how-to-create-a-user-and-grant-permissions-in-oracle/)
- [Creating users in SQL Server](https://docs.microsoft.com/en-us/sql/t-sql/statements/create-user-transact-sql?view=sql-server-ver15)
- [Creating users in MySQL](https://dev.mysql.com/doc/refman/8.0/en/create-user.html)
- [Creating users in PostgreSQL](https://www.postgresql.org/docs/current/sql-createuser.html)

### Data Dictionary

The data dictionary is an area of the database that contains a range of tables and views. They can help you find out more information about the database.

Learn more:

- [Oracle data dictionary](https://docs.oracle.com/cd/B10501_01/server.920/a96524/c05dicti.htm)
- [SQL Server data dictionary](https://dataedo.com/kb/query/sql-server)
- [MySQL Server data dictionary](https://dev.mysql.com/doc/refman/8.0/en/data-dictionary.html#:~:text=MySQL%20Server%20incorporates%20a%20transactional,storage%20engine%2Dspecific%20data%20dictionaries.)
- [PostgreSQL system catalogs](https://www.postgresql.org/docs/current/catalogs.html)

Have I missed anything on this list? Let me know in the comments below.