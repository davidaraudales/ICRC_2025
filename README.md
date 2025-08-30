# The Trinity-One PeV Neutrino Observatory
This repository is meant to help reproduce results presented in 

D.A. Raudales, A. N. Otte, for the Trinity Collaboration, The Trinity-One PeV Neutrino Telescope, 39th International Cosmic Ray Conference (ICRC2025), PoS ICRC 2025, 1136 (2025)

# Basic Information

The repository has five main jupyter notebooks, each of which can be run mostly independent of each other. The necessary functions should be defined inside each jupyter notebook so that one doesn't depend on the other. 

The effective area calculations are done using the trinity performance code which can be cloned from https://github.gatech.edu/aotte6/Trinity. The .root files resulting from running the Trinity Performance Code for a 60 degree FoV telescope and a 360 degree FoV telescope are stored in effective_areas/files

files folder also contains digitized models from different references included in each jupyter notebook. 
