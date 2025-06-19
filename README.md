Optimization Model for Store Location Selection:

The goal of this project is to determine OXXO the best candidate store locations in terms of profitability.  The approach done is to create a Mixed-Integer Linear Programming model based on facility location Models, as well as spatial analysis, to determine the most profitable combination of candidate stores.

Software used for project:
- Python 3.10
- Pandas 2.2.2
- Geopandas 0.14.0
- Numpy 2.3.0
- Matplotlib 3.10.3
- Pyomo 6.6.2

There are two Jupyter notebooks.  
- aid_oxxo_montos.ipynb - The complementary file is unnecessary but was used to try different strategies.
- Opti1_OXXO_Entregable3.ipynb - This file is where the main project is and all of its process.

The data used in this project is as follows:

Shapefiles for AGEBs (Basic Geostatistic Areas):
- AGEB_MTY.shp
- AGEB_MTY.dbf
- AGEB_MTY.shx
- AGEB_MTY.prj
- AGEB_MTY.cpg

Data files for OXXO Stores:
- dataset_comp_ratio_test.csv
- dataset_comp_ratio.csv
- RESAGEBURB_19CSV20.csv
- ventas_oxxo.xlsx

The data files are provided separately to the notebooks.  In order for the project to run properly, the data files and the project files must be in the same location.

Disclaimer: The store data used in this project, although based on actual OXXO data, is dummy data with the primary purpose of serving as a placeholder for actual data.
