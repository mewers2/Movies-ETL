# Movies-ETL

## Project Overview

The purpose of this project is to create an Extract, Transform, Load data pipeline for the multiple large movie-related datasets.  First, the data is scraped from the web, then the data is cleaned, extracted and transformed to a much more user-friendly format and composition.  Lastly, the datasets are loaded into an easily queryable database in SQL.

One example of the end-product of this ETL is the clean and concise dataframe displayed below showing the movie ratings.  This dataframe was created using data from two different large datasets which were scraped from the open web and cleaned through the ETL process.  Once transformed, the two datasets were merged to create the dataframe displayed here:

![ratings](https://github.com/mewers2/Movies-ETL/blob/main/Resources/ratings.png)

For the last step of the ETL process, the data was loaded into a SQL database, as shown here:

![ratings_query](https://github.com/mewers2/Movies-ETL/blob/main/Resources/ratings_query.png)