# Covid-19-Dashboard

## Video 

Check out this video on how dashboard is created in power BI and what all information we can draw from each visuals created in the dashboard.
[Watch the Video part1](https://drive.google.com/file/d/1R6UgG_a0SpuILuXKe0JJfkhTGMI3ooyB/view?usp=drive_link)
[Watch the Video part2](https://drive.google.com/file/d/1H1tor9Kl6W3jEAvHrn4_Bou7P12TN30q/view?usp=drive_link)

## Objective
This project is mainly aiming to analyze COVID-19 data using power BI,For a better understanding of the informations and analysis made from the dataset is to create a dashboard .
The dataset that we have choosen here contains from global to country_wise infromation regarding COVID-19 in a particular year 2020.
The analysis focuses on visualizing key metrices such as confirmed cases, deaths, recoveries , New cases and trends over time.


## Dataset
The dataset used here contains the following table:

1. usa_county_wise.csv - Day to day county level no. of cases
2. worldometer_data.csv - Latest data from https://www.worldometers.info/
3. full_grouped.csv - Day to day country wise no. of cases (Has County/State/Province level data)
4. covid_19_clean_complete.csv - Day to day country wise no. of cases (Doesn't have County/State/Province level data)
5. day_wise.csv - Day wise no. of cases (Doesn't have country level data)
6. country_wise_latest.csv - Latest country level no. of cases


## Procedure

### step1:Data preprocesing
Data cleaning: Removed unwanted rows and columns,missing values, irrelavent columns


### step 2:Data Modelling
Designed the data model to establish relationship between the tables based on the existing common columns such as date , country/Region.
Made necessary changes in data type feilds for analysis in power BI.

### step3: Report creation
Inorder to visualize the trends and metrices of COVID-19 made use of certain effective visuals such  as cards, slicers,bar chart,column chart, area chart,Gauges , Map , donut charts,line charts,clustered bar chart.
To understand the spread and impact of the virus over the world,
Visualized trends of total confirmed cases , deaths and recoveries over time both Globally and Country_wise.
Analysed the trend of  CPR , Recovery rate, Mortality rate Globally by calculating creating new measures using the DAX language and  visualized and summarized to know the trend over time globally and country_wise.

### Dashboard Analysis Summary
From the insights gotten from the analysis of the covid-19 data, we can conclude that while Asia has the most population, the continent of Europe had the highest numbers in both cases and infection. 
This could be a result of a number of reasons which were not explored in this analysis, some of which may include the under-reporting of some of the cases in certain countries and the efficient handling of the outbreak in some others.


  
