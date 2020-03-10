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
