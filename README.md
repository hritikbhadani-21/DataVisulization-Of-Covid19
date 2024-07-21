# DataVisulization-Of-Covid19
Objective: The goal of this project is to create an interactive web-based visualization of COVID-19 data globally using the Folium library in Python. This visualization will provide insights into the geographical distribution and trends of COVID-19 cases across different countries.
Data Sources:
COVID-19 Data:

The dataset includes COVID-19 case statistics by country, with information such as confirmed cases, recoveries, and fatalities. The data is structured with columns representing dates and regions.
Geospatial Data:

The project utilizes a GeoJSON file containing the geometries of world countries to visualize data on a global map.
Features Implemented:
Choropleth Map:

A Choropleth map is created to represent the intensity of COVID-19 cases across different countries. The map uses color gradients to illustrate variations in the number of confirmed cases.
Circle Markers:

Circle markers are added to represent specific data points on the map. Each marker is placed at the coordinates of COVID-19 cases and can display additional information, such as the number of confirmed cases or recoveries, when clicked.
