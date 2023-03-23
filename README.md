# Spatial Data Science Conference Bootcamp - 2023 - New York

https://spatial-data-science-conference.com/bootcamps/2023/#register



## Setup 

I generally recommend using Miniconda - https://docs.conda.io/en/latest/miniconda.html - for managing geospatial python environments. 

> Miniconda is a free minimal installer for conda. It is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others. Use the conda install command to install 720+ additional conda packages from the Anaconda repository. - https://docs.conda.io/en/latest/miniconda.html

Latest Miniconda installers - https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links

Once Miniconda is set up, create an env: 

`conda create -n sdsc python=3.8`

Activate your Conda environment. 

`conda activate sdsc`

Install Jupyter Lab

`pip install jupyterlab` 

Install GeoPandas

`conda install geopandas` 

Install Rasterio 

`pip install rasterio`

Install Folium

`conda install folium -c conda-forge --yes`

IPyLealeft

`conda install -c conda-forge ipyleaflet`

Enable extension

`jupyter nbextension enable --py --sys-prefix ipyleaflet`

Raster Stats

`pip install rasterstats` 

Rise
`pip install RISE`

OSMnx (Optional)
`!conda install osmnx -y`


#### Create Conda Requirements file

`conda list -e > requirements.txt`