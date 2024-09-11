OVERVIEW

This project consists of multiple geospatial analysis tasks using Python and various geospatial data tools. The analysis covers a wide range of use cases, including earthquake analysis, identifying potential Starbucks Reserve Roastery locations, and optimizing hospital response times for traffic collisions in New York City.

PREREQUISITES:

To run this project, you'll need the following:

Python 3.8+
Jupyter Notebook
Installed Python libraries listed below (see Tools and Libraries Used)

DATA SOURCES:

The datasets used in the project include:

1. Earthquake Depth and Magnitude Data: Global earthquake data including depth and magnitude for analysis.
   
2. California Starbucks Locations: Starbucks stores in California and relevant demographic data such as population, median age, and household income.
   
3. NYC Motor Vehicle Collisions Data: Collision data from 2013-2018, including crash locations and proximity to hospitals.
   
4. Hospitals in NYC: Hospital location data to analyze response times for crashes.
   
PROJECT TASKS:

1. Earthquake Depth Analysis
Goal: Explore global patterns in earthquake depth and analyze how depth varies across regions, particularly in Japan.

Tools Used: Folium, GeoPandas, Pandas.
Key Steps:
Visualize earthquake depth globally using a base map with tectonic plate boundaries.
Use choropleth maps to show the distribution of earthquake depth in Japan.
Analyze earthquake magnitude and density to suggest prefectures in Japan that may benefit from earthquake reinforcement efforts.

2. Starbucks Location Analysis in California
Goal: Analyze demographic data in California counties to identify potential locations for a Starbucks Reserve Roastery.

Tools Used: Folium, GeoPandas, Pandas.
Key Steps:
Load Starbucks location data and demographic data for California counties.
Create choropleth maps to visualize population density, high-income earners, and median age.
Filter counties that meet specific demographic criteria for a Reserve Roastery location.
Visualize Starbucks locations in the selected counties.

3. Hospital Response to Collisions in New York City
Goal: Identify how hospitals in NYC respond to major motor vehicle collisions and create a recommendation system for the nearest hospital to crash sites.

Tools Used: Folium, GeoPandas, Pandas, Shapely.
Key Steps:
Load and visualize motor vehicle collision data.
Identify collisions that occurred more than 10 kilometers away from the nearest hospital.
Build a recommendation system that suggests the closest hospital for any given collision.
Visualize the recommended hospitals on a map for each collision.

TOOLS AND LIBRARIES USED:

Python 3.8+
Jupyter Notebook
Pandas: Data manipulation and analysis.
GeoPandas: Handling and processing of geospatial data.
Folium: Interactive map visualization.
Shapely: Manipulating and analyzing planar geometric objects.
Geopy: Geocoding and reverse geocoding.
Matplotlib: Data visualization.
Fiona: Reading and writing vector data (shapefiles).
Pyproj: Coordinate system transformations.
