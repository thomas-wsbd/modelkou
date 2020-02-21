# modelkou

## Download the data
You can download the data (geodata like locations of the rivers, digital elevations models of the Kou area), scripts and examples either via Owncloud or Github, Owncloud is the easier if you don't have Git.

#### Via OwnCloud
Go to [this link](https://owncloud.brabantsedelta.nl/index.php/s/oybM3PwuPexvych) and download the zip-file containing all data.

#### Via Github 
Go to [this repository](https://github.com/thomas-wsbd/modelkou). You can use Git or follow the following steps.
1. Download the repository using the green button ``Clone or download`` > ``Download ZIP``. 
2. This will not download the ``.asc`` files (they are too big, and store using Git Lfs), you can manually download the ascii raster files from [here](https://github.com/thomas-wsbd/modelkou/tree/master/data/kou) select the ``.asc`` file you want to download and click on ``Download`` in the following tab. 

## Installing software
Depending on what you will be doing coming days the following software could be usefull. Mind your computer specs and find the correct download using the following links;

- [QGIS](https://www.qgis.org/nl/site/forusers/download.html), A Geographic Information System (GIS), when working with geographic data, like vectors and rasters, you can use ``kou.qgz`` to check out the created grid;
- [ModFlow6](https://www.usgs.gov/software/modflow-6-usgs-modular-hydrologic-model), the groundwater modeling software we will be using, see ``ex1.ipynb`` for basic example;
- [Gridgen](https://www.usgs.gov/software/gridgen-a-program-generating-unstructured-finite-volume-grids), to create unstructured grids for modflow, see ``ex2.ipynb`` for example;
- [Anaconda](https://www.anaconda.com/distribution/), python distribution software, select the ``python 3.7`` version;

## Setting up your python environment
In order to check out the ``flopy`` examples, you'll need to install some python packages. This can be achieved using the requirements.txt in this repository. Go to your anaconda prompt and type, ``conda install --file <location of requirements.txt>``, this will start the installation of the required packages.  
