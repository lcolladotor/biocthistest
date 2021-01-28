
<!-- README.md is generated from README.Rmd. Please edit that file -->

# biocthistest

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![BioC
status](http://www.bioconductor.org/shields/build/release/bioc/biocthistest.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/biocthistest)
[![R-CMD-check-bioc](https://github.com/lcolladotor/biocthistest/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/lcolladotor/biocthistest/actions)
[![Codecov test
coverage](https://codecov.io/gh/lcolladotor/biocthistest/branch/master/graph/badge.svg)](https://codecov.io/gh/lcolladotor/biocthistest?branch=master)
<!-- badges: end -->

The goal of `biocthistest` is to …

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `biocthistest` using
from [Bioconductor](http://bioconductor.org/) the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("biocthistest")
```

And the development version from [GitHub](https://github.com/) with:

``` r
BiocManager::install("lcolladotor/biocthistest")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("biocthistest")
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

## Citation

Below is the citation output from using `citation('biocthistest')` in R.
Please run this yourself to check for any updates on how to cite
**biocthistest**.

``` r
print(citation('biocthistest'), bibtex = TRUE)
#> 
#> Collado-Torres L (2021). _Ejemplo de biocthis para ConectaR2021_. doi:
#> 10.18129/B9.bioc.biocthistest (URL:
#> https://doi.org/10.18129/B9.bioc.biocthistest),
#> https://github.com/lcolladotor/biocthistest/biocthistest - R package
#> version 0.99.0, <URL:
#> http://www.bioconductor.org/packages/biocthistest>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {Ejemplo de biocthis para ConectaR2021},
#>     author = {Leonardo Collado-Torres},
#>     year = {2021},
#>     url = {http://www.bioconductor.org/packages/biocthistest},
#>     note = {https://github.com/lcolladotor/biocthistest/biocthistest - R package version 0.99.0},
#>     doi = {10.18129/B9.bioc.biocthistest},
#>   }
#> 
#> Collado-Torres L (2021). "Ejemplo de biocthis para ConectaR2021."
#> _bioRxiv_. doi: 10.1101/TODO (URL: https://doi.org/10.1101/TODO), <URL:
#> https://www.biorxiv.org/content/10.1101/TODO>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     title = {Ejemplo de biocthis para ConectaR2021},
#>     author = {Leonardo Collado-Torres},
#>     year = {2021},
#>     journal = {bioRxiv},
#>     doi = {10.1101/TODO},
#>     url = {https://www.biorxiv.org/content/10.1101/TODO},
#>   }
```

Please note that the `biocthistest` was only made possible thanks to
many other R and bioinformatics software authors, which are cited either
in the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the `biocthistest` project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

## Development tools

-   Continuous code testing is possible thanks to [GitHub
    actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
    through *[usethis](https://CRAN.R-project.org/package=usethis)*,
    *[remotes](https://CRAN.R-project.org/package=remotes)*, and
    *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)*
    customized to use [Bioconductor’s docker
    containers](https://www.bioconductor.org/help/docker/) and
    *[BiocCheck](https://bioconductor.org/packages/3.12/BiocCheck)*.
-   Code coverage assessment is possible thanks to
    [codecov](https://codecov.io/gh) and
    *[covr](https://CRAN.R-project.org/package=covr)*.
-   The [documentation website](http://.github.io/biocthistest) is
    automatically updated thanks to
    *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
-   The code is styled automatically thanks to
    *[styler](https://CRAN.R-project.org/package=styler)*.
-   The documentation is formatted thanks to
    *[devtools](https://CRAN.R-project.org/package=devtools)* and
    *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.12/biocthis)*.
