[![DOI](https://zenodo.org/badge/492086150.svg)](https://zenodo.org/badge/latestdoi/492086150)

# MEM_manuscript
Cloud fraction and temperature data used in "Distribution and Local Time Variability of Aphelion Equatorial Mesospheric Clouds."

## Data
Cloud fraction data: `data/cloud_fractions.nc`
Temperature data: `data/binned_temperatures.nc`

Each are have dimensions in Ls, latitude, altitude local time (day, night), direction (corresponding to MCS aziumth directions: "180"=in-track, "090"=left cross-track, "270"=right cross-track). Cloud fractions also have a channel dimension (corresponding to MCS spectral channels: A2 and A6). Temperature variables are the mean (`Tmean`), standard deviation (`Tstd`), probability below the CO2 frost point (`P(T<Tc)`), and CO2 frost point temperature (`Tc`).

## Notebook
Code used to generate the manuscript figures is found in `generate_figures.ipynb`. The first cell installs the required packages. You may want to create a virtual environment first: `python3 -m venv env`. 
