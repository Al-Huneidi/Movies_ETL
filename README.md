# Movies_ETL
Use ETL to create database that can be analyzed to predict movie popularity.

# Objective
Prepare a dataset for a hackathon using the ETL process.  Gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that the hackathon participants have a nice, clean dataset to use.

### Resources:

Downloaded wikipedia.movies.jason
Downloaded from Kaggle the-movies-dataset zip folder
	Unzipped the folder and used 2 of the files:  movies_metadata.csv and ratings.csv 

## Steps Taken in the ETL Process

1. Inspected the data to determine any problems that may need to be addressed int the transformation process.

2.  Filled in missing data
	- substituted data from another data frame that had good data
	- interpolated between existing data points
	- extrapolated from existing data

3. Normalized the data
	- reshaped the data
	- converted data types
	- parsed text data to the correct format
	- split columns using regex

Used during entire transformation process:

	- list comprehensions to filter data
	- created functions to perform the cleaning process
	- lambda functions
	- regular expressions, regex
	- parsing
	- histogram
	- scatter plots
	- connected pandas to a SQL database by creating a Database engine
	
Images generated to compare similar values between the data sets:

Histogram:
![alt text](https://github.com/Al-Huneidi/Movies_ETL/blob/master/Screenshots/Ratings%20Histogram%20and%20Statistics.png)

Scatter Plots:
Realease Dates
![alt text](https://github.com/Al-Huneidi/Movies_ETL/blob/master/Screenshots/release_date_wiki%7Crelease_date_kaggle.png)

wiki_box_office vs kaggle_revenue
![alt text](https://github.com/Al-Huneidi/Movies_ETL/blob/master/Screenshots/wiki_box_office%7Ckaggle_revenue.png)

wiki_budget vs kaggle_budget
![alt text](https://github.com/Al-Huneidi/Movies_ETL/blob/master/Screenshots/wiki_budget%7Ckaggle_budget.png)

wiki_running_time vs kaggle_runtime
![alt text](https://github.com/Al-Huneidi/Movies_ETL/blob/master/Screenshots/wiki_running_time%7Ckagggle_runtime.png

Verification data copied to movies table in SQL database:
![alt text](https://github.com/Al-Huneidi/Movies_ETL/blob/master/Screenshots/row_count_movies_table_sql.png)
