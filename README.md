# GEE Terrain Watershed Analysis

This repository contains the code developed for a project analyzing terrain and watershed classifications using Google Earth Engine (GEE). Inspired by the [Complete QGIS Watershed Delineation Tutorial](https://example.com/tutorial), our aim was to adapt and replicate the flood risk analysis process within GEE. Due to some platform limitations, it wasn't possible to replicate the workflow exactly. However, this code provides a foundational approach for extracting river data and watershed characteristics.

## Overview

The code in this repository:

- Classifies terrain using data from the SRTM (Shuttle Radar Topography Mission) model.
- Extracts key river metrics, including river shape and flow direction.
- Automatically identifies where rivers connect to larger watercourses, helping analyze watershed and flood-prone areas.

## Repository Structure

- **/Scripts**: Contains Google Earth Engine scripts for:
  - Terrain classification
  - Watershed and river flow analysis

## Requirements

- **Google Earth Engine**: This code is designed specifically for GEE, so you will need access to the platform.

## Results

This project enabled us to classify watershed boundaries and river flow paths effectively within GEE, despite its limitations in fully replicating QGIS-based flood risk analysis workflows. The extracted data provides insights into river shape, direction, and the hierarchy of watercourses within the watershed.

## Screenshots

![image](https://github.com/user-attachments/assets/c045bcb1-55c4-46d2-b2ec-64fb07986d74)

![image](https://github.com/user-attachments/assets/d5cac1f1-12e0-44f9-9c5f-2ab8edf78462)

![image](https://github.com/user-attachments/assets/f9742da0-bb7b-4b87-a56e-9ade2c59aa65)
