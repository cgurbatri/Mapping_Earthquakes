# Mapping Earthquakes

## Project goal
The goal of this project is to visually show the differences between the magnitudes of earthquakes for the last seven days with circle markers. Tectonic plate fault lines and major earthquakes will also be shown.

## Method
1. Retrieve geogrpahical coordinates from GeoJSON earthquake data (USGS website) using JavaScript and D3.js library
2. Use leafelet library to plot data on a Mapbox map through an API request and create interactivity for the earthquake data
3. Overlay multiple types of map backgrounds (street, satellite streets, dark)
4. Include a filter element on map where user can select map background and type of data to visualize (all earthquakes, major earthquakes, and tectonic plates)

