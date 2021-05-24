# Day 3 - CONNECTING TO A MYSQL DATABASE

## Daily Journal - Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

1. In a SQL table, what is the difference between information in a row and information in a column?

well the row is like an object but each column is one specific value out of all objects in that table

2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters (
  id INT NOT NULL AUTO_INCREMENT,
  name VARCHAR(255) NOT NULL,
  age VARCHAR(255) NOT NULL,
  description VARCHAR(255) NOT NULL,
);

3. What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

delete from removese like one value or thing
DROP TABLE deletes the entire ga'darn table... don't do it unless you reeeeeaaally gotta


## Links
<!--some comment-->
[castlesandknights](https://github.com/PaytonMacdonald/knightcastle)