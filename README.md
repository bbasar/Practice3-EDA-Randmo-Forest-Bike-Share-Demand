
## Practice3-EDA-Random-Forest-Bike-Share-Demand
EDA and Random Forest Model are utilized to predict bike sharing demand with information available prior to the rental period
Data available at: https://www.kaggle.com/c/bike-sharing-demand/data

Content: Bike sharing systems function as a sensor network, which can be used for studying mobility in a city. In this project, historical usage patterns and weather data are combined to forecast bike rental demand in the Capital Bikeshare program in Washington, D.C.

Acknowledgements: This dataset was provided to Kaggle by Hadi Fanaee Tork using data from Capital Bikeshare.


## Data Description
Hourly rental data spanning two years.
The training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. 


Data Fields
datetime - hourly date + timestamp  
season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 
holiday - whether the day is considered a holiday
workingday - whether the day is neither a weekend nor holiday
weather - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 
temp - temperature in Celsius
atemp - "feels like" temperature in Celsius
humidity - relative humidity
windspeed - wind speed
casual - number of non-registered user rentals initiated
registered - number of registered user rentals initiated
count - number of total rentals
