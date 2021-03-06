# click Binder badge to launch notebook on Binder (no need to install environment):
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/donatagiglio/test2/HEAD)
# Notebook: Investigating upper ocean variability during tropical cyclones and seasonal sea ice formation and melting: Argovis APIs exposed to co-locate oceanic and atmospheric datasets
# authors: Giovanni Seijo-Ellis, Donata Giglio, Sarah Purkey, Megan Scanderbeg, and Tyler Tucker
# Last edit on original version: 05/14/2021 9:25 pm MT
# Last edit on current REU version by dg: 06/02/2021 9:25 am MT
# contact: giovanni.seijo@colorado.edu
#  This notebook has been submitted to the EarthCube 2021 Annual Meeting.
# Purpose:
Argovis is a web app and database that allows easy access to Argo profile observations of the global ocean and other earth science datasets using a browser and/or via Application Programming Interfaces (APIs). This notebook serves two main purposes: (i) introducing two new APIs available to access National Hurricane Center tropical cyclone (TC) track data and sea-ice concentration from the Southern Ocean State Estimate (SOSE), and (ii) leverage the capabilities of these APIs with interactive educational activities suitable for courses in oceanography and air-sea interactions. In addition, the notebook serves as a basis for research applications of the two APIs, e.g. to co-locate these datasets with oceanic observations (e.g. profiles of ocean temperature and salinity from Argo) for interdisciplinary research at the interface of different climate system components: the ocean, the atmosphere and the cryosphere.
#
# INSTRUCTIONS ARE LISTED BELOW to create and environment from a .yml file, make that environment available when using jupyter, and start jupyter (if you start jupyter within the folder where your notebook is, you can then open the notebook and run it, after selecting the right kernel). Let me know how it goes!
#
# run these commands from the terminal (jupyter and conda need to be installed)
# conda env create -f environment.yml
# conda activate py_REU2021
# conda install -c anaconda ipykernel
# python -m ipykernel install --user --name=py_REU2021
# conda deactivate
# jupyter notebook & (then select the right kernel)
