### These scripts are example "mapping pipelines" that are under current development
- The "ForestPotential\_CV\_and\_Bootstrapping\_Pipeline.ipynb" notebook contains code for the "main pipeline", which allows abritrary input of categorical and continuous data;
	- To attain the point samples / build the classification and regression matrix, use the point sampling script titled "20200303\_ForestPotential\_PointSampling";
	- The point sampled data is found in the CSV titled "20200303\_ForestPotential\_Samples.csv"
	
- The "ForestPotential\_CV\_and\_Bootstrapping\_Pipeline.ipynb" script contains separate pipeline code for a specific biome prediction project, but shows examples of generating regression and classification matrix datasets from a raster (rather than from point locations);

- The "Functions to Integrate" directory contains additional functions that need to be added as part of the pipelines;


### AC Notes
These are the fields in the '20200303_ForestPotential_Samples.csv' file:
system:index,
CHELSA_Annual_Mean_Temperature,
CHELSA_Annual_Precipitation,
CHELSA_Mean_Temperature_of_Warmest_Quarter,
CHELSA_Precipitation_Seasonality,
CHELSA_Precipitation_of_Driest_Quarter,
EarthEnvTopoMed_Eastness,
EarthEnvTopoMed_Elevation,
EarthEnvTopoMed_Northness,
Lat,
Long,
Resolve_Biome,
SG_Depth_to_bedrock,
SG_Sand_Content_000cm,
SG_Sand_Content_005cm,
shrubcover,
treecover,
.geo