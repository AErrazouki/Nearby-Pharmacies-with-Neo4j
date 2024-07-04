# Project Description
This project aims to use Neo4j, a graph database, to detect the nearest pharmacies from a given location. By leveraging Neo4j's capabilities to model relationships between pharmacies and using geospatial tools to calculate distances, the project enables efficient and precise searches for nearby pharmacies.

# Objective
The primary objective of this project is to create an effective solution for identifying and visualizing nearby pharmacies using Neo4j's graph database. By representing pharmacies as nodes and utilizing relationships to represent distances between them, the project facilitates accurate proximity searches for pharmacies.

# Technologies Used
Neo4j: Graph database for modeling pharmacies and their relationships.

osmnx: Python library for downloading and visualizing geospatial data from OpenStreetMap.

geopandas: Python library for working with geospatial data.

networkx: Python library for creating, manipulating, and studying complex graph structures and dynamics.

geopy: Python library for geospatial calculations.

folium: Python library for creating interactive maps.

requests: Python library for making HTTP requests.

webbrowser: Python library for opening web browsers.

# Explanation of the Code
Connecting to Neo4j: Configuring the connection to the Neo4j database.

Creating Nodes: Modeling pharmacies as nodes in Neo4j with their geographical coordinates.

Creating Relationships: Calculating distances between pharmacies and modeling them as relationships between nodes.

Visualization: Using Folium to visualize pharmacies on an interactive map.
