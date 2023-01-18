# Weather Data Analysis

## Overview of Project

### Purpose

The purpose of this analysis is to analyze weather data using Python, Pandas functions and methos, and SQLAlchemy. 
Investor W.Avy wants information about temperature trends before opening up a surf shop in Oahu, in order to determine if
a surf and ice cream shop business is sustainable year round. The weather dataset is in a SQLLite file and it includes temperature data year
round from 2010 to 2017. 

## Results
In this project I filtered the date columns to retreive all the temperatures for the month of June and December. The temperatures were
converted into a seperate list each and then put into seperate Dataframes. Lastly, a summary statistics was generated with `df.describe()`.

The results are:

![June_Temps.PNG](/resources/June_Temps.PNG)		![December_Temps.PNG](/resources/December_Temps.PNG)


Here are three key differences in weather between June and December.

- The average temperature for the month of June is about 75 degrees while in December it's around 71 degrees.
- The minimum temperature for June is 64 degress which is higher compared to 56 degrees in December.
- The maximum temperature for December is 83 degrees and for June it's 85 degrees.

## Summary 
Looking at the results, we can see the most frequent temperatures for June are above 73 degrees. The more frequent temperatures for December are above
65 degrees. An additional query I would add to gather more data for June and December is the precipitation numbers and elevation.  
