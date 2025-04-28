# Earthquakes-Heatmap-Animation

![Earthquake Heatmap Animation](Earqthauakes.gif)

This project visualizes earthquake data from 1990 to 2023 in India using QGIS. The data is presented in the form of a heatmap density overlaid on a CartoDB Dark Matter base map. An animated GIF showcases the occurrence of earthquakes over the years, with the title indicating the year at each point in the animation.

## Project Overview

- **Data**: Earthquake data from 1990 to 2023, focusing on locations in India.
- **Tools Used**: 
  - **QGIS**: For spatial analysis and visualization.
  - **CartoDB Dark Matter**: As the base map for visualization.
  - **Heatmap**: For visualizing earthquake density.
  - **Animation**: Created within QGIS and exported as a GIF to showcase earthquake trends over time.
  
## Features

- **Heatmap Density**: Shows the intensity of earthquakes over the years.
- **Animation**: Displays a timeline of earthquakes from 1990 to 2023, with each frame representing a year and the year displayed as the title in the middle of the map.
- **Data Source**: Earthquake data filtered from global datasets to focus on Indian earthquake events.
- **Visual Representation**: The CartoDB Dark Matter base map provides a contrasting background for better visual clarity.

## Files Included

- **earthquake_heatmap.gif**: Animated GIF showing the earthquake heatmap from 1990 to 2023.
- **QGIS Project (.qgs)**: The QGIS project file used to create the heatmap and animation.
- **Earthquake CSV Data**: Original earthquake data (CSV) used for the project.

## How to Use

1. Download or clone the repository to your local machine.
2. Open the QGIS project file (`.qgs`) in QGIS to view the full map and the heatmap layers.
3. You can modify the project by importing your own earthquake data or changing the visualization styles.
4. Open the animated GIF (`earthquake_heatmap.gif`) to view the earthquake occurrences over time.

## How to Run the Project Locally

If you want to work with the QGIS project locally:
1. Install [QGIS](https://qgis.org) if you don't already have it.
2. Open the QGIS project file (`earthquake_heatmap.qgs`).
3. The CSV earthquake data should automatically load. If not, make sure to add it manually under the "Layers" section.

## Contributing

Feel free to fork the repository, open issues, or submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [CartoDB](https://carto.com/) for the Dark Matter base map.
- Thanks to the global earthquake data providers for making this data available.
