# NDVI Calculation and Plant Phenology Analysis 

## Purpose
This repository contains a presentation-ready markdown file in which I analyze plant phenology near the Santa Clara River which flows from Santa Clarita to Ventura. The purpose of this project is to calculate seasonal trends of plants and to analyze their phenology. I do so by generating a time series of Landsat imagery and polygons identifying the locations of study sites within each plant community 

## Data Access
To access the  data used for the project, please unzip this [folder](https://drive.google.com/file/d/1e9ZwWoC6kmqy5r7WtDOkabYa02jMx_sd/view?usp=sharing).

Because of the large size of the data folder, I added it to the `.gitignore` file in order to avoid pull/push errors. 


## Repository Structure
```
C:
|   .gitignore
|   eds-223-ndvi-calculation.Rproj
|   ndvi-calculation.html
|   ndvi-calculation.Rmd
|   README.md
|
\---data
    |   landsat_20180612.tif
    |   landsat_20180815.tif
    |   landsat_20181018.tif
    |   landsat_20181103.tif
    |   landsat_20181103.tif.aux.xml
    |   landsat_20190122.tif
    |   landsat_20190223.tif
    |   landsat_20190412.tif
    |   landsat_20190701.tif
    |   study_sites.dbf
    |   study_sites.prj
    |   study_sites.shp
    |   study_sites.shx
    |
    \---__MACOSX
            ._landsat_20180612.tif
            ._landsat_20180815.tif
            ._landsat_20181018.tif
            ._landsat_20181103.tif
            ._landsat_20181103.tif.aux.xml
            ._landsat_20190122.tif
            ._landsat_20190223.tif
            ._landsat_20190412.tif
            ._landsat_20190701.tif
```

## Final Output
![timeseries](https://github.com/mariamkg00/eds-223-ndvi-calculation/assets/105567684/f241bff0-66e2-446d-ba4b-9d0a3dac59a0)
