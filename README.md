
# poissontemplate

<!-- badges: start -->
[![R-CMD-check](https://github.com/maelle/poissontemplate/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/maelle/poissontemplate/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

poissontemplate provides a custom [pkgdown](https://pkgdown.r-lib.org/) template for Poisson consulting packages. 
Please don’t use it for your own package.

## Setup

For all sites, ensure that DESCRIPTION contains:

```yaml
Config/Needs/website: maelle/poissontemplate
```

by editing the file manually or by running `desc::desc_set("Config/Needs/website", "maelle/poissontemplate")`.


## Installation

You can install the development version of poissontemplate from [GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("maelle/poissontemplate")
```
