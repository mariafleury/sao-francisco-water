# sao-francisco-water
### accessing_netCDF_v2.ipynb
Reads in GRACE JPL files, which are in netCDF format, as an _xarray_ and uses shapefiles to clip the data to the São Francisco River basin and sub-basins, using the _regionmask_ package. Introduces geospatial averages, and compares GRACE's total water storage data to MapBiomas' water surface area time-series. Data files used in this notebook (and an updated version of the notebook) are included in the folder _water/geospatial._
### agriculture.ipynb
Reads MapBiomas' agricultural land-use time-series data and plots the breakdown in bar charts. Data files used in this notebook (and an updated version of the notebook) are included in the folder _agriculture_.
### climate.ipynb
Reads in GLDAS files, which are in  netCDF format, as an _xarray_, strings files together temporally, and uses shapefiles to clip the data to the São Francisco River basin and sub-basins, using the _regionmask_ package. Introduces geospatial averages resulting in regional time-series graphs and boxplots for rainfall rate, air temperature and evapotranspiration rate. Uses climate time-series data and area of center-pivot (MapBiomas data) to estimate water used by center-pivot irrigation. Data files used in this notebook (and an updated version of the notebook) are included in the folder _climate+irrig._
