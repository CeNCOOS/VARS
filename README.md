# VARS

Code for accessing and obtaining data from the [VARS database](https://www.mbari.org/products/research-software/video-annotation-and-reference-system-vars/) and converting it to [Darwin Core Standard format](https://dwc.tdwg.org/terms/#occurrence).

This is old development code. For a more polished version, look in the vars-dwc repo.

**Author:** Diana LaScala-Gruenewald <br>
**Code:** Python 3.7

## Folders and files currently included:
- **CeNCOOS_VARS_in_CBNMS_GBNMS** - Jupyter notebook containing code querying VARS for any annotations within Cordell Bank or Greater Farallones National Marine Sanctuaries
- **VARS.py** - Python module for accessing and querying the VARS database <br>
- **VARS_2001_WoRMS_log.txt** - Text file containing concept names that didn't match on [WoRMS](http://www.marinespecies.org/) when searching for all annotations from 2001
- **VARS_2001_conversion.ipynb** - Jupyter notebook containing code to convert one year of VARS annotations to DwC. This is the current version of the conversion code that should be used for any further work.
- **VARS_get_data_example.ipynb** - Jupyter notebook containing example code for how to query VARS
- **VARS_six-species_conversion.ipynb** - Jupyter notebook containing initial code to convert VARS annotations to DwC
- **WoRMS.py** - Python module for querying the [World Register of Marine Species (WoRMS) REST API](http://www.marinespecies.org/rest/)
- **eDNA_VARS_queries.ipynb** - Jupyter notebook containing code querying VARS for annotations from Spring and Fall CANON 2019 cruises for Francisco Chavez
- **eDNA_VARS_annotations_by_depth.ipynb** - Jupyter notebook containing code querying VARS for all annotations from particular species of interest observed near M1 for Francsico Chavez. Also plots annotation locations on a map, number of annotations by depth category, number of annotations by depth category through time as a heatmap.

