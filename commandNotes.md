# Guide to basic commands/notes for sql. Note: utilizing mySQL
- **Note:** good habit is capitalizing sql commands, but not necessarily required
- `-- SQL COMMENT`
## Databases (schemas)
- `SHOW DATABASES;`
- `CREATE DATABASE <name>;`
- `DROP DATABASE <name>;`
- `USE <name>;`
- `SELECT DATABASE();`: show current working database   
## Tables
- **Note:** Some examples of valid datatypes include `LONGINT`, `INT`, `CHAR(x)`, `VARCHAR(x)` where x is the max_length
- ```CREATE TABLE <table_name> (<column1> <datatype>, <column2> <datatype>);```
- `SHOW TABLES;`
- `SHOW COLUMS FROM <table_name>;` OR `DESC <table_name>;` OR `DESCRIBE <table_name>;`
- `DROP TABLE <table_name>;`
