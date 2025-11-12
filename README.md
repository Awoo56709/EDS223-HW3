# Texas Blackouts and Socioeconomic Lenses

# Author
Joshua Ferrer-Lozano

# Repository's Purpose

This project analyzes the February 2021 Texas blackouts using satellite night lights (VIIRS), OpenStreetMap building data, and U.S. Census socioeconomic data. The workflow detects blackout areas, estimates the number of homes affected, and explores whether income levels influenced outage impacts.

# Data Access and Sources
While data sources are stored within the repository, direct sources are linked below:

- VIIRS Night Lights (NASA/NOAA) – daily radiance composites.
- OpenStreetMap (OSM) – building footprints and road networks.
- U.S. Census ACS 2019 5‑Year Estimates – tract‑level socioeconomic data.

# Repository Structure
```text
├── EDS223-HW3.Rproj
├── README.html
├── README.md
├── data
│   ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb
│   ├── VNP46A1
│       ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif
│       ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif
│       ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif
│       └── VNP46A1.A2021047.h08v06.001.2021048091105.tif
├── texas_blackout.html
├── texas_blackout.qmd
└── texas_blackout_files
```

# Acknowledgements
[Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)](shttps://ladsweb.modaps.eosdis.nasa.gov/)
[Open Street Maps](https://planet.openstreetmap.org/)
[U.S Census Bureau;s American Community Survey](https://www.census.gov/programs-surveys/acs)

# References

- Level‑1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC). (n.d.). NASA Earth Observing System Data and Information System (EOSDIS). Retrieved from https://ladsweb.modaps.eosdis.nasa.gov/
- OpenStreetMap Contributors. (n.d.). Planet OSM data dump. Retrieved from https://planet.openstreetmap.org/
- U.S. Census Bureau. (n.d.). American Community Survey (ACS). Retrieved from https://www.census.gov/programs-surveys/acs
