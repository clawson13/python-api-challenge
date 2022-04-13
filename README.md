WeatherPy & VacationPy

Homework for Boot Camp Week 6: Python-APIs; Submitted by Corey Lawson-Enos

## Summary
* WeatherPy: Study compares geographical latitude's effect on four weather categories--Temperature, Humidity, Cloudiness, and Wind Speed. Includes Northern/Southern hemisphere comparison.
* VacationPy: Vacation planner for 500+ cities worldwide selected at random. Cites are mapped according to humidity level, including a final map with hotel pins for each city within temperate zone of 70-80&deg F, wind speed less than 10 mph, and zero cloudiness.  

## Technologies
Google Maps, OpenWeatherMap API, citipy, Matplotlib, Pandas, Jupyter Notebook

## Additional Analysis
* Latitude did not show significant relationship to Humidity, Cloudiness, and Wind Speed categories. Sample humidity plot: 

![alt text](https://github.com/clawson13/python-api-challenge/blob/0bfb9434e4ecd2b0e2b83335a9e208d2540a885d/Images/Lat_v_Humidity.png)

* Although northern latitude change shows a strong link to temperature, the tie is much weaker in the South; as such, it cannot be construed from the dataset generated that latitude is the only contributing factor to global temperature variance.

![alt text](https://github.com/clawson13/python-api-challenge/blob/0bfb9434e4ecd2b0e2b83335a9e208d2540a885d/Images/Lat_v_Temp_South.png)

* Interactive Google Map displays VacationPy's plotted cities colored by humidity level:

![alt text](https://github.com/clawson13/python-api-challenge/blob/0bfb9434e4ecd2b0e2b83335a9e208d2540a885d/Images/Heat_Map.html)
