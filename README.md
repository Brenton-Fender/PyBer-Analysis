# PyBer-Analysis


## Project Overview
As a new employee at PyBer, I have been assigned the task of analyzing PyBer's rideshare data. I will provide the CEO, V. Isualize, with a summary in DataFrame and written form in addition to an accompanying multi-line graph compiled with Matplotlib.


## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.10.5, Jupyter Notebook 6.4.8
 
## Results
Grouping the data by city type (Urban, Suburban, Rural) showed that the more densely populated the city type, the more rides, drivers, and total fares. Higher density of the city type also returned a lower average fare per ride and driver. These correlations were true for every week of the final analysis. 


![PyBer_fare_summary](https://user-images.githubusercontent.com/105960365/200393502-e4f0edab-f5aa-4eba-ad39-2f0fd18d33fd.png)


## Summary
The positive correlation of population density with drivers and usage was expected. With a significantly increased user demand, it would be projected that the number of drivers needed to fill this demand would also increase. However, by calculating an extra statistic that showed the number of riders per driver, I can show that for only urban cities there are more drivers than rides. This would negatively affect the average fare per driver in urban cities. It would be beneficial to PyBer to do this same analysis without inactive drivers. The negative correlation of population density with average fare per ride and driver could probably be further explained if data for distance per ride was provided. 
