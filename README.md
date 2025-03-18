# NorthernLapwing-habitatSelection

## Master thesis: Habitat selection of the northern lapwing (Vanellus vanellus) during breeding season in Europe.
## Author: Lady Johanna Esguerra Montaña
#### Afiliation: Hochschule für technik stuttgart & BIOECOS (Biodiversity & Ecosystem Services) research group from Helmholtz Centre for Environmental Research – UFZ
#### Abstract:This repository compiles code and sample data used in the methodology developed in the context of the master’s thesis: Habitat selection of the northern lapwing (Vanellus vanellus) during breeding season in Europe. The study aimed to analyze how landscape structure influences the species’ habitat selection during the breeding season. Its purpose is to share these resources and facilitate their application in other studies.

### Coding: Landscape metrics and step-selection function (SSF) implementation 

localContagionIndex.py: This Python-developed code calculates the Contagion Index from a land use and land cover raster. It analyzes the spatial distribution of classes in the raster and quantifies the degree of aggregation of the present categories. The output is a new raster with the computed index values.

localMeanPatchAreaIndex.py: Developed in Python, this code calculates the Mean Patch Area Index from a land use and land cover raster. It analyzes the average patch size within each category to quantify landscape fragmentation. The result is a new raster with the computed index values.

localShannonIndex.js: This JavaScript code, developed in Google Earth Engine, calculates the Shannon Index from a land use and land cover raster. It analyzes the distribution of classes in the study area and measures landscape heterogeneity. The result is a new raster with the computed index values.

implementationSSFmodel.R: This R code implements Step Selection Function (SSF) models to analyze habitat selection based on individual movement data. It generates random steps from observed locations and fits statistical models to assess the influence of environmental variables, including landscape metrics, on path choice. The output includes model coefficient estimates and goodness-of-fit metrics.

Local approach: The landscape metrics code uses moving windows, allowing for the assessment of landscape variability and structure at a local scale. This approach considers a defined area around each cell in the raster, capturing spatial patterns based on the immediate context of each analyzed point.


### Sample data: 

CONTAG_sample.tif: Sample of the computed Contagion index raster.

DEM_sample.tif: Sample of Digital Elevation Model (DEM) Copernicus GLO-30.

LULC_sample.tif: Sample of land use and land cover dataset Dynamic World.

MPA_sample.tif: Sample of the computed mean patch area index raster.

SHDI_sample.tif: Sample of the computed Shannon diversity index raster.

trackingData_sample.shp: Point-geometry shapefile representing individual positions.

