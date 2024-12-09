# Predicting Appropriate Sites for Aquaculture along the West Coast of the US
## A project for EDS 223 in the Master's of Environmental Data Science Program at UCSB
![Mariculture of Oysters: middlesoundmariculture.com](https://img1.wsimg.com/isteam/ip/e6715026-e6cc-42bb-a6e0-c2abe7d97162/DJI_0550.jpg/:/) 

## About this repository:
Mariculture (or marine aquaculture) is the process of cultivating marine species in an open or enclosed marine environment to be used as commerical produce. Marine aquaculture is a promising development in food production, as it not only produces large quantities of food, but can also be highly cost effective (depending on the species) in comparion to terrestrial agriculture or food production. As most countries around the world are trying to cope with inequitable distribution of food and resources, mariculture could greatly benefit communities on a global scale.

For example, many species of filter feeders can be cultivated with almost no additional input from the fishers, as they feed on plankton and detritus suspended in the water column and do not need space to move around. Many lines or pots seeded with juveniles can be dropped into the water column, suspended from floats, and easily harvested when they are fully grown in a 1-2 years time. In lieu of this, I was interested in the West Coast's potential to cultiavte oysters and mussels, two species desirable as a food source both locally and abroad. 

To accurately predict where these species could be aquacultured, I had to find areas along the western coast of the US that were both the appropriate depth and temperature for these species. Using the format developed to predict this potential area for oyster cultivation, I created a function tht can predict potential area for aquaculture of any species in the Exclusive Economic Zone(EEZ) of the US, given it's desired temperature and depth range.
 
![Underwater Mariculture Oysters: aquaculturemag.com](https://aquaculturemag.com/wp-content/uploads/2019/08/Oysters-iStock-653783296-1280x854.jpg) 

## Repository Structure:
```
Marine_Aquaculture_West_Coast
│   README.md
│   Marine_Aquaculture_Sites.qmd
|   Marine_Aquaculture_Sites.html (rendered version)
|   .gitignore
```


## Data Analysis Objectives:
In this project we were looking to:
- Combine vector and raster data to analyze the overlap between the EEZ and appropriate aquaculture sites
- Resample and mask data for an appropriate overlay of our data sets
- Create a function that predicts total area for potential aquaculture use given a species and it's temperature and depth requirements 


## Data Access:
This data was obtained from the instructor of EDS 223, compiled from sources below.
All relevant data available [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view).

#### California Mussel and Oyster Data
The SeaLifeBase database compiles habitat and taxonomic data on a wide array of marine species. Both the mussel and oyster habitat data (SST and depth information) were acquired from this website. 
<a href="https://www.sealifebase.ca/search.php" target="_blank">SeaLifeBase</a>

#### Bathymetry Data
The bathymetry data was pulled from a database via 'General Bathymetric Chart of the Oceans' (GEBCO). 
<a href="https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area" target="_blank">GEBCO</a>

#### Sea Surface Temperature Data:
Sea Surface Temperature (SST) data was compiled via a 'National Oceanic and Atmospheric Administration' (NOAA) satellite, in a dataset called 'Daily Global 5km Satellite Sea Surface Temperature Anomaly' on the NOAA 'Coral Watch' website. 
<a href= "https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php" target= "_blank">Sea Surface Temperature Anomaly</a>  

## Resources:

#### Project Description and Access to Data
Oliver, Ruth. (2024). EDS 223: Geospatial Analysis and Remote Sensing, Masters of Environmental Data Science (MEDS) Program. University of California, Santa Barbara. <a href="https://eds-223-geospatial.github.io/" target="_blank">Geospatial Analysis and Remote Sensing</a>

#### Benefits of Mariculture
Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M. Blue Frontiers: Managing the Environmental Costs of Aquaculture (The WorldFish Center, Penang, Malaysia, 2011).↩︎

#### Mapping Aquaculture Potential
Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. Nature Ecology & Evolution, 1, 1317-1324 (2017).↩︎

#### Bathymetry Data
GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).↩︎

