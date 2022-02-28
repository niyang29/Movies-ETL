# Movies - Extract, Transform, and Load (ETL)

## Project Overview

Purpose: In order to help prepare for a hackaton, it was important to gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that hackathon participants have a clean dataset to use. The Extract, Transform, and Load (ETL) process was utilized - extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.

## Process

1. Write an ETL Function to Read Three Data Files - Kaggle metadata, Wikipedia, and Movie Lens (reference ETL_function_test.ipynb)
*  Extract data from website in JSON and CSV formats.
*  Data is written in Pandas DataFrames.
*  Loading the JSON file through creating a file directoring and uploading via pandas

2. Extract and Transform the Wikipedia Data (reference ETL_clean_wiki_movies.ipynb)
* Clean movie by combining data of alternative languages into one column.
* Reorganize columns to create a more consistent pattern.
* Using list comprehension, regular expression (regex), and apply and map() methods and lambda functions.

3. Extract and Transform the Kaggle Data (reference ETL_clean_kaggle_data.ipynb)
* Changing the appropriate datatype.
* Filling in missing values.
* Mergeing DataFrames.

4. Create the Movie Database (reference ETL_create_database)
* Connect the database by sqlalchemy library and to_sql method
* And Finally ETL - extract, transform, and load the data. 
