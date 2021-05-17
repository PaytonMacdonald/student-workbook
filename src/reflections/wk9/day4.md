# Day 4 - Capstones

## Daily Journal - Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

1. In a SQL table, what is the difference between information in a row and information in a column?

a row is horzontal, a column is vertical...
each column contains all the information under the parameters of the top row. each row is one 'thing' that contains the information from each column in that particular row.

just like any other table chart

2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE houses(
  id int NOT NULL,
  description VARCHAR(255) NOT NULL,
  things int,
  thingsInThings int,
  thingFunction TINYINT DEFAULT 0
);

3. What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

delete from destorys the targeted data from the data and drop table bumps it out but the data isn't gone.


