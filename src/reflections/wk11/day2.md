# Day 2 - MYSQL RELATIONSHIPS (MANY-TO-MANY)

## Daily Journal - Read Dotnet WebAPI's > Relationships, and answer the following questions

1. What is the difference between a primary key and a foreign key



2. What is an Alias?



3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)




## Links
[contractor](https://github.com/PaytonMacdonald/contractor)