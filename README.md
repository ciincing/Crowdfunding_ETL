# Crowdfunding_ETL Project 2 (/w Yolanda Bustos and Ciin Cing)

For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

## Instructions
The instructions for this mini project are divided into the following subsections:

Create the Category and Subcategory DataFrames
Create the Campaign DataFrame
Create the Contacts DataFrame
Create the Crowdfunding Database

## Create the Category and Subcategory DataFrames
1. Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame that has the following columns:
   - A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories
   - A "category" column that contains only the category titles
   - The following image shows this category DataFrame:
   - <img width="92" alt="image" src="https://github.com/ciincing/Crowdfunding_ETL/assets/130705911/6416de2b-51b1-4724-a876-666d3e518745">
