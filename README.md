# Mapping Earthquakes

## Project goal
The goal of this project is to visually show the differences between the magnitudes of earthquakes for the last seven days with circle markers. Tectonic plate fault lines and major earthquakes will also be shown.

## Method
1. Retrieve geogrpahical coordinates from GeoJSON earthquake data (USGS website) using JavaScript and D3.js library
2. Use leafelet library to plot data on a Mapbox map through an API request and create interactivity for the earthquake data
3. Overlay multiple types of map backgrounds (street, satellite streets, dark)
4. Include a filter element on map where user can select map background and type of data to visualize (all earthquakes, major earthquakes, and tectonic plates)

## Results

Fig. 1 shows the interactive webpage highlighting the modularity with multiple map backgrounds and data from which the user can choose.

<img width="551" alt="Screen Shot 2021-08-28 at 2 44 55 PM" src="https://user-images.githubusercontent.com/45336910/131227827-bd8622ca-6892-4f25-b915-1ec50d95d13d.png">


