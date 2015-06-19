derfinderHelper
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
biocLite(c("IRanges", "GenomicRanges"))

## derfinderHelper itself
library(devtools)
install_github("lcolladotor/derfinderHelper")
```

# Citation

Use [derfinder's citation](https://github.com/lcolladotor/derfinder#citation) information.
