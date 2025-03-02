# Road Network Analysis and Spatial Databases

This repository contains two projects related to spatial data analysis and urban planning. The first project focuses on creating and analyzing a routable road network in Zhongguanchun, Beijing, using OpenStreetMap data and Python libraries such as OSMnx and NetworkX. The second project involves developing a spatial querying system to identify Points of Interest (POIs) such as ATMs and restaurants within a specified vicinity using Python libraries like Pandas, GeoPandas, and Shapely.

## Road Network Analysis Report

### Introduction
This project demonstrates the process of creating and analyzing a routable road network within the Zhongguanchun area in Beijing, China. The analysis includes data acquisition from OpenStreetMap, network analysis to determine the shortest path between two points, and visualization of the road network.

### Methodology
1. **Installation and Setup**: Python environment setup with necessary libraries (OSMnx, NetworkX, Matplotlib).
2. **Data Acquisition**: Road network data retrieved from OpenStreetMap using OSMnx.
3. **Network Analysis**: Shortest path computation using NetworkX's shortest path algorithm.
4. **Visualization**: Road network and shortest path visualized using OSMnx.

### Results
- **Shortest Path**: Computed shortest path between two arbitrary points.
- **Road Length Distribution**: Histograms showing the distribution of road lengths within the network.
- **Visualization**: Clear representation of the road network's complexity and the efficiency of the shortest path algorithm.

### Conclusion
This project successfully demonstrates the use of OSMnx and NetworkX in extracting and analyzing road networks from OpenStreetMap data. The findings highlight the practical applications of these tools in urban planning and transportation studies.

## Spatial Databases Report

### Introduction
This project provides an overview of a Python-based spatial querying system designed to identify specific Points of Interest (POIs) such as ATMs and restaurants within a specified vicinity. The system utilizes libraries like Pandas, GeoPandas, Shapely, Rtree, and Haversine for efficient spatial data management and querying.

### Objectives
1. Build an in-memory spatial database for POIs to support efficient spatial range and nearest neighbor queries.
2. Demonstrate the efficiency of spatial indexing in querying processes.
3. Identify the nearest ATM and count the number of restaurants within a specified distance from predefined points.

### Methodology
1. **Data Preparation**: Load POI data into a GeoDataFrame and construct a spatial index using the R-tree algorithm.
2. **Spatial Indexing**: Implement an index-building function for efficient spatial queries.
3. **Spatial Queries**: Develop functions for range queries and nearest neighbor searches.
4. **Efficiency Comparison**: Compare the performance of spatially indexed queries against brute-force approaches.
5. **Integration with Haversine Formula**: Calculate real-world distances between geographic coordinates.

### Results
- **Nearest ATM Query**: Identified the nearest ATM to the Central Building of BIT.
- **Range Query for Restaurants**: Counted the number of restaurants within 500 meters of the south door of BIT.
- **List of Restaurants**: Detailed list of restaurants within the specified range.

### Conclusion
The developed system efficiently utilizes spatial indexing and querying techniques to identify and analyze POIs within geographic data. The integration of the Haversine formula enhances the accuracy of distance calculations, ensuring the results are practical for real-world applications.

## Future Work
Future research could expand on these projects to include traffic data, pedestrian pathways, and other transport modes to create a more detailed and multifaceted analysis of urban mobility.
