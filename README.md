# ev_charging_stations
Analysis of electric vehicle charging stations

## Background

Problem Statement: To investigate the correlation between the availability of EV charging stations and the median household income among various zip codes in the US.

Objective: To determine if areas with higher household incomes have more accessibility to EV charging stations.

## Description of Code

The following code analyzes data for EV charging stations and US household median income by zip code.  The analysis will provide visualizations on determining a correlation between these two factors.  The Pearson Correlation function was used to identify the level of correlation using a correlation coefficient which ranges from -1 to 1, where a higher coefficient in magnitude shows a strong correlation.  A pseudo code was developed as a high level summary of how the code would execute the objectives of this analysis.

There were two datasets in csv format used for this analysis and were downloaded from Kaggel; 

EV charging stations csv

(https://www.kaggle.com/datasets/prasertk/electric-vehicle-charging-stations-in-usa?resource=download&select=ev_stations_v1.csv ) 

and 

Income by Zip Code csv 
(https://www.kaggle.com/datasets/claygendron/us-household-income-by-zip-code-2021-2011).

The code will require use of panda libraries, jupyter notebooks, and a git repository. 
This code is available at Github under (https://github.com/algjor/ev_charging_stations).

The following steps were followed to produce the desired outcome.

1. Import panda libraries and dependencies.

2. Import, read, and write data frame for the ev_stations.csv.

3.  Import, read, and write data frame for the us_income_zipcode.csv.

4. The EV Station Charging Station data was cleaned by sorting and dropping empty rows for the ev_stations.csv.

5. The US Household Income data was cleaned by sorting and dropping empty rows for the ev_stations.csv.

6. The EV Station Charging Station data was further cleaned by removing columns and creating a new dataframe with the necessary columns.

7. The US Household Income data was further cleaned by removing columns and creating a new dataframe with the necessary columns.

8.  The new EV Station Charging Station dataframe was sorted and organized by zip code.

9. The new US Household Income dataframe was sorted and organized by zip code.

10. List and view (zip, income,) for EV Station Charging Station.

11. List and view (zip, income,) for US Household Income.
     
12. Visualizations of US Household Income were displayed for the top 10 Median and Mean Household incomes for 2020CY and 2021CY.  A bar chart was used as a visualizations to show the trends for the Median and Household income over a 2 year span.

13. The EV EV Station Charging Station dataframe and US Household Income dataframe were then merged into one dataframe on zip code with the index reset.  A groupby function was used to accomplish this step. 
    
14. The data from this merged dataset was cleaned and the primary columns for analysis used were the following:  State, City, Zip, US Household Median Income, EV Charging Stations, and Year.  The number of EV Charging Stations was determined by counting the total number EV Connector by Zip and this column was then rename to EV Charging Stations.  The column ZIP was also renamed to Zip Code.  

15. The 2020CY and 2021CY dataframe(s) were created and sorted by top 10 US Household Median Income.

16. A scatter plot was used to graph each dataframe by the EV Charging Stations vs. US Household Median Income for Upper (greater than $149K USD) and Lower (less than $149K USD) Median Incomes.  

17. A Pearson Correlation function was performed on both these factors and showed that EV Charging Stations and US Household Median Income (Lower or Upper Household Median Incomes) do not have a strong linear relationship or correlation for the years of 2020 and 2021.
