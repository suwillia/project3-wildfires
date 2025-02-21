#U.S. Wildfires Data Visualization
## **Description**

This project provides an **interactive visualization** of U.S. wildfire data using a **Flask API and Leaflet.js**. Users can query wildfire data and visualize fire occurrences on an interactive heatmap.

---
## Summary
🔥 Part 1: Flask API for Wildfire Data
The backend serves wildfire data stored in a local JSON file (USGS2014.json). The API allows filtering wildfire records by:

State
Year
Fire Size
Cause
County
Fire Name
Key API Endpoints:
Endpoint	Description	Example
/search	Retrieve wildfire data with optional filters.	/search?state=CA&year=2020
/years	Get a list of available years in the dataset.	/years


 Part 2: Interactive Heatmap with Leaflet.js
The front end uses Leaflet.js to generate an interactive wildfire heatmap. Users can filter wildfires by year and state and visualize their distribution on the map.

Key Features:
Dropdown filters for state and year.
Heatmap visualization with color intensity based on fire size.
Popups displaying fire details (fire name, acres burned, cause, etc.).
