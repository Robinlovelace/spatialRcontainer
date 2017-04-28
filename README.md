# spatialRcontainer

Setup script for container-based spatial analysis in R. Installs SQLite3,
Spatialite, GDAL, and Geos, along with both R and python (see here for full list
of standard packages). Most R libraries necessary for package development are
included, along with packages for geospatial analysis including `sf`, `sp`,
`spatstat`, `spdep`, `maptools`, and `tmap` (see here for full list of R
packages). Python 3 is installed along with `numpy`, `scipy`, `pandas` and
others (see here for full list).

## Usage

To use this script, run the following from the terminal on Ubuntu:


```bash
# not tested
wget https://github.com/mpadge/spatialRcontainer/archive/master.zip
unzip master.zip
chmod ... 
bash spatialRcontainer/setup.sh
```

**Not yet in a working state: do not use**
