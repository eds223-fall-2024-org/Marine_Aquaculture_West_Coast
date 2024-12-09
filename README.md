# Predicting Appropriate Sites for Aquaculture along the West Coast of the US
## A project for EDS 223 in the Master's of Environmental Data Science Program at UCSB

## About this repository:
Mariculture (or marine aquaculture) is the process of cultivating marine species in an open or enclosed marine environment to be used as commerical produce. Marine aquaculture is a promising development in food production, as it not only produces large quantities of food, but can also be highly cost effective (depending on the species) in comparion to terrestrial agriculture or food production. As most countries around the world are trying to cope with inequitable distribution of food and resources, mariculture could greatly benefit communities on a global scale.

For example, many species of filter feeders can be cultivated with almost no additional input from the fishers, as they feed on plankton and detritus suspended in the water column and do not need space to move around. Many lines seeded with juveniles can be dropped into the water column, suspended from floats, and easily harvested when they are fully grown in a 1-2 years time. In lieu of this, I was interested in the West Coast's potential to cultiavte oysters and mussels, two species desirable as a food source both locally and abroad. 

To accurately predict where these species could be aquacultured, I had to find areas along the western coast of the US that were both the appropriate depth and temperature for these species. Using the format developed to predict this potential area for oyster cultivation, I created a function tht can predict potential area for aquaculture of any species given it's desired temperature and depth range.

 
![Mariculture of Oysters: middlesoundmariculture.com](https://img1.wsimg.com/isteam/ip/e6715026-e6cc-42bb-a6e0-c2abe7d97162/DJI_0550.jpg/:/) 

## Repository Structure:
```
Historic_Redlining_Los_Angeles
│   README.md
│   Historic_Redlining_LA.qmd
|   HW2.html (rendered version)
|   .gitignore
```


## Data Analysis Objectives:
In this project we were looking to:
- Combine vector and raster data to analyze the overlap between the EEZ and appropriate aquaculture sites
- Resample and mask data for an appropriate overlay of our data sets
- Create a function that predicts total area for potential aquaculture use given a species and it's temperature and depth requirements 


## Data Access:
This data was obtained from the instructor of EDS 223, compiled from sources below.
All relevant data available [here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view?usp=drive_link).

#### US EJScreen Data:
The environmental justice block group data was compiled by the United States Environmental Protection Agency:Environmental Justice Screening and Mapping Tool. 
<a href="https://www.epa.gov/ejscreen/purposes-and-uses-ejscreen" target="_blank">EPA: EJ Screen</a>

#### HOLC Redlining Data:
The Home Owner's Loan Corporation redlining data was complied by the Digital Scholarship Lab, at the University of Richmond as a part of the 'Mapping Inequality Project'. 
<a href= "https://dsl.richmond.edu/panorama/redlining/data" target= "_blank">Mapping Inequality Project</a> 

#### Biodiversity Data:
The biodiversity data came from the Cornell Lab of Ornthology, accessed via the Global Biodiversity Information Facility, which records species, location, and time for each observation. The specific subset of this data utilized was on bird biodiversity from 2021 to 2024. 
<a href= "https://www.gbif.org/dataset/4fa7b334-ce0d-4e88-aaae-2e0c138d049e" target= "_blank">Bird Biodiversity</a> 

## Resources:

#### Project Description and Access to Data
Oliver, Ruth. (2024). EDS 223: Geospatial Analysis and Remote Sensing, Masters of Environmental Data Science (MEDS) Program. University of California, Santa Barbara. <a href="https://eds-223-geospatial.github.io/" target="_blank">Geospatial Analysis and Remote Sensing</a>

#### Description of HOLC Redlining
Gee, G. C. (2008). A multilevel analysis of the relationship between institutional and individual racial discrimination and health status. American journal of public health, 98(Supplement_1), S48-S56.

#### Ties to Higher HOLC Grade and Increased Greenery
Nardone, A., Rudolph, K. E., Morello-Frosch, R., & Casey, J. A. (2021). Redlines and greenspace: the relationship between historical redlining and 2010 greenspace across the United States. Environmental health perspectives, 129(1), 017006.

#### Ties to Lower HOLC Grade and Increased Ambient Temperature
Hoffman, J. S., Shandas, V., & Pendleton, N. (2020). The effects of historical housing policies on resident exposure to intra-urban heat: a study of 108 US urban areas. Climate, 8(1), 12.

#### Sampling Disparities Between Redlining and Non-Redlining Neighborhoods
Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 1-9.

