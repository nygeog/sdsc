### Spatial Data Science Conference Bootcamp - 2023 - New York

# Foundations of Geospatial 

https://spatial-data-science-conference.com/bootcamps/2023/#register

![sdsc](https://camo.githubusercontent.com/d493411c6fdf1da870c898d43ff3e93dd8ae0dfcca632be6711ce5ebd3149607/68747470733a2f2f7370617469616c2d646174612d736369656e63652d636f6e666572656e63652e636f6d2f696d672f323032332f7265706f7369746f72792f6e792d73756d6d69742d636172642d312e706e67)

### Additional Resources

* Class for Pratt SAVI 810 2020-03: Intro to Python Scripting for Geospatial - https://github.com/pratt-savi-810/pratt-savi-810-2020-03
* Geographic Data Science Lab is a research centre at the University of Liverpool -  https://www.liverpool.ac.uk/geographic-data-science/
* CSC Finland – IT Center for Science - Welcome to Introduction to Python GIS -course 2018 - https://automating-gis-processes.github.io/CSC/index.html
* https://modern-gis-curriculum-new-learngis.hub.arcgis.com/
* https://introduction-to-remote-sensing-learngis.hub.arcgis.com/
* https://learn.arcgis.com/en/gallery/
* https://geobgu.xyz/py/index.html
* https://pygis.io/docs/a_intro.html
* https://spatialthoughts.com/courses/
* Geographic Data Science, a course designed by Dr. Dani Arribas-Bel - https://darribas.org/gds_course/content/home.html


## Setup 

I generally recommend using Miniconda - https://docs.conda.io/en/latest/miniconda.html - for managing geospatial python environments. 

> Miniconda is a free minimal installer for conda. It is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others. Use the conda install command to install 720+ additional conda packages from the Anaconda repository. - https://docs.conda.io/en/latest/miniconda.html

Latest Miniconda installers - https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links

Once Miniconda is set up, create an env: 

`conda create -n sdsc python=3.8`

Activate your Conda environment. 

`conda activate sdsc`

Conda install from requirements.txt

`conda install --yes --file requirements.txt`




### List of Installations

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