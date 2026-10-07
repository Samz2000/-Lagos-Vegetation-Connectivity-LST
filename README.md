# Lagos Vegetation Connectivity and Land Surface Temperature

Google Earth Engine remote sensing analysis of vegetation connectivity and land surface temperature in the Lagos Lekki–Ajah corridor.

## Project Overview

This project investigates the relationship between vegetation connectivity and land surface temperature (LST) within a selected area of the Lagos Lekki–Ajah corridor, Nigeria.

The analysis uses satellite remote sensing and Google Earth Engine to examine spatial patterns of vegetation connectivity and surface temperature.

## Study Area

The study focuses on the Lagos Lekki–Ajah corridor, an area experiencing rapid urban development and changes in land cover.

The selected study area was defined in Google Earth Engine and used as the spatial boundary for the analysis.

## Objectives

The main objectives of the project are to:

- Map vegetation and land-cover-related patterns within the study area.
- Assess vegetation connectivity across the study area.
- Estimate land surface temperature (LST).
- Compare LST across different vegetation connectivity classes.
- Explore the relationship between vegetation connectivity and surface temperature.

## Data and Tools

### Google Earth Engine

Google Earth Engine was used for:

- Satellite imagery processing
- Study-area definition
- Vegetation/connectivity analysis
- Land surface temperature processing
- Spatial classification
- Statistical analysis and visualization

### Satellite Remote Sensing

Satellite imagery was used to derive information about vegetation and surface temperature without direct field measurement.

### Python

Python was used as part of the project's data-processing and visualization workflow.

## Analysis Workflow

The project followed a workflow that included:

1. Defining the study area.
2. Preparing satellite imagery.
3. Processing vegetation-related information.
4. Deriving vegetation connectivity classes.
5. Calculating land surface temperature.
6. Comparing LST across connectivity classes.
7. Exporting results for further analysis.
8. Producing maps and charts to communicate the results.

## Land Surface Temperature Results

The analysis compared land surface temperature across three vegetation connectivity classes:

- Low connectivity
- Medium connectivity
- High connectivity

The resulting temperature ranges were extracted from the Google Earth Engine analysis and exported as a CSV dataset.

## Project Outputs

The repository contains the following outputs:

- GEE/ — Google Earth Engine scripts used for the analysis.
- Results/ — exported tabular results, including results.csv.
- figures/ — maps and charts generated from the analysis.
- GeoTIFF files — exported spatial raster outputs from Google Earth Engine.

## Figures

The figures/ directory contains visual outputs from the analysis, including:

- Study-area map
- Vegetation/connectivity-related map
- Land surface temperature map
- Statistical charts comparing connectivity and LST
- Additional analysis charts

## Key Findings

The analysis provides a spatial comparison of land surface temperature across vegetation connectivity classes within the selected Lagos study area.

The results can be used to investigate how vegetation structure and connectivity may relate to variations in surface temperature in a rapidly urbanizing environment.

## Skills Demonstrated

This project demonstrates practical experience with:

- Remote sensing
- Geographic Information Systems (GIS)
- Google Earth Engine
- Satellite imagery
- Land surface temperature analysis
- Vegetation/connectivity analysis
- Spatial data processing
- GeoTIFF raster outputs
- CSV data analysis
- Data visualization
- Python-assisted analysis

## Project Structure

Lagos_GEOAI/
│
├── GEE/
│   └── Google Earth Engine scripts
│
├── Results/
│   └── results.csv
│
├── figures/
│   ├── maps
│   ├── charts
│   └── .gitkeep
│
├── .tif / .tiff
│   └── exported raster outputs
│
└── README.md



## Future Improvements

Possible extensions of the project include:

- Incorporating additional years of satellite imagery.
- Examining seasonal changes in vegetation and LST.
- Testing additional vegetation and landscape metrics.
- Applying machine-learning approaches to land-cover classification.
- Investigating the relationship between urban expansion, vegetation loss and surface temperature.

## Author

Lagos GeoAI project developed as a practical remote sensing and geospatial analysis portfolio project.
