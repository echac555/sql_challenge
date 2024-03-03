# Sql_Challenge

It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

Purpose:
We conducted data modeling, data engineering, and data analysis using SQL on CSV files containing employee databases from the 1980s to 1990s for Pewlett Hackard. This involved creating entity-relationship diagrams, establishing tables in PostgreSQL, importing CSV files into these tables, and conducting thorough analysis and querying of the data.

Process:
Data Modelling:
In the realm of data modeling, I crafted an Entity Relationship Diagram (ERD) encompassing the CSV files residing in the EmployeeSQL directory, including: departments, dept_emp, dept_manager, employees, salaries, and titles. The diagram was created on QuickDBD: https://www.quickdatabasediagrams.com/

The diagram is labelled as: QuickDBD-ERD.png

Data Engineering:
The schema of the code can be found labelled: schema.sql or QuickDBD-ERD.sql. The latter was exported from the QuickDBD website when making the diagram.

Please adhere to the following sequence of steps:
1. Begin by executing all the scripts to create the tables.
2. Proceed to import the CSV files.
3. Finally, execute the scripts for setting up foreign keys and making alterations to the employees table as necessary.

Data Analysis:
Data analysis and querying have been successfully conducted and are documented in the file named: Data_Analysis.sql

Table of contents

Resources:
Used to assist in using QuickDBD:
https://www.youtube.com/watch?v=dR5lPbGLY84
https://www.quickdatabasediagrams.com/

Creating Tables:
Referenced in class work to assist in the code and formatting on creating tables.

Importing CSV files into pgAdmin4:
Referenced in class work to assist in formating and steps on importing csv files.

Data engineering:
Referenced in class work to assist in code and format for Primary Keys, Foreign Keys, Null/Not Null conditions and Value lengths for each row (VARCHAR/INT)

generated from QuickDBD:
https://www.quickdatabasediagrams.com/

Data analysis:
Referenced in class work to assist in code and format

ChatGPT: used to assist in coding and formatting when errors presented themselves: 
chat.openai.com

Used to assist in what to include in the README.md file: 
https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/

