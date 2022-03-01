# ICESat-2 Water Superelevation Finder

### James (Jake) Gearon, Department of Earth & Atmospheric Sciences, Indiana University
##### [Github](https://github.com/jameshgrn) | [Medium](https://medium.com/@jake.gearon_34983) | [Twitter](https://twitter.com/JakeGearon) | [LinkedIn](https://www.linkedin.com/in/jake-gearon-742767148/) | [Website](https://jameshgrn.github.io) 

---

Jupyter Notebooks for ICESat-2 Water Superelevation, use the notebook CONSOLE-SWOT.ipynb, the CONSOLE-SWOT dev notebook is currently a work in progress.

To install these notebooks locally:
1. create a new conda environment using the provided dependencies
   1. Clone this repo into a local folder
      1. `git clone https://github.com/jameshgrn/IS2_Water_SE.git`
      2. `cd IS2_Water_SE`
   2. Create an environment from the provident `environment.yml` file:
      1. `conda create -f environment.yml`
         - _note: this will take awhile, go grab a coffee..._
      2. `conda activate IS2SE`
   3. Launch Jupyter Notebooks
      1. `cd IS2_Water_SE`
      2. `jupyter notebook`

To launch this notebook without downloading it locally, use [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jameshgrn/IS2_Water_SE/HEAD?labpath=https%3A%2F%2Fgithub.com%2Fjameshgrn%2FIS2_Water_SE%2Fblob%2Fmain%2FConsole-SWOT.ipynb)
* _note: this will fail if the data is more than 2GB, making it only good for demo purposes!_
