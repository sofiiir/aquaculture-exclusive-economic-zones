# Potential Aquaculture Locations within Exclusive Economic Zones
#### Author: Sofia Rodas
#### Date: November 30, 2025

Aquaculture is a viable solution to help address over-fishing while providing ocean foods to communities that rely on them. It additionally creates a job sector increasing local employment opportunities. There are many factors in choosing suitable locations for aquaculture, sea surface temperature (SST) and bathymetry are two key considerations. This repository focuses on  analyzing SST and bathymetry species requirements to identify potential aquaculture locations. Further, the findings of potential aquaculture locations for each species is broken into Exclusive Economic Zones (EEZ). These steps are packaged into a function for use on additional species. 


## Data Access:

-**Data download:** Data used in this analysis can be accessed and downloaded from a Google Drive here: [Data Google Drive]((https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view)). The data is all publicly available as denoted below. 

-**Sea Surface Temperature (SST) Data:** SST data was acquired from the [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php). It is publicly available. 

-**Bathymetry Data:** Bathymetry data is available through the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area). It is publicly available.

-**Exclusive Economic Zones (EEZ) Data:** EEZ data is available through [marineregions.org](https://www.marineregions.org/eez.php). It is publicly available.

-**Additional Species SST and bathymetry Values:** Species suitable SST and bathymetry ranges are available through [SeaLifeBase](https://www.sealifebase.ca/search.php). It is publicly available.

## File structure:
<img width="367" height="229" alt="eds223-aqu-tree" src="https://github.com/user-attachments/assets/10a77beb-e58c-4e00-bb91-023488dedc00" />


**Note:** Data was added to .gitignore. Data can be downloaded from a [Google Drive](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view).

## Repository Contents:
-**Quarto document:** [aquaculture-exclusive-economic-zones.qmd](https://github.com/sofiiir/aquaculture-exclusive-economic-zones/blob/main/aquaculture-exclusive-economic-zones.qmd)


### References:

Flanders Marine Institute (2025): MarineRegions.org. Available online at www.marineregions.org. Consulted on 2025-11-14.

Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. Nature Ecology & Evolution, 1, 1317-1324 (2017).

GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).

Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M. Blue Frontiers: Managing the Environmental Costs of Aquaculture (The WorldFish Center, Penang, Malaysia, 2011).

NOAA Coral Reef Watch. 2019, updated daily. NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1 for the West Coast, 2008 - 2012. College Park, Maryland, USA: NOAA Coral Reef Watch. Data set accessed 2025-11-14 at [https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

Palomares, M.L.D. and D. Pauly. Editors. 2025. SeaLifeBase. World Wide Web electronic publication. www.sealifebase.org, version (04/2025).
