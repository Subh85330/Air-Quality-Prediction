# Air-Quality-Prediction
 Linear Regression using Python
 
 # Data
In this work, we tackle air quality forecasting by using machine learning approach i.e. linear regression to predict the hourly concentration of air pollutants (e.g., ozone, particle matter (PM2.5) and sulfur dioxide). .We collected air pollutant data and meteorological data from internet of two weather stations of 2015. We selected the meteorological variables that would affect the air pollutant concentrations, including air temperature, relative humidity, wind speed and direction, wind gust,precipitation accumulation, visibility, dew point, wind cardinal direction, pressure, and weather conditions.

# Setup:
We manipulated the Meteorological data table and merge with hourly data table
which contains the concentration of ozone(O3). The final dataset with which we ended up is
used for further processing.
# Results:
After doing all the necessary stuff we predicted the concentration of Ozone by
our designed model. We predicted the mean absolute error which is having value
‘0.07506380683317264’ which is very less, later we also predicted mean squared error which
is having value ‘0.09546089593030946’. Both errors are very less, hence these are tolerable.
So, our model is predicting in a good way.
