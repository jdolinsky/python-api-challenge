# Weather Analysis
What is the weather like as we approach the equator? This research is broken down into two deliverables: [WeatherPy](WeatherPy/WeatherPy.ipynb) and [VacationPy](VacationPy/output_data). The first deliverable creates plots to showcase the relationship between weather variables and latitude. The second deliverable, first, finds a list of cities that satisfy a personal preference for the "perfect vacation" weather conditions. Then, for each city, a hotel is located within 10,000 meters of its coordinates. Finally, a map is created to display a point for each city with the information about the current weather conditions, country and hotel name. 

## Data Source
A csv file [cities.csv](WeatherPy/output_data/cities.csv) is used for the research.  City name and lat lon were acquired using citipy library. The additional data for the weather variables was pulled from OpenWeatherMap API and the hotels were added using Geoapify API. 

## Technologies
Python, Python libraries: pandas, matplotlib, scipy, numpy, hvplot, and Jupyter Notebook.