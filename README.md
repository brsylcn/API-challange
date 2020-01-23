# WEATHER DATA ANALYZE
## EXECUTIVE SUMMARY
599 raws of data is available. 43 raws of data is ignored since there are missing values. 556 raws of data that includes cities with their maximum temperature, humidity, cloudiness and wind speed values. Data is retrieved on 01/19/2020.
## DATA LIMITATIONS
According to the data (http://phl.upr.edu/library/notes/distributionoflandmassesofthepaleo-earth), the distrubition of the total Earth is not even between Northern Hemisphere and Southern Hemispeher.(68% located in Southern, 32% located in Northern). It basically means that less cities are generated for Northern Hemisphere for the comparision.
## TOOLS & METHODS USED
Across the world, random cities are generated by using Citipy method. Citipy is a library to randomly select the nearest cities accorfding ot the locations.

Open Weather API is used to retrieve real time values of temperature, humidity, cloudiness and wind speed for these cities with geo coordinates if their data is available on Open Weather API..

Pandas/Matplotlib/Python/Numpy/Seaborn

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
## ANALYSIS & CONCLUSIONS

![Image description]()
