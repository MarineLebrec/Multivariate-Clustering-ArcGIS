# Multivariate-Clustering-ArcGIS

This repository includes Jupyter notebooks outlining the workflow used to generate regional benthic habitat classification maps using ArcGIS Pro geoprocessing tools. This workflow uses similar non-hierarchical multivariate clustering methods as those described in [McQuaid et al. (2023)](https://doi.org/10.1016/j.pocean.2023.103016). <br><br>
This content was used during a hands-on training course as part of the Deep Ocean Observing Strategy ["Deep Ocean Collective Solution Accelerator"](https://www.deepoceanobserving.org/pages/collective-solution-accelerator) in October 2023 at Scripps Institution of Oceanography, La Jolla, CA, USA. <br>

This workflow was run using ArcGIS Pro 3.1.2. The ArcGIS Pro Project file can be downloaded at this link: https://arcg.is/1DOOXr0. Note that the URL needs to be copy and pasted in a browser. 

### Below is an overview of what each notebook covers:

##### <u>Step1_Data_Access.ipynb:<u> <br>
- Accessing GEBCO bathymetry data, clipping that data to a region of interest, and masking that data to exclude values above sea level.
- Running the Benthic Terrain Modeler
- Accessing Bio-ORACLE and NEMO-MEDUSA raster layers

##### <u>Step2_Run_Clustering.ipynb:<u><br>
- Aggregating data and converting either to hex bins or points
- Creating feature class containing all layers
- Run Multivariate Clustering
- Visualizing clustering outputs using box plots and different mapping techniques

##### Want to get involved in the DOOS Habitat Mapping working group? 
:email: Reach out to us: mlebrec@mbari.org <br>

<img src="images/iDOOS_logo-3-400x295.png" style="width:200px; height:auto;" />
