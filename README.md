[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/SI-caffeine-surface-area/HEAD)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10122308.svg)](https://doi.org/10.5281/zenodo.10122308)

# Electronic Notebook: Salt Effects on Caffeine Across Concentration Regimes

This is supporting information for the scientific manuscript by _Hervø-Hansen et al._ (JPCB 2023, DOI: [doi](https://doi.org/10.1021/acs.jpcb.3c01085)) on the usage of multi-scale computer simulations combined with vapor-pressure osmometry on caffeine solutions to reveal that a SASA description captures a rich set of molecular driving forces in tertiary solutions at changing solute and osmolyte concentrations. All figures within the analyis are publication ready and can be reproduced by running the provided Jupyter notebooks (`.ipynb`). For running the simulation we recommend you clone the repository, else the original dataset can be analyzed through the use of [Binder](https://mybinder.org), which will open the notebook in an executable environment and can be accessed [here](https://mybinder.org/v2/gh/mlund/SI-caffeine-surface-area/HEAD).

## Requirements

To run the Notebooks online, click on the _Launch Binder_ logo above. Alternatively, if you want to run on your own computer,
install python using e.g. [Miniconda](https://conda.io/miniconda.html) or [Anaconda](https://docs.conda.io))
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
    conda env create -f environment.yml
    source activate SASACaffeine
    jupyter-notebook
```
