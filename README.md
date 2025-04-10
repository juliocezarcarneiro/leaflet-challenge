# leaflet-challenge: Visualizing USGS Earthquake Data

## Overview
This project involves creating an interactive map to visualize earthquake data provided by the United States Geological Survey (USGS).

## Table of Contents
1. Overview
2. Technologies Used
3. Features
4. Setup Instructions
5. Steps to Reproduce the Project
6. Project Structure
7. References

### Technologies Used
- **Leaflet.js**: For creating the interactive map.
- **D3.js**: For fetching and parsing GeoJSON data.
- **HTML/CSS**: For structuring and styling the visualization.

### Features
- **Interactive Map**: Displays earthquake data from the USGS.
- **Data Markers**: Size corresponds to earthquake magnitude and color represents earthquake depth.
- **Popups**: Click on any marker to view additional details about the earthquake.
- **Legend**: Provides context for the color scale used to represent earthquake depth.

## Setup Instructions

1. Clone this repository to your local machine: git clone https://github.com/your-username/leaflet-challenge.git

## Steps to Reproduce the Project
1. Open `Leaflet-Part-1/index.html` in a browser
2. The map automatically loads the latest USGS data
3. Interact with the map:
   - Click markers for details
   - Navigate between OpenStreetMap and Humanitarian (HOT)
   - Use the legend to interpret depth colors

## Project Structure
The repository is organized as follows:

## /leaflet-challenge

- **LICENSE.txt**
- **README.md**

- **/Leaflet-Part-1**
  - **index.html**
  - **/static**
    - **/css**
        - **style.css**
    - **/js**
        - **logic.js**

## References

* Data Source: [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).

* ChatGPT: for brainstorming, clarification and coding assistance.

* USGS Earthquake Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php.

* Leaflet.js: open-source JavaScript library for interactive maps. https://leafletjs.com/.

* D3.js: https://d3js.org/.

* OpenStreetMap: OpenStreetMap. https://www.openstreetmap.org/.

* Humanitarian (HOT) Layer: https://www.hotosm.org/.
