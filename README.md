# Food flow study

Food flow data was collected in West Africa for four cities - Bamako (Mali), Bamenda (Cameroon), Ouagadougou (Burkina Faso), and Tamale (Ghana). The data covers, depending on the city, road, rail, boat, and air traffic. Surveys were conducted for one week on average during the peak harvest, lean, and rainy seasons, resulting in a dataset of over 100,000 entries for 46 unprocessed food commodities. The data collected includes information on the key types of transportation used, and quantity, source, and destination of the food flows. They can be used to inform academic and policy discussions on urban food system sustainability, to validate other datasets and to plan humanitarian aid and food security interventions.

# Data

The dataset is available on zenodo.org. The Jupyter Notebook suggests options for reusing the data (food_flow_notebook.ipynb). The related Python script (food_flow_script.py, Version 3.9) requires the installation of following packages
	`pyproj`
	`matplotlib`
	`pandas`	
	`shapely`	
	`numpy`
	`seaborn`
	`gdal`
	`geopandas`
We recommend to install these packages using the conda package manager. 
The PostgreSQL folder provides the underlying database structure with auxiliary tables, including calibration lists and metadata (not needed for reusing the published food flow dataset).
