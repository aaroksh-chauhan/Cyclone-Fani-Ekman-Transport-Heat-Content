# Cyclone Fani: Ocean Density, Ekman Transport, and Heat Content Analysis

## Overview
This project studies how the ocean responded to Cyclone Fani (April–May 2019), 
one of the strongest cyclones to hit the Bay of Bengal/Odisha coast, by 
analyzing seawater density distribution, wind-driven Ekman transport, and 
ocean heat content during the cyclone period.

## Objective
- Examine the spatial distribution of seawater density during Cyclone Fani
- Compute Ekman transport (the movement of surface water driven by wind, 
  modified by the Earth's rotation) both spatially and as a time series, to 
  understand how the cyclone's winds altered upper-ocean circulation
- Calculate ocean heat content during the cyclone period, a key factor in 
  cyclone intensification

## Data
- **Source:** Gridded ocean reanalysis data (NetCDF) — temperature, salinity, 
  and wind fields
- **Time period:** April–May 2019 (covering Cyclone Fani)
- **Region:** Bay of Bengal, along the cyclone's track

## Tools & Methods
- **Language:** Python
- **Key libraries:** xarray, numpy, matplotlib, cartopy
- **Method:** Computed seawater density from temperature and salinity fields, 
  calculated Ekman transport from wind stress and analyzed it both as a 
  spatial pattern and as a time series across the cyclone period, and computed 
  ocean heat content to assess the thermal energy available to the storm

## Results
- Mapped how seawater density varied spatially across the Bay of Bengal during 
  the cyclone period
- Ekman transport showed a clear response to the cyclone's wind field, both in 
  its spatial pattern and its evolution over time as the storm passed
- Ocean heat content analysis provided insight into the thermal conditions 
  that can influence cyclone strength — a key variable in tropical cyclone 
  research

## Skills Demonstrated
- Ocean dynamics analysis (density, Ekman transport, heat content)
- Case-study analysis of an extreme weather event using reanalysis data
- Working with gridded NetCDF ocean and wind data
- Scientific visualization using Python (cartopy, matplotlib)

## Author
Aaroksh Chauhan — M.Sc. Atmospheric and Oceanic Sciences, IIT Bhubaneswar
