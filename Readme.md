# nosql-challenge

## Establishments NoSQL Database

## Background
It's time for the UK Food Standards Agency to evaluates establishments across the United Kingdom, and give them a food hygiene rating. You've been contratcted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Objective
The purpose of this project is to import data from json files into local MongoDB database via your terminal, use PyMongo library interface with MongoDB to update NosQl Database, and use aggregation pipeline with MongoDB to analyze the database.

## Technologies
MongoDB,
Mongoimport,
Jupyter notebook,
Pandas,
PyMongo,
Windows command prompt.

## Instructions
### Part 1: Database and Jupyter Notebook Set Up
Use NoSQL_setup_starter.ipnynb for this section of the challenge
* Import the data provider inthe establishments.json file from your Terminal.
* In your notebook, import all the libraries you need.
* Create an instance of the Mongo Client
* Confirm the database is created and loaded properly.
* Assign the establishments collection to a variable

### Part 2 : Update the Database
* Make the requested changes to the esytablishments collection

### Part 3 : Exploratory Analysis
Use NoSQL_analysis_starter.ipynb for this section of the challenge, and answer the followings:
* Which establishments have a hygeine score equal to 20:
* Which establishments in London have a RatingValue greater than or equal to 4?
* What are the top 5 establishments with RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
* How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


## Reference
Jason Lepelmeier,(2023, Mar 16). Class lecture: Pdf 12.3 Aggregation, Analysis, and Integration with MongoDB. Data Analytics and Visualization Bootcamp. University of Minnesota.https://umn.bootcampcontent.com/University-of-Minnesota-Boot-Camp/UofM-VIRT-DATA-PT-12-2022-U-LOLC/-/tree/main/12-NoSQL-Databases/3