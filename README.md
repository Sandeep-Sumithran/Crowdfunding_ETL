# Crowdfunding_ETL
Data Analytics Boot Camp Project 2

For the ETL mini project, you will work with a partner to practise building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track.

Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support.
Background
In this project, Our group practiced building an ETL pipeline to process crowdfunding data from Excel files. I extracted and transformed the data, created four CSV files, and then used the CSV files to create an Entity Relationship Diagram (ERD) and a table schema. Finally, I loaded the CSV files into a PostgreSQL database.
Features
Extract and transform crowdfunding and contact data from Excel files
Create and export Category, Subcategory, Campaign, and Contact DataFrames as CSV files
Design an ERD and table schema for the database
Create and populate PostgreSQL database tables
Before You Begin
Create a new repository, named Crowdfunding_ETL, for this project. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Rename the ETL_Mini_Project_Starter_Code.ipynb file with your first name initial and last name, for example, ETL_Mini_Project_NRomanoff.ipynb. Then, add this Jupyter notebook file and the Resources folder containing the crowdfunding.xlsx and the contacts.xlsx files to your repository.

Push the changes to GitHub
Run the Jupyter Notebook to extract and transform data, and create CSV files.

Create the Crowdfunding Database
Inspect the four CSV files, and then sketch an ERD of the tables by using QuickDBDLinks to an external site..

Use the information from the ERD to create a table schema for each CSV file.

Note: Remember to specify the data types, primary keys, foreign keys, and other constraints.

Save the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it to your GitHub repository.

Create a new Postgres database, named crowdfunding_db.

Using the database schema, create the tables in the correct order to handle the foreign keys.

Verify the table creation by running a SELECT statement for each table.

Import each CSV file into its corresponding SQL table.

Verify that each table has the correct data by running a SELECT statement for each.

Built With:
Built With
Python
Pandas
PostgreSQL
Jupyter Notebook
Excel
