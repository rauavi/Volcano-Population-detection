# Volcano and Population Map

This project uses Python and the Folium library to create an interactive map displaying the locations of volcanoes and population data.

## Features

- **Volcano Markers**: The map includes markers for volcanoes, with the location data being pulled from a CSV file. The markers are color-coded based on the elevation of the volcano: green for less than 1000m, orange for 1000m to 3000m, and red for above 3000m.
- **Population Overlay**: There is also a population overlay, which colors countries based on their population: green for less than 10 million, orange for 10 million to 20 million, and red for above 20 million.

## Libraries Used

- [Folium](https://python-visualization.github.io/folium/): For creating the map and adding the markers and overlays.
- [Pandas](https://pandas.pydata.org/): For reading and processing the data from the CSV file.

## How to Run

1. Ensure you have Python installed and the necessary libraries (Folium and Pandas).
2. Run the Python script (`your_script_name.py`).
3. Open the generated `Map1.html` file in a web browser to view the map.

Please note that you need to have the `Volcanoes.txt` and `world.json` files in the same directory as your Python script for it to run correctly.
```
