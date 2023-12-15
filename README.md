# West Coast Region Suitable Aquatic Homes

Marine aquaculture has the potential to play an important role in the global food supply as a more sustainable protein option than land-based meat production.[^1] [Gentry et al.](https://www.nature.com/articles/s41559-017-0257-9) mapped the potential for marine aquaculture globally based on multiple constraints, including ship traffic, dissolved oxygen, bottom depth .[^2]

[^1]: Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O'Keefe, M. Blue Frontiers: Managing the Environmental Costs of Aquaculture (The WorldFish Center, Penang, Malaysia, 2011).

[^2]: Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. *Nature Ecology & Evolution*, 1, 1317-1324 (2017).

For this project, we will be determining which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture for several species of oysters and other aquatic species.

Based on previous research, we know that oysters needs the following conditions for optimal growth:\

-   sea surface temperature: 11-30°C
-   depth: 0-70 meters below sea level

##### Learning objectives:

-   combining vector/raster data
-   resampling raster data
-   masking raster data
-   map algebra

### Data

#### Sea Surface Temperature

We will use average annual sea surface temperature (SST) from the years 2008 to 2012 to characterize the average sea surface temperature within the region. The data we are working with was originally generated from [NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

[^3]: Watch, NOAA Coral Reef. NOAA Coral Reef Watch Daily 5km Satellite Coral Bleaching Heat Stress SST Anomaly Product (Version 3.1), coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php.

#### Bathymetry

To characterize the depth of the ocean we will use the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area).[^3]

[^4]: GEBCO Compilation Group (2022) GEBCO_2022 Grid (<doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c>).
[^5]: General Bathymetric Chart of the Oceans. “Gridded Bathymetry Data (General Bathymetric Chart of the Oceans).” GEBCO, www.gebco.net/data_and_products/gridded_bathymetry_data/#area.
#### Exclusive Economic Zones

We will be designating maritime boundaries using Exclusive Economic Zones off of the west coast of US from [Marineregions.org](https://www.marineregions.org/eez.php).

[^6]: Marine Regions, www.marineregions.org/eez.php. 

**Note:** the data associated with this project is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?usp=sharing). Unzip the folder and all the contents and store in your directory as follows. Don't include data pushing to GitHub!

    WCR_SuitableAquaticHomes
    │   README.md
    │   Rmd/Proj files    
    │
    └───data
        │   wc_regions_clean.shp
        │   depth.tif
        │   average_annual_sst_2008.tif
        │   average_annual_sst_2009.tif        
        │   average_annual_sst_2010.tif        
        │   average_annual_sst_2011.tif
        │   average_annual_sst_2012.tif     
   

