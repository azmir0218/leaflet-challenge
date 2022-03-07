# USGS Map Using Leaflet

### Background
Welcome to the United States Geological Survey, or USGS for short. The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

### Task

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. We visited the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and picked a data set to visualize. We will use the URL of this JSON to pull in the data for our visualization.

**Import & Visualize the Data**

   We created a map using Leaflet that plots all of the earthquakes from our data set based on their longitude and latitude.

   * Our data markers should reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

<img width="592" alt="Screen Shot 2021-10-28 at 6 29 10 PM" src="https://github.com/leaflet-challenge/blob/main/Images/2-BasicMap.png">


   * **HINT:** The depth of the earth can be found as the third coordinate for each earthquake.

   * We included popups that provide additional information about the earthquake when a marker is clicked.

   * We created a legend that will provide context for your map data.

   * Our visualization should look something like the map above.
