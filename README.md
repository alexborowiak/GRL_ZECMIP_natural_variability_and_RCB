# GRL_ZECMIP_natural_variability_and_RCB

Scritps used in the journal article "Projected Global Temperature Changes after Net Zero are Small but Significant" 
[https://doi.org/10.22541/essoar.170904760.09408825/v1]

zec_00_make_zecmip_path_file_v3_(all_variable)_prod.ipynb
This notebook is used to generate json files that contain the paths the locations of all the models. This notebook has to be run
each time a file for a new variable is generated. 

zecmip_natural_variability_01_v2_multivar_analysis_prod.ipynb
This notebook generates all of images used in the supplementary. This notebook also can be used to save netcdf files and 
csv files of the data.

zecmip_natural_variability_02_plot_combine_prod.ipynb
This notebook opens the csv and netcdf files generated by zecmip_natural_variability_01_v2_multivar_analysis_prod.ipynb 
and plots the precipitation and temperature distributions in a single figure. 