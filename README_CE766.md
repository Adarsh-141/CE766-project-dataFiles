# Upper Sina Catchment: Rainfall and Groundwater Data

This repository contains preliminary datasets prepared for the CE 766
Watershed Management project on the **seasonal groundwater balance of
the upper Sina catchment, Maharashtra**, for the intended study period
**June 2016--May 2020**.

## Repository contents

  ---------------------------------------------------------------------------
  File                                    Description
  --------------------------------------- -----------------------------------
  `Rainfall_Data_Upper_Sina_Clean.xlsx`   Daily gridded rainfall values,
                                          grid-cell coordinates, monthly
                                          summaries, and seasonal summaries
                                          derived from the available IMDWeb
                                          NetCDF file.

  `Catchment_Data_Starter_Clean.xlsx`     Data-source inventory, published
                                          rainfall figures, published
                                          groundwater-level averages, and
                                          village-level well observations
                                          transcribed from a published Upper
                                          Sina mini-watershed study.
  ---------------------------------------------------------------------------

## Data sources

-   **Rainfall:** IMDWeb gridded daily rainfall data, at 0.25° spatial
    resolution. The original downloaded file was processed into Excel
    tables.
-   **Groundwater observations:** Preliminary values transcribed from a
    published hydrogeological study of the Upper Sina mini-watershed.
    These values should be checked against the original publication and
    official CGWB/GSDA records before use in calibration.
-   **Planned supporting datasets:** SRTM DEM from USGS/NRSC,
    land-use/land-cover data from NRSC/Bhuvan, crop statistics from the
    Maharashtra Directorate of Economics and Statistics, and groundwater
    monitoring data from CGWB/GSDA.

Useful source portals: - [IMD gridded rainfall
data](https://www.imdpune.gov.in/cmpg/Griddata/Rainfall_25_NetCDF.html) -
[IMDWeb](https://imdweb.lwcc.in/) - [USGS
EarthExplorer](https://earthexplorer.usgs.gov/) - [NRSC
Bhuvan](https://bhuvan-app1.nrsc.gov.in/2dresources/bhuvanstore.php) -
[Central Ground Water Board](https://www.cgwb.gov.in/) - [Maharashtra
Directorate of Economics and
Statistics](https://mahades.maharashtra.gov.in/)

## Rainfall data coverage

The supplied IMDWeb file covers **1 January 2017--31 December 2025**.
The rainfall workbook currently extracts **1 January 2017--31 May
2020**, which means the 2016 part of the proposed study period is not
yet included.

The rainfall grid has **not yet been clipped or area-weighted to a
verified DEM-derived upper Sina catchment boundary**. Therefore, the
regional grid summaries should not be interpreted as final
catchment-average rainfall.

## Seasonal definitions

For the project, the year is divided into: - **Monsoon:**
June--October - **Non-monsoon:** November--May

These seasons follow the project's proposed methodology.

## Project method

The planned seasonal groundwater balance is:

`ΔS = R − P − O`

where: - `ΔS` = change in groundwater storage (m³) - `R` = groundwater
recharge (m³) - `P` = groundwater pumping/abstraction (m³) - `O` = other
groundwater outflows (m³)

An approximate water-level change is estimated as:

`Δh = ΔS / (A × Sy)`

where `A` is catchment area (m²) and `Sy` is specific yield.

The intended analysis compares baseline conditions with three
intervention types: additional recharge structures, reduced pumping, and
a shift to less water-intensive crops.

## Current status and limitations

This is a **preliminary data repository**, not a completed or calibrated
groundwater model.

-   Catchment delineation from a 30 m DEM is still pending.
-   Catchment-specific rainfall extraction and the 2016 rainfall record
    remain outstanding.
-   Groundwater observations require verification against original or
    official records.
-   Crop-water demand, pumping, recharge coefficients, specific yield,
    intervention capacities, and costs still need to be compiled or
    justified.
-   No validated baseline simulation or final intervention comparison is
    included yet.

## Suggested citation and use

Please cite the original data providers and publications when using
their data. The processed Excel files are provided for academic project
work; verify source values and document assumptions before reporting
quantitative conclusions.

## Author / project

**Course:** CE 766 --- Watershed Management\
**Project:** Seasonal groundwater balance of the upper Sina catchment,
Maharashtra (June 2016--May 2020)\
**Purpose:** Preliminary data organization and preparation for
groundwater-balance and watershed-intervention analysis.
