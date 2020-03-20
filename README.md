# TTC Subway Delay Analysis

This repository contains my analysis (and data cleanup) of the [TTC subway delay dataset](https://open.toronto.ca/dataset/ttc-subway-delay-data/), as published on City of Toronto's Open Data Portal. To view the rendered results on NBViewer:

- [Data prep](https://nbviewer.jupyter.org/github/x249wang/ttc_subway_delays/blob/master/1_data_prep.ipynb)
- [Data analysis](https://nbviewer.jupyter.org/github/x249wang/ttc_subway_delays/blob/master/2_data_analysis.ipynb)

To launch an interactive copy of the notebooks on Binder, press this button:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/x249wang/ttc_subway_delays/master)

To install locally, everything needed to run the notebooks, including helper data (e.g. spelling correction lookup table, in the `helper_data/` folder) and Python environment dependencies (`enviornment.yml`), can be found within this repo. The first notebook (`1_data_prep.ipynb`) generates the processed data and saves it to the working directory, which is then used as input for the second notebook for analysis (`2_data_analysis.ipynb`). 
