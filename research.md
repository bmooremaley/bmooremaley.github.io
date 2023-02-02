---
title: My research
---

## Doctoral thesis project

**Thesis:** *Wind-driven upwelling and nutrient supply in a productive estuarine sea*. (2022) doi:<a href="https://doi.org/10.14288/1.0418447" target="_blank">10.14288/1.0418447</a>\
**Supervisor:** Susan Allen <a href="https://www.eoas.ubc.ca/people/susanallen" target="_blank">university profile</a>\
**Institution:** University of British Columbia

<figure style="width: 250px; margin-top: 0px; margin-bottom: 0px" class="align-right">
<img alt="" src="{{ site.url }}{{ site.baseurl }}/assets/images/thesis-img.png">
<figcaption>Simulated surface nitrate concentration in the Strait of Georgia during a summer northwesterly wind event. The red plumes originating along the northeast coastline are upwelled nitrate.</figcaption>
</figure>

For my doctoral thesis project, I explored wind-driven circulation and upwelling in the Salish Sea on the US/Canadian Pacific coast using a high-resolution configuration of the <a href="https://www.nemo-ocean.eu" target="_blank">NEMO</a> ocean model called [SalishSeaCast](#salishseacast). Ocean upwelling is an important source of nutrients for phytoplankton, and ocean circulation affects the trajectories of pollutants and floating objects. I found that upwelling occurs frequently in the largest basin of the Salish Sea, the Strait of Georgia, and that upwelling depth is controlled by a combination of wind speed and stratification strength. This phenomenon presents an important link between climate and seasonal productivity that may have implications for higher organisms like Pacific salmon.

I used a combination of methods and resources to complete this project including:
   * gridded meteorological forcing data sets and oceanographic sampling data
   * collaboratively-produced long hindcasts of SalishSeaCast
   * my own idealized and experimental NEMO simulations
   * post-processing data methods including principal component analysis and spectral analysis
   * theoretical models

Additionally, I used several software and computational tools including:
   * Python and data processing/analysis/visualization libraries like NumPy, SciPy, Xarray and Matplotlib
   * Fortran-based NEMO source code
   * netCDF and the NCO command line tools
   * high-performance computing and parallel processing on remote clusters

My doctoral research was supported by the Canadian Marine Environmental Observation, Prediction and Response Network (<a href="https://meopar.ca" target="_blank">MEOPAR</a>), <a href="https://www.oceannetworks.ca" target="_blank">Ocean Networks Canada</a>, the <a href="https://psf.ca" target="_blank">Pacific Salmon Foundation</a> and the <a href="https://alliancecan.ca" target="_blank">Digital Research Alliance of Canada</a>.


## SalishSeaCast

<figure style="width: 350px; margin-top: 0px; margin-bottom: 0px" class="align-right">
<img alt="" src="{{ site.url }}{{ site.baseurl }}/assets/images/salishseacast-img.png">
<figcaption>Map of the Salish Sea region showing the SalishSeaCast model domain (gray) and bathymetry (contoured).</figcaption>
</figure>

I have also contributed to the ongoing development of the SalishSeaCast model. SalishSeaCast is a collaborative modelling project based at the University of British Columbia with a range of applications including semi-operational forecasting, storm surge, circulation, oil spills, microplastics, lower trophic ecosystem dynamics and ocean acidification.

Details about the project and links to results and additional resources can be found at <a href="https://salishsea.eos.ubc.ca/nemo/" target="_blank">https://salishsea.eos.ubc.ca/nemo/</a>.

My most recent contribution to SalishSeaCast was an evaluation of the surface velocity, temperature and salinity fields against surface <a href="https://drifters.eoas.ubc.ca/" target="_blank">drifter</a> and <a href="https://marinesurvivalproject.com/research_activity/list/citizen-science-program/" target="_blank">CTD</a> data sets, and a tuning of the default NEMO surface wave breaking parameterization. This work is summarized in Chapter 2 of my Ph.D. thesis.

Additionally, I have contributed Python code to the <a href="https://salishsea-meopar-tools.readthedocs.io" target="_blank">SalishSeaTools</a> package, and have developed work flows for various team research tasks such as <a href="https://nbviewer.org/github/UBC-MOAD/PythonNotes/blob/main/OceanParcelsRecipes.ipynb" target="_blank">particle tracking</a>, <a href="https://nbviewer.org/github/UBC-MOAD/PythonNotes/blob/main/ONC_recipes.ipynb" target="_blank">downloading data</a> and <a href="https://nbviewer.org/github/UBC-MOAD/PythonNotes/blob/main/cartopy_recipes.ipynb" target="_blank">mapping</a>.