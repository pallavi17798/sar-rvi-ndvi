# Crop Stage Detection and Prediction

This project utilizes Google Earth Engine (GEE) to analyze satellite imagery from Sentinel-1 and Sentinel-2 for agricultural applications, specifically to calculate the Radar Vegetation Index (RVI) and the Normalized Difference Vegetation Index (NDVI). These indices are helpful in monitoring crop health and estimating yield.

## Overview

The project involves:
- Accessing and filtering Sentinel-1 and Sentinel-2 image collections.
- Calculating the RVI (Radar Vegetation Index) from Sentinel-1 data.
- Calculating the NDVI (Normalised Difference Vegetation Index) from Sentinel-2 data.
- Visualizing the results on a map using geemap.

## Key Features

- **RVI Calculation**: Computes RVI for each image in the Sentinel-1 collection and generates a mosaic if multiple tiles are present.
- **NDVI Calculation**: Computes NDVI for each image in the Sentinel-2 collection and generates a mosaic.
- **Visualization**: Displays RVI and NDVI images on an interactive map with a manual legend with the help of geemap library.

## Dependencies

- [Google Earth Engine](https://earthengine.google.com/)
- [geemap](https://geemap.org/)
- [NumPy](https://numpy.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciPy](https://www.scipy.org/)

## Setup

1. **Install Required Libraries**:
   Ensure you have the required libraries installed in your Python environment. You can install them using pip:

   ```bash
   pip install geemap earthengine-api tensorflow numpy pandas scipy
