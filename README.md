# solar-fleet-subhourly-modeling

This repository contains sample code for generating subhourly (i.e., 5-minute interval) power data for a fleet of solar plants using NREL NSRDB [1] and pvlib [2]. It is demonstrated using solar plant specifications from EIA Form 860 [3], but could be modified to use other lists of plants and specifications. 

See the notebook [solar_fleet_subhourly_modeling.ipynb](solar_fleet_subhourly_modeling.ipynb) for setup information and all Python code. 

[1] https://nsrdb.nrel.gov/.

[2] Anderson, K., Hansen, C., Holmgren, W., Jensen, A., Mikofski, M., and Driesse, A. “pvlib python: 2023 project update.” Journal of Open Source Software, 8(92), 5994, (2023). https://doi.org/10.21105/joss.05994

[3] https://www.eia.gov/electricity/data/eia860/