# ev_charging_stations
Analysis of electric vehicle charging stations

## Background

Problem Statement: To investigate the correlation between the availability of EV charging stations and the median household income among various zip codes in the US.

Objective: To determine if areas with higher household incomes have more accessibility to EV charging stations.

## Description of Code
a - EV charging station [EV]
b - income data [CF]

(1) - Import panda libraries

(2a) - Import, read, write data frame from each csv

(2b) - Import, read, write data frame from each csv

(3a) - Clean data (sort, drop empty rows,) for each data set

(3b) - Clean data (sort, drop empty rows,) for each data set

(4a) - View unique values (drop columns not necessary) -> create the new dataframe for the columns to keep
    => Unique values analysis (utilities, parking garage, airport, shopping mall, shopping center)

(4b) - View unique values (drop columns not necessary) -> create the new dataframe for the columns to keep

(5a) - Sort and organize new dataframe by zip code

(5b) - Sort and organize new dataframe by income

(6a) - List and view (zip, income,) and use print statements:
    => Unique values of state names then get list of states with most chargers
    => 

(6b) - List and view (zip, income,) and use print statements:
    => Zip with highest income (view top 10)
    => Show a list of zip codes that have incomes > $149K
     
(7a) - Visualizations of EV charging stations
    => Ask Steven to help us with map Longitude & Latitude (Road block)
    
(7b) - Visualizations of quartiles for income data [AJ] 
    => Will follow-up Carolina to get example from homework

(8) - Merge dataframe(s) on zip code and reset index on zip code [AJ]
    => Determine on how to join (merge, concatenate, join)???
    
(9) - Clean (higher salary dataframe) and rename dataframe (final dataframe to perform regression analysis) [AJ]

(10.1) - Correlation - check Slack from Carolina (happiness) and Al (homesales)
    =>  Reference the homesales HW instructor solution ( reference Al)
    =>  Reference the happiness HW (7 Day1 Activities 1) -> use zip code instead of country
    
(10.2) - Compare data for income > 150K (create dataframe) and income < 150K (create dataframe)

    





Note:  J1772 remember to capture in data cleaning
