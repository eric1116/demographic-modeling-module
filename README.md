# demographic-modeling-module

Demographic modeling module ideas for ArcGIS Python API

## Getting Started

From the project directory, create an environment with all dependencies installed and linked.

```
> make env
```

This creates a conda environment cloned from the ArcGIS Pro default environment `arcgispro-py3`, and names this new
environment `demographic-modeling`, and also activates this environment for ArcGIS Pro at the same time. If opening
a new command prompt, you can easily activate this environment using the command.. 

```
> make env_activate
``` 

...which simply calls `> activate demographic-modeling` for you.

From there, the example workflow can be found in the notebooks in the `./notebooks` directory of the project, and
explored by simply calling.

```
> make jupyter
```

This command takes care of activating the environment, and also starting jupyter lab, so you can get started quickly.

## Project Organization
------------
```
    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data`
    ├── make.bat           <- Windows batch file with commands like `make data`
    ├── setup.py           <- Setup script for the library (dm)
    ├── .env               <- Any environment variables here - created as part of project creation, 
    │                         but NOT syncronized with git repo for project.                
    ├── README.md          <- The top-level README for developers using this project.
    ├── arcgis             <- Root location for ArcGIS Pro project created as part of
    │   │                     data science project creation.
    │   ├── demographic-modeling-module.aprx <- ArcGIS Pro project.    
    │   └── demographic-modeling-module.tbx  <- ArcGIS Pro toolbox associated with the project.
    ├── scripts            <- Put scripts to run things here.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   │   └── interim.gdb
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   │   └── processed.gdb
    │   └── raw            <- The original, immutable data dump.
    │       └── raw.gdb
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    ├── notebooks          <- Jupyter notebooks. Naming convention is a 2 digits (for ordering),
    │   │                     descriptive name. e.g.: 01_exploratory_analysis.ipynb
    │   └── notebook_template.ipynb
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    ├── environment.yml    <- The requirements file for reproducing the analysis environment. This 
    │                         is generated by running `conda env export > environment.yml` or
    │                         `make env_export`.                         
    └── src                <- Source code for use in this project.
        └── dm <- Library containing the bulk of code used in this 
                                                  project. 
```

<p><small>Project based on the <a target="_blank" href="https://github.com/knu2xs/cookiecutter-geoai">cookiecutter GeoAI project template</a>. This template, in turn, is simply an extension and light modification of the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
