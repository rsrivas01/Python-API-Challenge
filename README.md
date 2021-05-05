# What's the Weather Like?
*[Python library](https://pypi.org/project/citipy/) and [OpenWeatherMap API](https://openweathermap.org/api) were used to complete this assignment*

### WeatherPy and VacationPy

__WeatherPy:__
  - Create a Python script to visualize the weather of 500+ cities across the world
  - Create a series of scatter plots:
      - Temperature (F) vs. Latitude
      - Humidity (%) vs. Latitude
      - Cloudiness (%) vs. Latitude
      - Wind Speed (mph) vs. Latitude
  - Run linear regression on each relationship, Northern Hemisphere and Southern Hemisphere:
      -  Northern Hemisphere - Temperature (F) vs. Latitude
      -  Southern Hemisphere - Temperature (F) vs. Latitude
      -  Northern Hemisphere - Humidity (%) vs. Latitude
      -  Southern Hemisphere - Humidity (%) vs. Latitude
      -  Northern Hemisphere - Cloudiness (%) vs. Latitude
      -  Southern Hemisphere - Cloudiness (%) vs. Latitude
      -  Northern Hemisphere - Wind Speed (mph) vs. Latitude
      -  Southern Hemisphere - Wind Speed (mph) vs. Latitude


__VacationPy:__

*Using jupyter-gmaps and the Google Places API for this part of the assignment*
  - Create a heat map that displays the humidity for every city
  - Narrow down the DataFrame to find the ideal weather condition
      - A max temperature lower than 80 degrees but higher than 70.
      - Wind speed less than 10 mph.
      - Zero cloudiness.
      - Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
  - Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates
  - Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country

### Concluded Observation

  - Temperatures tend to be warmer closer to the equator. The current data shows that its warmer to the northern hemisphere, month of August. Make sense because its summer season for the northern hemisphere.
  - We can also see more humidity count in the northern hemisphere. Along the latitude most of the humidity percent range between 60 – 100.
  - It seems that there is no relation between cloudiness and latitude. There’s seems to be a lot of gathering of scatters at 0, 40, and between 80 – 100%
  - There’s seem to be no relation between wind speed and latitude. Generally, wind speed tend to stay below 15 mph.
