# narok-NDVI
GEE NDVI determination
Here's a Google Earth Engine (GEE) script that performs a time series analysis over your highlighted area (table). 
It extracts and plots NDVI (Normalized Difference Vegetation Index) trends using Landsat 8 data over time.
This script:

Filters Landsat 8 imagery over your area (table).
Computes NDVI for each image.
Extracts and plots mean NDVI over time using ui.Chart.feature.byFeature().
Displays the latest composite image for visualization.
