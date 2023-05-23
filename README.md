# Crowdfunding_ETL
Data Analytics Boot Camp Project 2.    
Sandeep Sumithran, Tattwamasi Ray, Owen Johannes

## Tables
The database consists of the following tables:

'contacts'     
'category'       
'subcategory'     
'campaign'

## Table Relationships
The tables in the database are related to each other using foreign key constraints. The following relationships exist:

campaign.contact_id references contacts.contact_id  
campaign.category_id references category.category_id   
campaign.subcategory_id references subcategory.subcategory_id

## Queries
To view the data stored in the tables, you following queries can be executed:

SELECT * FROM Campaign;: Retrieves all records from the campaign table.    
SELECT * FROM Category;: Retrieves all records from the category table.    
SELECT * FROM Subcategory;: Retrieves all records from the subcategory table.    
SELECT * FROM Contacts;: Retrieves all records from the contacts table.
