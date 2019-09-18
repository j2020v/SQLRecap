# WEEK 2 RECAP

## SQL

<p>For Week 2 at Sparta, I learnt <b>Structured Query Language (SQL)</b> which is a language that retrieves information from a database.</p>

<b>Primary Key</b> is a unique key that identifies each record in the table. A Primary Key must:
* <p>must be unique </p>
* <p>must have an entry (cannot be null/blank)</p>
* <p>value must never change</p>

<b>Foreign Key</b> is a primary key of another table that provides a link between two tables, thus becoming a foreign key.

## DDL Data Definition Language
Alters/defines table
* CREATE
* ALTER
* DROP
* TRUNCATE
* CHARINDEX

## DML Data Manipulation Language
Creates table
* SELECT
* INSERT
* UPDATE
* DELETE

## Creating Databases
* <b>VARCHAR</b> - is a datatype. We are telling the databases what kind of 'stuff' will go in the column.</p>
* <b>DECIMAL</b> - fixed precision and scale.</p>
* <b>BINARY</b> - stores 1s, 0s, image or file</p>
* <b>FLOAT</b> - scientific use (very large number)</p>
* <b>INT</b> - holds an integer</p>
* <b>DATETIME</b> - stores date, time, both</p>
* <b>CHARINDEX</b> - fixed length</p>

## String Functions
* SUBSTRING( ) - substitute for any other characters
* LEN( ) - length
* REPLACE - replace piece of strings of text in a large body p
* UPPER/LOWER - capitalises/lower case
* CHARINDEX( ) - searches for a string

## Aggregate Functions
* SUM( )
* AVG( )
* MIN( )
* MAX( )

## Date Functions
* GETDATE( )
* SYSDATETIME( )
* DATEADD( )
* DATEDIFF( )

## Subquery
* Nested query inside another SELECT statement
* Usually in the WHERE( ) clause when there's no foreign key use subsquery

## Wildcards
* LIKE - substitute for any other characters
* % - a substitute for zero or more characters
* _ - a substitute for a single character
* . - distinguishes the table then going to column
