# humboldt-for-eco-survey-data

This repository contains script to infer non-detection of target taxa of a marine ecological survey dataset using Humboldt Extension.

## Repo structure 

```
.
├── README.md           
├── humboldt.Rproj      : R project file
├── images              : directory to store images used in Rmd file
├── renv                : renv files for dependencies
├── renv.lock           : describe the state of project's library
└── src
    ├── mapping.Rmd     : Rmarkdown file of the code 
    └── mapping.html    : HTML of knitted Rmd files 
```

Knitted Rmarkdown can be rendered at [https://raw.githack.com/ymgan/humboldt-for-eco-survey-data/main/src/mapping.html](https://raw.githack.com/biodiversity-aq/humboldt-for-eco-survey-data/main/src/mapping.html)

## Getting started

This project uses [renv](https://rstudio.github.io/renv/) to manage the virtual environment. If dependencies are not automatically installed by `renv` when you open `humboldt.Rproj`, please try the following command.

```
renv::restore()
```
