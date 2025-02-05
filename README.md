# Advent Windows Romanshorn Map

This web map displays the locations of the Advent windows in the city of Romanshorn. The Advent window event is organized by [Jubla Romanshorn](https://www.jubla-romanshorn.ch/) and takes place every year from December 1st to December 24th.

## Contents

- **MapLibre Map**: A MapLibre map using vector tiles is used as the background map.
- **GeoJSON Data**: The locations of the Advent windows are embedded as points in GeoJSON format.
- **Advent Windows with/without Inauguration**: Advent windows are divided into two categories: with inauguration or without inauguration. For windows with an inauguration, the window is presented by the creator on a specific day and time, often accompanied by an aperitif.
- **Data Display**: The Advent windows are labeled with the days from December 1st to 24th and can be visited in person starting on the respective day.

## Project Page

The web map is live at: [Advent Windows Romanshorn](https://fabianrechsteiner.github.io/adventsfenster/)

[![Advent Windows Romanshorn Preview](https://github.com/user-attachments/assets/b8946955-f39b-4b99-83d7-c4b7f4739dbf)](https://fabianrechsteiner.github.io/adventsfenster/)

## Repository Structure

- `index.html`: The main file that embeds the MapLibre map and loads the GeoJSON file.
- `adventsfenster.geojson`: Contains the locations and information about the Advent windows (points and attributes such as with or without inauguration).

## Usage Instructions

1. Clone this repository:  
   ```bash
   git clone https://github.com/FabianRechsteiner/adventsfenster.git
2. Open the `index.html` file in your browser or use the provided GitHub Pages link.
