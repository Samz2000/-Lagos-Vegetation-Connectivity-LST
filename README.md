# Lagos Vegetation Connectivity and Land Surface Temperature

Google Earth Engine remote sensing analysis of vegetation connectivity and land surface temperature in the Lagos Lekki–Ajah corridor, Nigeria.

## Project Overview

This project investigates the relationship between vegetation connectivity and land surface temperature (LST) within a selected area of the Lagos Lekki–Ajah corridor, Nigeria.

The analysis uses satellite remote sensing and Google Earth Engine to examine spatial patterns of vegetation connectivity and surface temperature.

## Study Area

The study focuses on a selected area within the Lagos Lekki–Ajah corridor, an area experiencing urban development and changes in land cover.

The study area was defined in Google Earth Engine and used as the spatial boundary for the analysis.

## Objectives

The main objectives of the project are to:

- Map vegetation-related patterns within the study area.
- Assess vegetation connectivity across the study area.
- Estimate land surface temperature (LST).
- Compare mean LST across different vegetation connectivity classes.
- Explore the observed relationship between vegetation connectivity and surface temperature.

## Data and Tools

### Google Earth Engine

Google Earth Engine was used for:

- Study-area definition
- Satellite imagery processing
- Vegetation-related analysis
- Vegetation connectivity classification
- Land surface temperature processing
- Spatial analysis
- Results extraction and visualization

### Satellite Remote Sensing

Satellite imagery was used to derive information about vegetation and land surface temperature without direct field measurement.

### GIS

Geographic Information System (GIS) concepts were used to define, organize, analyze, and visualize spatial data within the study area.

## Analysis Workflow

The project followed a workflow that included:

1. Defining the study area.
2. Preparing satellite imagery.
3. Processing vegetation-related information.
4. Deriving vegetation connectivity classes.
5. Calculating land surface temperature.
6. Comparing mean LST across connectivity classes.
7. Calculating temperature differences relative to the high-connectivity class.
8. Exporting the results as CSV and GeoTIFF files.
9. Producing maps and charts to communicate the results.

## Land Surface Temperature Results

The analysis compared mean land surface temperature across three vegetation connectivity classes.

- Low connectivity: 32.0°C
- Medium connectivity: 30.5°C
- High connectivity: 29.2°C

The high-connectivity class was used as the reference for calculating temperature differences.

- Low connectivity: 2.8°C warmer than high connectivity
- Medium connectivity: 1.3°C warmer than high connectivity
- High connectivity: 0.0°C difference

## Project Outputs

The repository contains:

- GEE/ — Google Earth Engine scripts used for the analysis.
- Results/ — exported tabular results, including results.csv.
- figures/ — maps and charts generated from the analysis.
- .tiff/ — exported GeoTIFF raster outputs.
- README.md — project documentation.

## Figures

The figures/ directory contains visual outputs from the analysis, including:

- Study-area maps
- Vegetation/connectivity maps
- Land surface temperature visualizations
- Charts comparing vegetation connectivity and LST
- Additional charts generated during the analysis

## Results and Interpretation

The analysis shows an observed association between vegetation connectivity and land surface temperature within the selected study area.

Low-connectivity areas recorded the highest mean LST at 32.0°C, while high-connectivity areas recorded the lowest mean LST at 29.2°C.

Low-connectivity areas were approximately 2.8°C warmer than high-connectivity areas, while medium-connectivity areas were approximately 1.3°C warmer.

The results suggest that areas with higher vegetation connectivity were associated with lower mean surface temperatures in this analysis.

These findings represent the results of this project analysis and should not be interpreted as proof that vegetation connectivity alone causes the observed temperature differences.

## Key Findings

- Low connectivity: 32.0°C mean LST.
- Medium connectivity: 30.5°C mean LST.
- High connectivity: 29.2°C mean LST.
- Low-connectivity areas were 2.8°C warmer than high-connectivity areas.
- Medium-connectivity areas were 1.3°C warmer than high-connectivity areas.
- The analysis identified an observed relationship between vegetation connectivity and surface temperature.

## Skills Demonstrated

This project demonstrates practical experience with:

- Remote sensing
- Geographic Information Systems (GIS)
- Google Earth Engine
- Satellite imagery processing
- Land surface temperature analysis
- Vegetation/connectivity analysis
- Spatial data processing
- Raster data and GeoTIFF outputs
- CSV data analysis
- Data visualization

## Project Structure

- GEE/ — Google Earth Engine scripts
- Results/ — Contains results.csv
- figures/ — Maps and charts from the analysis
- .tiff/ — Exported GeoTIFF raster outputs
- README.md — Project documentation

## Future Improvements

Possible extensions of the project include:

- Incorporating additional years of satellite imagery.
- Examining seasonal changes in vegetation and LST.
- Testing additional vegetation and landscape metrics.
- Applying machine-learning approaches to land-cover classification.
- Investigating the relationship between urban expansion, vegetation loss, and surface temperature.

## Author

Lagos GeoAI project developed as a practical remote sensing and geospatial analysis portfolio project.


