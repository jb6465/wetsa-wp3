# WETSA Work Package 3 - list of activities and tasks
GitHub repository for WETSA WP3 team to store, track and develop code, key outputs and relevant analysis.<br>
<sub> 🚩 indicates action required by BMKG</sub><br><br>

**Navigation:** [Obs Comparison](https://github.com/jb6465/wetsa-wp3/edit/main/README.md#reanalysis-comparison-with-in-situ-data) | [Reanalysis Climatology](https://github.com/jb6465/wetsa-wp3/edit/main/README.md#barraera5-resource-potential-climatology) | [Coincident peak/low resource periods](https://github.com/jb6465/wetsa-wp3/edit/main/README.md#coincident-peaklow-resource-period-analysis) | [Projections Analysis](https://github.com/jb6465/wetsa-wp3/edit/main/README.md#projections-analysis) | [Relevant Studies](https://github.com/jb6465/wetsa-wp3/edit/main/README.md#relevant-studies)<br>



## Reanalysis comparison with in situ data
- Obtain in situ data from BMKG - ensuring adequate representation of spatial regions, climate zones and mainland/offshore locations.🚩
- BARRA topography plot with station locations + sub-regions labelled.
- Statistical analyses - bias, MAE, RMSE, correlations, PDF plots, wind gust rose plots, scatter plots
- Timeseries/spatial plots for regions/points of interest → Kalimantan existing wind farm South Sulawesi prospected location
    
## BARRA/ERA5 resource potential climatology
- mean annual, monthly, seasonal climatology (at surface and hub heights for wind) → averages and by hour by day
- hourly wind speed timeseries composites aggregated by spatial region (western, central, eastern) and climatological regions (monsoon, equatorial, other)
- hours per year above/below minimum wind threshold (multiple thresholds, 3 m/s for modern turbines, 6 m/s, advised by PLN as ‘decent’ production)
- hours per year above maximum wind threshold + overlay transmission line map if possible (25 m/s, advised by PLN)
- hours per year above power plant lending threshold (p75 and p90, advised by PLN)
- repeat relevant above according to ENSO/IOD signal
- daily solar irradiance PDFs
- timing of diurnal maximum wind speed in local solar time
 
      
## Coincident peak/low resource period analysis
- low resource period - identify synoptic set up, suspected monsoonal activity/objects
- scatter plot of year (y-axis), month (x-axis) and high/low production days for concurrent p90 exceedance wind, solar and rainfall, accompany with spatial plots (similar to fig 6 in [this study](https://doi.org/10.1002/met.2093))
- capacity factor - using previously representative power conversion models
- integrate with demand data (direct or derive proxies from population density/nightlight satellite products) 🚩

## Projections analysis
- finalise dynamically downscaled ensemble (likely ACS core 39 → 7 BARPA, 7 CCAM, 15 UQ-DES, 10 NARCliM)
- extract and interpolate to common resolution over SEA domain
- slice to GWLs
- for each ensemble member
    - annual hours above absolute thresholds GWL1.5, 2.0 and 3.0 relative to 1.2
    - annual hours above percentile thresholds GWL1.5, 2.0 and 3.0 relative to 1.2
- multi-model ensemble median plots with stippling to show where >66% of the ensemble agrees on the sign of change.
- outlier ensemble members → stress testing case study

## Relevant Studies
https://doi.org/10.1071/ES24028<br>
https://doi.org/10.1002/met.2093<br>
https://doi.org/10.1038/s41598-022-25570-y<br>
https://doi.org/10.1063/5.0060375<br>
https://doi.org/10.1063/5.0000854<br>
https://doi.org/10.5194/acp-24-10209-2024<br>
