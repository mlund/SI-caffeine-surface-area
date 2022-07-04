[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/SI-caffeine-surface-area/HEAD)

# Electronic Notebook: Surface Area Description of Salting-in and Salting-out of Caffeine

This is supporting information for the scientific manuscript by _Hervø-Hansen et al._ (_????_, 2022, doi: [doi](https://doi.org/10.1039/D1CP04129K)) on the usage of multi-scale computer simulations combined with vapor-pressure osmometry on caffeine solutions to reveal that a SASA description captures a rich set of molecular driving forces in tertiary solutions at changing solute and osmolyte concentrations. All figures within the analyis are publication ready and can be reproduced by running the provided Jupyter notebooks (`.ipynb`). For running the simulation we recommend you clone the repository, else the original dataset can be analyzed through the use of [Binder](https://mybinder.org), which will open the notebook in an executable environment and can be accessed [here](https://mybinder.org/v2/gh/mlund/SI-caffeine-surface-area/HEAD).

## Layout

Description of the directory layout.

- `.zenodo.json` This contains metedata for the Zenodo deposition. When you on github make a new
  _Release_, this can trigger a Zenodo build. To learn more about the available datafields, see
  [here](https://developers.zenodo.org/?python#depositions).
- `README.md` This is the file you're viewing right now. You may want to edit the **Binder** badge above to match your repository.
- `environment.yml` Defines the required Python packages using conda. It's a good idea to try to set specific versions of your
  dependencies as their behavior may change in the future.
  The environment is currently called `my_environment` and you'll likely want to rename it to something less generic.

## Requirements

To run the Notebooks online, click on the _Launch Binder_ logo above. Alternatively, if you want to run on your own computer,
install python using e.g. [Miniconda](https://conda.io/miniconda.html) or [Anaconda](https://docs.conda.io))
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
    conda env create -f environment.yml
    source activate SASACaffeine
    jupyter-notebook
```
