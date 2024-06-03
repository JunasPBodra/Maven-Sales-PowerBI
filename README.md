# Maven-Sales-PowerBI

OBJECTIVE 1
Connect and profile the data
Your first objective is to connect to the source data files, conduct basic profiling and QA tasks, and familiarize yourself with the tables and fields you'll be working with.
 - Connect to the sales, products, stores, and calendar csv files

- Review table columns, check for blank or null values, confirm that datatypes are accurately defined, and identify any primary and foreign keys

- Take a moment to profile the data. How many transactions were recorded? How many stores does Maven Toys operate? What are the lowest and highest priced products?

- Add calculated columns in the calendar table for ‘start of month’ and ‘start of week’


OBJECTIVE 2
Create a relational model
Your second objective is to create a relational data model by defining relationships between fact and dimension tables, creating simple hierarchies, and adjusting model properties.

- Load the tables to the data model and create relationships from the sales table to the products, stores, and calendar tables

- Confirm that you are following data modeling best practices. Your model should take the form of a star schema, with 1:many relationships between fact and dimension tables

-  Create a date hierarchy containing the ‘start of month’, ‘start of week’, and ‘date’ fields

- Hide all foreign keys in the sales table from the report view
