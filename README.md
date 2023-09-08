# Gender-Disparity-Olympic-Games

Documentation of an Analysis Project done on the existing company Instacart, an online grocery store that operates through an app. Done as part of the CF Data Analysis Certification course.

## Background and Key Questions
1. What is the gender distribution of athletes over different Olympic editions?

2. Is there a relationship between pyshical attributes of female and male athletes?

3. What's the country distribution of medals by gender?


## Data Set
For this project, a series of open-source data sets the Olympic Games were used. While each data set contains a different kind of information, they all include some
kind of common identifier. Data set is called 'Olympic Historical Dataset From Olympedia.org' and was accessed via Kaggle on September 2023: https://www.kaggle.com/datasets/josephcheng123456/olympic-historical-dataset-from-olympediaorg?select=Olympic_Athlete_Bio.csv

## Data Limitations and Ethics
The data was collected through web scrapping therefore there could be some problems inherent to this. 

Athlete to event data is validated by providing some data aggregation to medal tally data and then comparing the counts of medals won by each country in all Winter / Summer Olympic games. Details are provided via source code in github.
Finally, data contains personal identifiable information (PII)  (specifically, name and birthdate) which can be an issue. However, athletes are considered public figures, and no other information like address is not present. 
