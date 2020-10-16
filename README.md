# LANDFIRE - A236

Code to prepare data for Landfire Update using ST-Sim.

Intructions to run on small extent: 

1. Ensure you have the proper versions of the following software/packages.
  - R: `3.6.2` or higher, download it [here](https://cran.r-project.org/)
  - Syncrosim: `2.2.19`, download it [here](https://syncrosim.com/download/) 
  - StSim: `3.2.21`, download it [here](https://syncrosim.com/packages/)

2. Download the Access database 

2. Open the a236.Rproj file in Rstudio

3. Open the script in `scripts/buildSsimLibrary.R`, then source or Run the script to build the library

4. Ensure you have all the package necessary: `tidyverse`, `rsyncrosim`, `raster`, `RODBC`

4. Open the new library `LandFire_Test_SmallExtent.ssim` in the `library` folder.

5. Click on the Test scenario and run it.
