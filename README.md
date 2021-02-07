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
 Web APIs allow us to request data from a website or database server by observing the rules of the website. When we retrieve data from an API, the data is returned 
 a variety of formats such as csv and json formats. Many analysts prefer json format because it has hierarchical structure and stores metadata in key-value pairs. 
 We analyze data using pandas, matplotlib library and google maps API. Lastly, the end results is a series of plots that visually statistically show the relationship between latitude and variety of weather parameters. 
 
## Resources
- Data Sources: WeatherPy_Database.csv, WeatherPy_Vacation.csv, Web APIs
- Software: [Anaconda( Jupyter Notebook )](https://www.anaconda.com/products/individual)
- Module: Pandas, Numpy, CitiPy, Matplotlib.pyplot, gmaps




## Summary
We added the weather description to the weather data that we have already retrieved. Then we have the beta testers use input statements to filter 
the data for the weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential 
travel destinations, the beta tester will choose four cities to create a travel iternerary. Finally, using the Google Maps Directions API, we create 
a travel route between four cities as well as layer map. 

