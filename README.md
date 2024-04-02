# cone-db
This repository contains collected data of cone calorimeter tests of different materials, especially from rail car interior finish.
## Anonymization of Materials
The materials tradenames, manufacturers and projects where the corresponding material was used is not given in this database. This is due to data protection effords. Each material in this repository was given a hash to identify and distinguish the datasets. 
The material parameters that are given are:

- Material type (Polymer, Wood-Based or Mixture
- Application (for example: paneling, flooring)

## Overview Dataframe
[Overview Dataframe](ConeData/combined_overview_official.csv)

For each Cone Calorimeter experiment the following information is given in the overview csv-file:

- Applied external flux
- Sampling interval
- Orientation
- If an Edge frame was used
- Separation
- Initial mass
- Thickness
- Surface Area
- Manually determined Ignition Time
- File name with corresponding datasets

## Datasets
For each Cone Calorimeter experiment time dependent values are given for:

- HRR
- SEA
- MLR
- CO Yield
- CO2 Yield

In some cases instead of the CO and CO2 Yield the Mass Fraction of CO and CO2 in the smoke gases. The unit specified in those cases is ppm or percent and is given in the column header.
