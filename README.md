# Bikeprediction-project
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental 1593765632600.jpg

First we import the necessary libraries and look at our data and its characteristics. We have a dataset of 8760 rows and 14 columns with no duplicate/missing data. Next we study the features thoroughly and the data it represents.

We first see that the column 'Date' is in 'object' datatype, and we convert it to datetime datatype. Later from the date column, we extract, 'Date', 'month', 'year' and number of week, We drop the date column and we rename columns for convinence.

We ploted various charts and explored usefull insites.

Based on our visualizations, we formulate 3 hypothetical statements and perform hypothesis tests. The statements are:

1:-The average bike count in Seoul city at any point of time is greater than 100.

2:-he average temperature in Seoul city at any point is grater than 10 degree Celsius.

3:-The Standard deviation of humdidity in Seoul city is 20.

Furthur, we performed one hot encoding on our categorical features with dropping the first column being true. We found out during visualization that our dependant variable, 'Rented_bike_count' was right skewed, hence to overcome this we applied a squareroot transformation to get a normal distribution. Next we scaled our data using MinMax scaler. Finally we split our data into train and test in 80-20 ratio.

The data was ready to fit into a machine learning model, we implemented the various models and calculated the various stastical parameters for the performance

Finally, we see that the bike rental company can deploy a machine learning model that uses Random Forest Regressor to predict the demand for city bikes for a particular hour, which can help the company meet the demand accurate

*Problem Statement *

The problem statement for this project is to develop a machine learning model that can accurately predict the number of rental bikes required at each hour in urban cities. This is crucial for ensuring a stable supply of rental bikes and minimizing waiting times for users. The project aims to address the challenge of making rental bikes available and accessible to the public at the right time by predicting the demand for rental bikes at different times of the day. The ultimate goal is to help cities optimize their bike-sharing systems by predicting demand and allocating resources accordingly

General Guidelines : -

1:-Well-structured, formatted, and commented code is required.

2:-Exception Handling, Production Grade Code & Deployment Ready Code will be a plus. Those students will be awarded some additional credits.

   The additional credits will have advantages over other students during Star Student selection.
      [ Note: - Deployment Ready Code is defined as, the whole .ipynb notebook should be executable in one go
          without a single error logged. ]
3:-Each and every logic should have proper comments.

4:-You may add as many number of charts you want. Make Sure for each and every chart the following format should be answered.
