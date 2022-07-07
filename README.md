# Movies-ETL

## Overview of the analysis
With this analysis we are creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We refractored the code from the modue to create one complete function that takes in three files (Wikipedia data, Kaggle metadata and MoviesLens rating data) and perform the ETL process by adding the data to a PostgreSQL data.

## Results
The result of this analysis is the following:
- Movies table: Showing the information of each movie including imdb id and title.
- Rating table: Showing the movie id, user id that gave the rating and the rating given.

This two clean tables will be updated using the function on a daily basis to keep the database updated.
