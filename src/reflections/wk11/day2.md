# Day 2 - MYSQL RELATIONSHIPS (MANY-TO-MANY)

## Daily Journal - Read Dotnet WebAPI's > Relationships, and answer the following questions

1. What is the difference between a primary key and a foreign key

primary key is the main part of the sql table, it is the unique thing that prevents duplicate data. the only that should ever be the primary key is ID
foreign key is data used from other tables populated on other tables. again, usually reserved for ID's

2. What is an Alias?

a nickname for accounts or data

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

This is what I would write
    SELECT 
    doctors.*,
    patients.* 
    FROM keeps doctors
    JOIN accounts patients ON doctors.creatorId = patients.id;


## Links
[contractor](https://github.com/PaytonMacdonald/contractor)