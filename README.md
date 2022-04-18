# Groundwater-recharge-mapping-with-GEE
Implementation of the Thornthwaite-Mather procedure to map groundwater recharge in Rwanda.
This procedures relies on several parameters and variables described as follows:
1. information about soil texture (e.g. sand and clay content) to describe the hydraulic properties of the soil and its capacity to store/infiltrate,
2. meteorological records: precipitation and potential evapotranspiration.

Datasets used:
1 OpenLandMap datasets
2 Evapotranspiration and precipitation datasets

A function will be defined to resample the time resolution of an ee.ImageCollection and to homogenize time index of both datasets. Both datasets will then be combined into one.

In the fourth and final part, the Thornthwaite-Mather(TM) procedure will be implemented by iterating over the meteorological ee.ImageCollection. Finally, a comparison between groundwater recharge in two places will be described and the resulting mean annual groundwater recharge will be displayed over Rwanda
