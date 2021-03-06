# phenofit2

[![Travis Build
Status](https://travis-ci.org/kongdd/phenofit2.svg?branch=master)](https://travis-ci.org/kongdd/phenofit2)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/kongdd/phenofit2?branch=master&svg=true)](https://ci.appveyor.com/project/kongdd/phenofit2)
[![codecov](https://codecov.io/gh/kongdd/phenofit2/branch/master/graph/badge.svg)](https://codecov.io/gh/kongdd/phenofit2)
[![License](http://img.shields.io/badge/license-GPL%20%28%3E=%202%29-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/gpl-2.0.html)
[![CRAN](http://www.r-pkg.org/badges/version/phenofit2)](https://cran.r-project.org/package=phenofit2)
[![total](http://cranlogs.r-pkg.org/badges/grand-total/phenofit2)](https://www.rpackages.io/package/phenofit2)
[![monthly](http://cranlogs.r-pkg.org/badges/phenofit2)](https://www.rpackages.io/package/phenofit2)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3605560.svg)](https://doi.org/10.5281/zenodo.3605560)

The second generation of phenofit cooperating with Julia.

-   `phenofit` combine merits of TIMESAT and phenopix
-   A simple and stable growing season dividing methods was proposed
-   Provide a practical snow elimination method, based on Whittaker
-   7 curve fitting methods and 4 phenology extraction methods
-   We add parameters boundary for every curve fitting methods according
    to their ecological meaning.
-   `optimx` is used to select best optimization method for different
    curve fitting methods.

***Task lists***

-   [ ] Test the performance of `phenofit` in multiple growing season
    regions (e.g. the North China Plain);
-   [ ] Uncertainty analysis of curve fitting and phenological metrics;
-   [x] shiny app has been moved to
    [phenofit.shiny](https://github.com/kongdd/phenofit.shiny);
-   [x] Complete script automatic generating module in shinyapp;
-   [x] `Rcpp` improve double logistics optimization efficiency by 60%;
-   [x] Support spatial analysis;
-   [x] Support annual season in curve fitting;
-   [x] flexible fine fitting input ( original time-series or smoothed
    time-series by rough fitting).
-   [x] Asymmetric of Threshold method

![title](man/Figure/Figure1_phenofit_flowchart.svg)

*<u>Figure 1. The flowchart of phenology extraction in `phenofit`.</u>*

# Installation

You can install phenofit2 from github with:

``` r
# install.packages("devtools")
devtools::install_github("kongdd/phenofit2")
```

# **References**

> \[1\] Kong, D., Zhang, Y., Wang, D., Chen, J., & Gu, X. (2020).
> Photoperiod Explains the Asynchronization Between Vegetation Carbon
> Phenology and Vegetation Greenness Phenology. *Journal of Geophysical
> Research: Biogeosciences*, 125(8), e2020JG005636.
> <https://doi.org/10.1029/2020JG005636>
>
> \[2\] Kong, D., Zhang, Y., Gu, X., & Wang, D. (2019). A robust method
> for reconstructing global MODIS EVI time series on the Google Earth
> Engine. *ISPRS Journal of Photogrammetry and Remote Sensing*, 155,
> 13–24.
>
> \[3\] Kong, D., (2020). R package: A state-of-the-art Vegetation
> Phenology extraction package, `phenofit` version 0.2.6,
> <https://doi.org/10.5281/zenodo.3605560>
>
> \[4\] Zhang, Q., Kong, D., Shi, P., Singh, V.P., Sun, P., 2018.
> Vegetation phenology on the Qinghai-Tibetan Plateau and its response
> to climate change (1982–2013). Agric. For. Meteorol. 248, 408–417.
> <https://doi.org/10.1016/j.agrformet.2017.10.026>

# Acknowledgements

Keep in mind that this repository is released under a GPL2 license,
which permits commercial use but requires that the source code (of
derivatives) is always open even if hosted as a web service.
