# Upgrade-Project
Nithin B upgrade project

NYC tickets analysis using Spark
The NYC Police Department has collected data for parking tickets. Of these, the data files for multiple years are publicly available on Kaggle. We will try and perform some exploratory analysis on a part of this data. Spark will allow us to analyse the full files at high speeds as opposed to taking a series of random samples that will approximate the population. For the scope of this analysis, we will analyse the parking tickets over the year 2017.

In this project ticket anlysis is don to find out the most pressing violations in NYC. The Steps for analysis are as follows:

Load the dataset into a dataframe.
Perform Data Inspection and Data Cleaning on the dataframe.
Exploratoratory Data Analysis is done on the dataframe.
Answer the following question using Spark
Find the total number of tickets for the year.
Find out the number of unique states from where the cars that got parking tickets came.
Find out How often does each violation code occur? Display the frequency of the top five violation codes.
How often does each 'vehicle body type' get a parking ticket? How about the 'vehicle make'?
Find the violation code frequencies for three precincts that have issued the most number of tickets. Do these precinct zones have an exceptionally high frequency of certain violation codes? Are these codes common across precincts?
Divide 24 hours into six equal discrete bins of time. Choose the intervals as you see fit. For each of these groups, find the three most commonly occurring violations.
Then, find the three most common violations for each of these seasons.
The fines collected from all the instances of parking violation constitute a source of revenue for the NYC Police Department.Find the total occurrences of the three most common violation codes.
After answering the questions insights based on viloation code are provided
