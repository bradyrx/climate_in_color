# Observational and Model Data

Most observations were pulled from the already post-processed `MPAS-Analysis` set: https://mpas-analysis.readthedocs.io/en/master/observations.html. We try to provide a simple 1degree product for a single time slice (e.g., climatology over some period). The goal here is to showcase student-designed colormaps.

Model output was taken from the simple Dry Dynamical Core model and CESM versions 1 and 2.

## Atmosphere

1. `CESM2_delta_precip_2070-2100_1970-2000.nc`: Change in precipitation in a single ensemble member of [CESM2](http://www.cesm.ucar.edu/models/cesm2/) between the historical (1970-2000 average) and high-emissions SSP585 (2070-2100 average) scenarios.

2. `ERA5.500mb.2018-01-01.nc`: 500mb observations (e.g. specific humidity and geopotential height) from [ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) at midnight UTC on January 1st, 2018.

3. `HS94.climate.d0500-d3500.nc`: Results from a Dry Dynamical Core model experiment.

## Ocean

1. `SST.HadNOAA.1970-2010.1deg.nc`: SST merged Hadley Center-NOAA/OI [product](https://climatedataguide.ucar.edu/climate-data/merged-hadley-noaaoi-sea-surface-temperature-sea-ice-concentration-hurrell-et-al-2008) climatology over 1970-2010.

2. `SST_ENSO_response.nc`: Global SSTs in a single member of the [CESM1 Large Ensemble](http://www.cesm.ucar.edu/projects/community-projects/LENS/) (1920-2005) regressed onto the Nino3.4 index for that same member. I.e., the response of SSTs globally to a 1 degree El Niño event.

## Sea Ice

1a. `ICESat_gridded_mean_thickness_NH_fm.interp0.5x0.5.nc`,`ICESat_gridded_mean_thickness_NH_on.interp0.5x0.5.nc`: Climatology of gridded ICESat product over its coverage period for the northern hemisphere for Feb-Mar and Oct-Nov.

1b. `ICESat_gridded_mean_thickness_SH_fm.interp0.5x0.5.nc`, `ICESat_gridded_mean_thickness_SH_on.interp0.5x0.5.nc`: Climatology of gridded ICESat product over its coverage period for the southern hemispehre for Feb-Mar and Oct-Nov.
