# Mapping_Earthquakes

## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the past seven days, as well as see the earthquake data in relation to the location of tectonic plates on earth. 

## Approach
To complete this project, I used a URL for GeoJSON earthquake data from the U.S. Geological Survey Website to retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. I used JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I then used the Leaflet library to plot the data on a Mapbox map through an API request and create an interactive earthquake map.

## Deliverable Details
This map visually differentiates between earthquakes of magnitude less than 5, greater than 5, as well as greater than 6. The magnitude and location of each earthquake is shown as a popup marker and the diameters of the markers reflect the magnitude of the earthquake in their size and colour. Earthquakes with higher magnitudes appear larger and darker in colour. The legend provides the context for the markers. Finally, fault lines were added on the map to illustrate the relationship between the location and frequency of seismic activity and tectonic plates.

## File Description
- The Earthquake_Challenge folder
    - index.html
        - it contains the HTML code necessary to interact with the final user
        - references the .css, .js code contained in the static folder
      - static
      - css
        - style.css
          It contains all necessary information to format the index.html folder
      - js
        - challenge_logic.js
          It contains JavaScript code that interacts with the final user and shows the data used in the index file
