# World_Weather_Analysis
## Project Overview
This project is done as follows: 
   - retrieve data from APIs 
   - store data in a dataframe
   - plot the data using matplotlib and google maps
   - perform statistical analysis
   
 The purpose of this analysis is to practice the analysis, visualization, and statistical skills by retrieving and analyzing weather data from 
 a website to an application programming interface. Gathering data from an API is more practical and efficient than trying to obtain data directly from
 a website specially when we want megabytes and gigabytes of data.
 Web API allow us to request data from a website or database server by observing the rules of the website. When we retrieve data from an API, the data is returned 
 a variety of formats such as CSV and json formats. Many analysts prefer json format because it has hierarchical structure and stores metadata in key-value pairs.  
 
 
 
 for a hypothetical travel company, PlanMyTrip.  
   
  

## Resources
- Data Sources: WeatherPy_Database.csv, WeatherPy_Vacation.csv, APIs
- Software: [Anaconda( Jupyter Notebook )](https://www.anaconda.com/products/individual), [Matplotlib-Python Plotting](https://matplotlib.org/) 
- Module: Pandas, Numpy, CitiPy, Matplotlib.pyplot, gmaps

## Results
Looking at the ride-sharing dataframe, we can see:


![here](https://github.com/halmasieh/PyBer_Analysis/blob/main/ride_sharing_data.PNG)



   - The total rides in the urban cities is about 2.6- and 13-times more per city than the suburban and rural cities, respectively.
   - The total drivers in the urban cities is about 5- and 31-times more per city than the suburban and rural cities, respectively. This shows that driving jobs
   in the urban cities is more prosperous.
   - The total fares in the urban cities is about 39854 which is not much different from the total fares in the suburban cities, almost 2.1-times and it is still
   9.2-times more per city than the rural cities.
   - The amount of average fare per ride in the rural and suburban cities is very close while the average fare per ride in the urban cities is less than the 
   amount of average fare per ride in the recent cities.
   - The average fare per driver in the rural and suburban cities is about 3.3- and 2.4-times more than the average fare per driver in the urban cities, repectively.

The above results show that the total rides, drivers and fares in the urban cities are more than the other cities while the average fare per ride and driver in the rural 
cities are more than the suburban and urban cities. In other words, suburban cities are mediated by all the five parameters.

## Summary
1- Looking at the sum of the fare for each week in the first quarter of the year, 



![here](https://github.com/halmasieh/PyBer_Analysis/blob/main/sum_fare.PNG)



the total fares in the urban cities is more than the other type of cities and it could be a sence of overall revenue.

2- The analysis of the total fare from January-April 2019 based on the following plot is as follows:



![here](https://github.com/halmasieh/PyBer_Analysis/blob/main/PyBer_fare_summary.png)


   - The urban cities experienced the highest total fare before and after the month March and on equal terms this happens 
 for suburban and rural cities before March and in April, repectively. 
   - In general, total fare fluctation for urban, suburban and rural cities is in the intervals [1700-2500], [750,1400] and [0,500], respectively. Therefore, 
   monitoring the growth and stagnation of cities, can be used to start a business in the transportation industry.   
   - Almost from mid-April, total fare growth in suburban cities has an upward trend compared to other type of cities.
   
 
 Undoubtedly, This analysis can be effective in job creation and economic circulation of the cities.
