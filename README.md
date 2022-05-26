# Movie Ratings ETL
Using PostgreSQL, jupyter notebook, and movie data I cleaned, analyzed, and created databases for movies and ratings.

### Resources
- Data source: wikipedia-movies.json, movies_metadata.csv*, ratings.csv* (* from [Kaggle](https://www.kaggle.com/rounakbanik/the-movies-dataset/download))
- Software: PostgreSQL 11, jupyter notebook

## Overview of Project
Using the Wikipedia JSON and Kaggle CSVs I
- Cleaned data for duplicates (movies named in different languages)
- Cleaned box office, budget, release data, and running time columns
- Merged DataFrames on the kaggle_id
- Added Python DataFrames to a SQL Database
