# la-covid-challenge

Examples for LA COVID-19 Data Challenge.

Joel McCune on 

- [LinkedIn](https://www.linkedin.com/in/joelmccune/)
- [the World Wide Web blogosphere](https://joelmccune.com)

## LA Challenge Examples and Resources

### [Examples](./notebooks)

- [Feature Layer](./notebooks/01-access-feature-service.ipynb)
- [Layer and Dataframe from Item ID](./notebooks/02-layer-from-item-id.ipynb)
- [Socrata to Spatial](./notebooks/03-socrata-geocoding.ipynb)

### Resources

- [LA COVID Challenge Page](https://grmds.org/2020challenge)
- [GeoAI Cookiecutter Template](https://esri.github.io/geoai-cookiecutter/)
- [ArcGIS Developers](https://developers.arcgis.com/)
	- [Sign-Up](https://developers.arcgis.com/sign-up/)
- [ArcGIS Python API](https://developers.arcgis.com/python/)
	- [Guide (samples)](https://developers.arcgis.com/python/guide/)
	- [Samples (complex notebooks)](https://developers.arcgis.com/python/sample-notebooks/)
- [Living Atlas](https://livingatlas.arcgis.com/en)
- [Esri Demographics Layers](http://goto.arcgisonline.com/demographics9/USA_Demographics_and_Boundaries_2019)
- [Location-Based Serices for Analysis](https://developers.arcgis.com/rest/location-based-services/) (bindings are in Python API, but REST documentation is really good)

## Project Organization
------------
```
    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data`
    ├── make.bat           <- Windows batch file with commands like `make data`
    ├── setup.py           <- Setup script for the library (la_challenge)
    ├── .env               <- Any environment variables here - created as part of project creation, 
    │                         but NOT syncronized with git repo for project.                
    ├── README.md          <- The top-level README for developers using this project.
    ├── arcgis             <- Root location for ArcGIS Pro project created as part of
    │   │                     data science project creation.
    │   ├── la-covid-challenge.aprx <- ArcGIS Pro project.    
    │   └── la-covid-challenge.tbx  <- ArcGIS Pro toolbox associated with the project.
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
        └── la_challenge <- Library containing the bulk of code used in this 
                                                  project. 
```

<p><small>Project based on the <a target="_blank" href="https://github.com/knu2xs/cookiecutter-geoai">cookiecutter GeoAI project template</a>. This template, in turn, is simply an extension and light modification of the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
