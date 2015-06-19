derfinderHelper [![Build Status](https://travis-ci.org/lcolladotor/derfinderHelper.svg?branch=master)](https://travis-ci.org/lcolladotor/derfinderHelper)
===============

Helper package for [derfinder](https://github.com/lcolladotor/derfinder).

# Installation instructions

Get R 3.1 or newer from [CRAN](http://cran.r-project.org/).

```S
## If needed
install.packages("devtools")

## Pre-requisites from CRAN
install.packages("Matrix")

## Pre-requisites from Bioconductor
source("http://bioconductor.org/biocLite.R")
biocLite(c("IRanges", "S4Vectors"))

## derfinderHelper itself
library("devtools")
install_github("lcolladotor/derfinderHelper")
```

# Citation

Use [derfinder's citation](https://github.com/lcolladotor/derfinder#citation) information.


## Travis CI

This package is automatically tested thanks to [Travis CI](travis-ci.org) and [r-travis](https://github.com/craigcitro/r-travis). If you want to add this to your own package use:

```R
## Use devtools to create the .travis.yml file
library('devtools')
use_travis('yourPackage')

## Read https://github.com/craigcitro/r-travis/wiki to configure .travis.yml appropriately

## Add a status image by following the info at http://docs.travis-ci.com/user/status-images/
```