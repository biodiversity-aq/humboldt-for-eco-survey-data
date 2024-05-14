# humboldt-for-eco-survey-data

This repository contains script to infer non-detection of target taxa of a marine ecological survey dataset using Humboldt Extension.

## Repo structure 

```
.
├── README.md
├── humboldt.Rproj      : R project file
├── images              : directory to store images used in Rmd file
├── output              : directory to store output files
├── renv                : renv files for dependencies
├── renv.lock           : describes the state of project's library
└── src                 : directory of Rmd and knitted html files
```

Knitted Rmarkdown can be rendered at:

- [mapping.html](https://raw.githack.com/biodiversity-aq/humboldt-for-eco-survey-data/main/src/mapping.html)
- [generate-humboldt-ext.html](https://raw.githack.com/biodiversity-aq/humboldt-for-eco-survey-data/main/src/create-humboldt-ext.html)

## Getting started

This project uses [renv](https://rstudio.github.io/renv/) to manage the virtual environment. If dependencies are not automatically installed by `renv` when you open `humboldt.Rproj`, please try the following command.

```
renv::restore()
```
