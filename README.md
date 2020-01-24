# WEATHER DATA ANALYZE
***Baris Yalcin- Data Science Bootcamp Student- Southern Methodist University***
## EXECUTIVE SUMMARY
599 raws of data is available. 43 raws of data is ignored since there are missing values. 556 raws of data that includes cities with their maximum temperature, humidity, cloudiness and wind speed values. Data is retrieved on 01/19/2020.
## DATA LIMITATIONS
According to the data (http://phl.upr.edu/library/notes/distributionoflandmassesofthepaleo-earth), the distrubition of the total Earth is not even between Northern Hemisphere and Southern Hemispeher.(68% located in Southern, 32% located in Northern). It basically means that less cities are generated for Northern Hemisphere for the comparision.
## TOOLS & METHODS USED
Across the world, random cities are generated by using Citipy method. Citipy is a library to randomly select the nearest cities according to the locations.

Open Weather API is used to retrieve real time values of temperature, humidity, cloudiness and wind speed for these cities.

Pandas/Matplotlib/Python/Numpy/Seaborn

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
## ANALYSIS & CONCLUSIONS
##### MAX TEMPERATURE Vs. LATITUDE
When we look at the plot bar, we can realize that the trand located closer to the equator (lat=0) gets increased temperature. However there are some exceptions if we check the cities are not located on the equator. On both Southern and Northern Hemispehere have some cities havin higher temperature than the cities are located on 0 latitude. That basically means distance from the equator is not only reason for high temperature.

![Max_Temp](https://github.com/brsylcn/API-challange/blob/master/WeatherPy/01_MaxTemp_Latitude.png)

##### CLOUDINESS Vs. LATITUDE
When we look at the scatter plot below, it is almost imposible to see any correlation  between cloudiness and latitude. Simply, we can assume that the amount of cloudiness is independent from that comparision.

![Cloud](https://github.com/brsylcn/API-challange/blob/master/WeatherPy/03_Cloudiness_Latitude.png)

##### HUMIDITY Vs. LATITUDE
When we check the figure below, we can say that the cities which having highest humidity are located between lat 20 and 60. Even though, latitude from 0 to 20 has the cities having the lowest humidty. According to our comparision, distance from equator might have some effect on the value of humidity. 

![Humid](https://github.com/brsylcn/API-challange/blob/master/WeatherPy/02_Humidity_Latitude.png)
