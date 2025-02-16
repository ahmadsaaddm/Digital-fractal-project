# Mobility Data Analysis in Madrid

## Overview
This project analyzes mobility data in Madrid using various spatial analysis techniques and machine learning models. It leverages the `scikit-mobility` library to process trajectory data, filter noise, detect stay locations, and visualize results. The project integrates Google Maps API to retrieve points of interest (POIs) and applies DBSCAN clustering for mobility pattern detection.

## Features
- **Retrieval of POI Latitude and Longitude**: Uses Google Maps API to fetch coordinates of major locations in Madrid.
- **Mobility Data Preprocessing**: Cleans and processes raw mobility data, removing unnecessary columns.
- **Filtering and Compression**: Removes outliers based on speed constraints and compresses trajectories.
- **Stay Location Detection**: Identifies locations where users stay for extended periods.
- **DBSCAN Clustering**: Detects clusters in movement data .

## Installation
To run this project, install the required dependencies:

```sh
pip install pandas geopandas googlemaps folium numpy scikit-mobility scikit-learn branca




## Data Source
The data was a small sample from IRYS, the goal was to use Markov Diary algorithm to augment data and collect patterns 



