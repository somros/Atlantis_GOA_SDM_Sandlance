# Spatial distributions for sand lance in the GOA

This code produces distribution maps for sand lance (*Ammodytes personatus*) in Atlantis GOA.  

Sand lance is not picked up much in the bottom trawl survey data, but it is an important item in the diet of some groundfish species, including Pacific cod, arrowtooth founder, Pacific halibut, and walleye pollock. Here we use diet data from the [REEM program](https://apps-afsc.fisheries.noaa.gov/refm/reem/webdietdata/dietdataintro.php) in the GOA to obtain crude estimates of sand lance spatial distributions based on the consumption of sand lance in space (all years lumped).  

Sand lance biomass is estimated from their weight per predator weight in each haul, averaged at the level of Atlantis box. These are then multiplied by the biomass of the predator per box as estimated by the sdmTMB work. See RMD file for a list of assumptions and limitations. Distributions are assumed to remain constant over time and between life stages.