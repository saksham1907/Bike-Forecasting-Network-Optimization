# LA-Metro-Bike-Share--Forecasting-Network-Mangement
Metro Bike Share is one of LA Metro's multiple public transportation options for Angelenos and visitors, which offers convenient round-the-clock access to a fleet of bicycles for short trips. 
I have tried to analyze the data available on LA metro bike share website to derive insights and answer some critical business questions through Data Science principles

The data was provided on the LA Metro Bike share website with the details of each trip from July 7, 2016,
to December 31st, 2018. Another dataset was provided for the details of individual stations with their Go
live dates, region they belong to and their status as on date. Following points can be noted from the by
analyzing the Data Sets coherently:
1. The LAbike dataset had 639786 unique trip details with 13 attributes pertaining to start and end
station IDs with their co-ordinates, start and end times, pass holder type and trip category
whether one way or round trip.
2. Stations_Table dataset provides the details of each 143 stations with their unique Station IDs,
station names and their Go Live Date. 

The questions that we targeted through our approach concern forecasting the demand for bicycle,
revenue generation through ticket sales and recommendations for Bicycle Staging in 2019. For forecasting
purposes, performed feature engineering to obtain the count of bike trips for a given day and time-series
analysis was done using the ARIMA algorithm to predict the demand for next quarter. This demand is
distributed in the proportion of trips at each station as per given data and the bicycle demand is estimated
using this ratio. For the pricing analysis, we have only used the data available for the walk-up category as
the rider information is not provided in the dataset and it cannot be ascertained that how many times an
individual rider used his pass in a given day. From the network management aspect, we have categorized
the routes which have the highest traffic and the maximum distance and proposed new stations at these
routes.
