# Crowdfunding_ETL
## For the ETL mini project, you and a partner will develop an ETL pipeline using Python and Pandas, focusing on data extraction and transformation. You'll start by creating several DataFrames from the crowdfunding.xlsx file, resulting in four CSV files. These will serve as the foundation for building an Entity-Relationship Diagram (ERD) and defining a table schema, which you will implement in a Postgres database.

## Project Steps

## Create Category and Subcategory DataFrames:
Extract unique categories and subcategories from the Excel data.
Build DataFrames with sequential IDs (category_id and subcategory_id) alongside their respective titles.
Export these DataFrames as category.csv and subcategory.csv.

## Create Campaign DataFrame:
Transform the crowdfunding data to create a campaign DataFrame with multiple specified columns, including cf_id, contact_id, and others.
Rename and convert certain columns as necessary (e.g., changing blurb to description and converting dates).
Include category_id and subcategory_id from the earlier DataFrames.
Export as campaign.csv.

##Create Contacts DataFrame:
Choose between two methods for extracting data from contacts.xlsx: using Python dictionary methods or regular expressions.
Process the data to separate full names into first and last names.
Export this cleaned DataFrame as contacts.csv.

## Create the Crowdfunding Database:
Analyze the four CSV files to sketch an ERD using a tool like QuickDBD.
Define the table schema in SQL, detailing data types, primary and foreign keys.
Save the schema as crowdfunding_db_schema.sql and create the crowdfunding_db database in Postgres.
Create tables following the schema, ensuring foreign key relationships are correct.
Import the CSV files into the corresponding tables and verify the data with SELECT statements.
Source Files

## Notebooks and Queries: The project includes a starter notebook, ERD diagram, validation queries, and the folder structure for resources and outputs.
This structured approach will help you effectively build your ETL pipeline and database for the crowdfunding data.
