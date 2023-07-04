# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Practicing the Statistical-Modelling-with-Python
Performing APIs request and EDA.

## Process
step 1: Accessing data using APIs
 sent query to Citybike, Foursquare and Yelp.
 extract the information based on latitude and longitude
 spot restaurants as my POI 
 concaten the table
step 2:Cleaning Data
 remove dublicate restaurant
 split the adress to keep only first part
 remove null value like station with 0 bike
 sorted the data by distance from station
 put cleaned data in csv file
step 3:Performing EDA
 reading csv files of both part
 put them all tables together by nearest lat and long
 (evry restaurant has name of nearest station and distance this station and number of bike )
 visualisation done by scatter plot
step 4: Identifying trends
 the plot and other statistical model shows that Roma station has the highest number of restaurants
step 5:results
 null hypothesis :is there is any relationship between the locations(IV) and the number of bikes(DV) in the nearest station
 p value is lower then 0.05 so we reject the null hypothesis
 the log-likehood indicating that the data is quite unlikely
 R-square only 21.8% of the total variance in the dependent variable can be explained by the independent variable
 
## challenges:
 model need more features and more API to be sent 

## Future Goals
managing my time better
