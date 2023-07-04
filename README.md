# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Practicing the Statistical-Modelling-with-Python
Performing APIs request and EDA.

## Process
##step 1: Accessing data using APIs
 sent a query to Citybike, Foursquare, and Yelp.
 extract the information based on latitude and longitude
 spot restaurants as my POI 
 concatenate the table
	
##step 2:Cleaning Data
 remove duplicate restaurant
 split the address to keep only the first part
 remove null value like a station with 0 bike
 sorted the data by distance from the station
 put cleaned data in a CSV file.

##step 3:Performing EDA
 reading CSV files of both part
 put them all tables together by nearest lat and long
 (every restaurant has the name of the nearest station and distance to this station and the number of bikes)
 visualization is done by scatter plot.

##Step 4: Identifying trends
 the plot and other statistical model shows that Roma station has the highest number of restaurants

##step 5:results
 null hypothesis :is there is any relationship between the locations(IV) and the number of bikes(DV) in the nearest station
 p-value is lower than 0.05 so we reject the null hypothesis
 the log-likelihood indicates that the data is quite unlikely
 R-square only 21.8% of the total variance in the dependent variable can be explained by the independent variable
 
## challenges:
 the model needs more features and more API to be sent 

## Future Goals
managing my time better
