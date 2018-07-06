# GSWP3.DataDescription
Description of GSWP3 Forcing Data

## Dimensions
+ Time: 3-hourly (hours since 1871-01-01 00:00:00)
+ Latitude: 0.5 degree 


## Versions

### 1.0 _@2018-07-06_
+ change variable naming convention: amip_name [wss] -> [sfcWind]
+ release for LS3MIP land_hist experiment

### 1.05 _@2018-02-17_
+ time span extended up to 2014
+ fill wind values over ocean pixels with downscaled reanalysis
+ release for CRECENDO project

### 1.0 _@2017-06-01_
+ version 1 official release

### 0.9b _@2017-05-13_
+ correct bias of reference Prcp (GPCC v7) in early 20th Century
+ reproduce Rainf/Snowf corresponding to updated wind speed

### 0.8b _@2017-05-12_
+ correct wind using CRU-CL2.0

### 0.7b _@2014-10-15_
+ add netCDF description
+ beta version release

### 0.6b _@2014-07-18_
+ remove negative values of Qair

### 0.5b _@2014-06-22_ 
+ first beta release 
+ release for ISI-MIP2
