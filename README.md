# Movies-ETL
## Overview
 Amazing Prime video is a platform for streaming movies and television shows through the world’s largest online retailer Amazing Prime.  Amazing prime is sponsoring a hackathon to develop an algorithm to see which low budget movies will become popular so they can purchase streaming rights for a bargain. We have been asked to help an employee of Amazing Prime, Britta to create a clean dataset for the hackathon.   
We were given two different sources to gather our data. One was a scrape of Wikipedia and another rating data from MovieLens website. The files are .csv and JSON file types. 
We used the ETL function to perform this task. The ETL function to read three data files, extracting and transforming the Wikipedia Data and again the Kaggle Data. Lastly, we created the Movie Database in PostgreSQL. 

## Write an ETL Function to Read the Three Data Files
-	Using Python, Pandas and ETL process and code refactoring, wrote a function that read in the three data files and created three separate DataFrames
o	wiki_movies_df
o	kaggle_metadata
o	ratings 
o	insert function img



## Extract ad Transform the Wikipedia Data
-	Using Python, Pandas and ETL process and code refactoring, we extracted and transformed Wikipedia data and merged it with the Kaggle metadata. Used the Try and Except block to catch errors 
-	Clean and Filtered data with list comprehensions
-	Wrote functions 
o	Created clean_movie function
o	Insert the clean_movie function file
-	Removed unnecessary columns with null values
-	Dropped null values and coverted data to string values
-	Cleaned the box office data
-	Cleaned the budget data, the release date, and the running time 

## Extract and Transform the Kaggle Data
-	Using Python, Pandas and ETL process and code refactoring, we extracted and transformed the Kaggle metadata and MovieLens rating data, then converted it into separate DataFrames. 
o	movies_df DataFrame
	merged the Kaggle metadata DataFrame with the Wikipedia movies DatFrame
o	movies_with_ratings_df 
	Merged the MovieLens rating data DataFrame with the movies_df DataFrame 
## Create the Movie Database 
-	Used PostgreSQL

