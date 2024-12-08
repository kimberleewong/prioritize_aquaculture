# Prioritizing Potential Aquaculture

Kimberlee Wong - December 7, 2024

![image](https://www.marinemammalcenter.org/storage/app/uploads/public/ec8/271/d6d/thumb__749_0_0_0_crop.jpg)


## About

This repository houses a notebook that shows the process of determining which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture for several species of oysters and red abalone. Suitable locations will be determined based on range of suitable sea surface temperature (SST) and depth values for the species. A function was created that has the following characteristics:

arguments: 
  - minimum and maximum sea surface temperature
  - minimum and maximum depth
  - species name
    
outputs:
  - map of EEZ regions colored by amount of suitable area
  - species name should be included in the map’s title

## Highlights
- Map algebra
- Combining raster and vector data
- Resampling and masking raster data
- Creating a function

## Repository Structure
```
prioritizing_aquaculture
│   README.md
│   prioritizing_potential_aquaculture.qmd
│   prioritizing_potential_aquaculture.html
│   .DS_Store
│   prioritizing_potential_aquaculture.Rproj
|   .gitignore
```
## References of Data

| Data                 | Source                                                    | Link                                                                  |
|----------------------|-----------------------------------------------------------|-----------------------------------------------------------------------|
| Depth                | GEBCO Gridded Bathymetry Data                             | https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area |
| SST                  | NOAA Global 5km Satellite Sea Surface Temperature Anomaly | https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php        |
| West Coast EEZs      | Marine Regions EEZ Boundaries                             | https://www.marineregions.org/eez.php                                 |
| Species Requirements | SeaLifeBase                                               | https://www.sealifebase.ca/search.php 


## Acknowledgements

Assignment came from UCSB Masters of Environmental Data Science class, EDS 223 - Working with Environmental Data Science. Class is taught by Ruth Oliver.

Data is available for download [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view)

