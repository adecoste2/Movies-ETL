# Movies-ETL

## Overview 
The purpose of this project is to create an automatedc pipling that takes in new data in the form of Wikipedia JSON data, Kaggle metadata, and MovieLens rating data, and then preforms the appropriate transformations of the raw data by writing code in jupyter notebook and finally adding the data to a PostgreSQL database. 

## Results 
The resulting database consists of two tables that are below:

A movies table with 6,052 rows of data representing a unique movie title. The table also includes columns with production information, i.e. movie budget, producers, actors and release data.

![movies_query](https://github.com/adecoste2/Movies-ETL/blob/main/Resources/movies_query.png?raw=true)

*Movies Query in PgAdmin*

A ratings table a table with 26,024,289 rows of data, each representing a viewer rating on a scale of 1 to 5. The ratings table additionally includes 5 columns of data, i.e. movie title, rating and date.

![ratings_query](https://github.com/adecoste2/Movies-ETL/blob/main/Resources/ratings_query.png?raw=true)

*Ratings Query in PgAdmin*
