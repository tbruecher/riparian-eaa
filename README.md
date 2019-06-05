# Calculating Riparian Zones
Calculating riparian zones within the Contributing and Recharge Zones of the Edwards Aquifer using the Riparian Zone Buffer Dileniation Model v3.0

### What is a riparian zone?
>"...a three-dimensional space of interaction that includes terrestrial and aquatic ecosystems that extend down into the groundwater, up above the canopy, outward across the floodplain, up the near-slopes that drain to the water, laterally into the terrestrial ecosystem, and along the water course at a variable width"
>
>(Ilhardt et al., 2000)

### Model Inputs
* [Streams, lakes, and watersheds](http://nhd.usgs.gov/) 
* 50-year flood height
* [Wetlands](https://www.fws.gov/wetlands/Data/Data-Download.html)
* [Soil](https://www.nrcs.usda.gov/wps/portal/nrcs/main/soils/survey/)
* [Elevation](http://ned.usgs.gov/)
* [Landcover](https://www.mrlc.gov/)

### Data Preparation
* Hydrologic Estimation
  * _Download "Annual Statistics" and "Field Measurements" data from the USGS stream gages_
  * _Calculate the 50-year flood height using the Hydrologic Estimation.xlsm file developed by Mason (2007) and Bedient & Huber (2002)_
* NHD
  * _The Streams attribute table should have a "StreamLeve" field_
  * _Correct NHD stream locations using aerial imagery_
* Soils
  * _Prepare soil layers using the Soil Data Viewer extension for ArcGIS Desktop_
* Model File Geodatabase
  * _The geodatabase should only contain the prepared data_
  
### Run the Model
Download the model at http://www.sfi.mtu.edu/muses/GIS_Riparian.htm

#### Referenced Presentation
http://proceedings.esri.com/library/userconf/proc15/papers/85_746.pdf
