# Multivariate-Clustering-ArcGIS
This repo includes Jupyter notebooks describing the workflow used to generate regional benthic habitat classification maps using ArcGIS Pro tools.

Below is an overview of what each notebook covers:

<u>Step1_Data_Access.ipynb:<u> <br>
- Accessing GEBCO bathymetry data, clipping that data to a region of interest, and masking that data to exclude values above sea level.
- Running the Benthic Terrain Modeler
- Accessing Bio-ORACLE and NEMO-MEDUSA raster layers

<u>Step2_Run_Clustering.ipynb:<u><br>
- Aggregating data and converting either to hex bins or points
- Creating feature class containing all layers
- Run Multivariate Clustering
- Visualizing clustering outputs using box plots and different mapping techniques
