# Movies-ETL

In this challenge we used Extract, Transform, and Load, or ETL on datasets which included a multitutde of features describing movies and their ratings from a wikipedia JSON file and from a large ratings csv file, respectively. We were tasked in creating functions that would clean, merge and drop columns from each dataset created.

After the ratings and movies dataframe were cleaned, they were merged based on their iMDB id. Finally, the movies_df and ratings_file were loaded and onto two tables in Postgres.