# NDWI_Lake_Bosomtwi_Evolution

### NDWI Analysis of Lake Bosomtwe (2018 vs. 2022):
This repository contains a Google Earth Engine (GEE) script to monitor surface water changes in Lake Bosomtwe, Ghana, using Sentinel-2 satellite imagery.

### Overview:
The analysis utilizes the Normalized Difference Water Index (NDWI) to delineate open water bodies. By comparing data from the latter halves of 2018 and 2022, the script calculates the total surface area (km²) and determines the absolute change over time.

### Key Features:
Satellite Data: Copernicus Sentinel-2 (Level-1C).
Index: NDWI using Green (B3) and NIR (B8) bands.
Cloud Masking: Automatically selects the least cloudy image within the specified date range.
Exports: Generates RGB, NDWI, and Binary Mask images directly to Google Drive.

### How to Use:
Open the Google Earth Engine Code Editor.
Copy the contents of "GEE Code" from this repo into the editor.
Click Run to see the layers and the calculated area in the Console.
Check the Tasks tab to export the processed imagery.

### Results:
The script outputs the following to the GEE console:
Number of images available per period.
Specific date of the image used for analysis.
Calculated water area (km²) for 2018 and 2022.
The absolute difference in lake surface area.

### Data Source & License:
Data: Copernicus Sentinel-2 courtesy of ESA/European Union.
Code License: MIT License — Feel free to use and adapt this for your own research.
