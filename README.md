
<!-- README.md is generated from README.Rmd. Please edit that file -->

# derfinderHelper

<!-- badges: start -->

[![Lifecycle:
stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![Bioc release
status](http://www.bioconductor.org/shields/build/release/bioc/derfinderHelper.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/derfinderHelper)
[![Bioc devel
status](http://www.bioconductor.org/shields/build/devel/bioc/derfinderHelper.svg)](https://bioconductor.org/checkResults/devel/bioc-LATEST/derfinderHelper)
[![Bioc downloads
rank](https://bioconductor.org/shields/downloads/release/derfinderHelper.svg)](http://bioconductor.org/packages/stats/bioc/derfinderHelper/)
[![Bioc
support](https://bioconductor.org/shields/posts/derfinderHelper.svg)](https://support.bioconductor.org/tag/derfinderHelper)
[![Bioc
history](https://bioconductor.org/shields/years-in-bioc/derfinderHelper.svg)](https://bioconductor.org/packages/release/bioc/html/derfinderHelper.html#since)
[![Bioc last
commit](https://bioconductor.org/shields/lastcommit/devel/bioc/derfinderHelper.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/derfinderHelper/)
[![Bioc
dependencies](https://bioconductor.org/shields/dependencies/release/derfinderHelper.svg)](https://bioconductor.org/packages/release/bioc/html/derfinderHelper.html#since)
[![Codecov test
coverage](https://codecov.io/gh/leekgroup/derfinderHelper/branch/devel/graph/badge.svg)](https://codecov.io/gh/leekgroup/derfinderHelper?branch=devel)
[![R build
status](https://github.com/leekgroup/derfinderHelper/actions/workflows/check-bioc.yml/badge.svg)](https://github.com/leekgroup/derfinderHelper/actions/workflows/check-bioc.yml)
[![GitHub
issues](https://img.shields.io/github/issues/leekgroup/derfinderHelper)](https://github.com/leekgroup/derfinderHelper/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/leekgroup/derfinderHelper)](https://github.com/leekgroup/derfinderHelper/pulls)
<!-- badges: end -->

Helper package for
[derfinder](http://www.bioconductor.org/packages/derfinder).

## Documentation

For more information about `derfinderHelper` check the vignettes
[through Bioconductor](http://bioconductor.org/packages/derfinderHelper)
or at the [documentation
website](http://leekgroup.github.io/derfinderHelper).

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `derfinderHelper` from
[Bioconductor](http://bioconductor.org/) using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("derfinderHelper")
```

## Citation

Below is the citation output from using `citation('derfinderHelper')` in
R. Please run this yourself to check for any updates on how to cite
**derfinderHelper**.

``` r
print(citation("derfinderHelper"), bibtex = TRUE)
#> To cite package 'derfinderHelper' in publications use:
#> 
#>   Collado-Torres L, Jaffe AE, Leek JT (2017). _derfinderHelper:
#>   derfinder helper package_. doi:10.18129/B9.bioc.derfinderHelper
#>   <https://doi.org/10.18129/B9.bioc.derfinderHelper>,
#>   https://github.com/leekgroup/derfinderHelper - R package version
#>   1.35.0, <http://www.bioconductor.org/packages/derfinderHelper>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {derfinderHelper: derfinder helper package},
#>     author = {Leonardo Collado-Torres and Andrew E. Jaffe and Jeffrey T. Leek},
#>     year = {2017},
#>     url = {http://www.bioconductor.org/packages/derfinderHelper},
#>     note = {https://github.com/leekgroup/derfinderHelper - R package version 1.35.0},
#>     doi = {10.18129/B9.bioc.derfinderHelper},
#>   }
#> 
#>   Collado-Torres L, Nellore A, Frazee AC, Wilks C, Love MI, Langmead B,
#>   Irizarry RA, Leek JT, Jaffe AE (2017). "Flexible expressed region
#>   analysis for RNA-seq with derfinder." _Nucl. Acids Res._.
#>   doi:10.1093/nar/gkw852 <https://doi.org/10.1093/nar/gkw852>,
#>   <http://nar.oxfordjournals.org/content/early/2016/09/29/nar.gkw852>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     title = {Flexible expressed region analysis for RNA-seq with derfinder},
#>     author = {Leonardo Collado-Torres and Abhinav Nellore and Alyssa C. Frazee and Christopher Wilks and Michael I. Love and Ben Langmead and Rafael A. Irizarry and Jeffrey T. Leek and Andrew E. Jaffe},
#>     year = {2017},
#>     journal = {Nucl. Acids Res.},
#>     doi = {10.1093/nar/gkw852},
#>     url = {http://nar.oxfordjournals.org/content/early/2016/09/29/nar.gkw852},
#>   }
```

Please note that the `derfinderHelper` was only made possible thanks to
many other R and bioinformatics software authors, which are cited either
in the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the derfinderHelper project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

## Development tools

- Continuous code testing is possible thanks to [GitHub
  actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
  through *[usethis](https://CRAN.R-project.org/package=usethis)*,
  *[remotes](https://CRAN.R-project.org/package=remotes)*,
  *[sysreqs](https://github.com/r-hub/sysreqs)* and
  *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)* customized
  to use [Bioconductor’s docker
  containers](https://www.bioconductor.org/help/docker/) and
  *[BiocCheck](https://bioconductor.org/packages/3.17/BiocCheck)*.
- Code coverage assessment is possible thanks to
  [codecov](https://codecov.io/gh) and
  *[covr](https://CRAN.R-project.org/package=covr)*.
- The [documentation
  website](http://leekgroup.github.io/derfinderHelper) is automatically
  updated thanks to
  *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
- The code is styled automatically thanks to
  *[styler](https://CRAN.R-project.org/package=styler)*.
- The documentation is formatted thanks to
  *[devtools](https://CRAN.R-project.org/package=devtools)* and
  *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.
