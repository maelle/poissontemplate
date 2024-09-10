
# poissontemplate

<!-- badges: start -->
[![R-CMD-check](https://github.com/poissonconsulting/poissontemplate/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/poissonconsulting/poissontemplate/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

poissontemplate provides a custom [pkgdown](https://pkgdown.r-lib.org/) template for Poisson consulting packages. 
Please don’t use it for your own package.

## Setup

### Register the use of the template

In `_pkgdown.yml` that you can create through `usethis::use_pkgdown()` if absent,
have these lines:

```yaml
template:
  package: poissontemplate
```

### For continuous integration

For all sites, ensure that DESCRIPTION contains:

```yaml
Config/Needs/website: poissonconsulting/poissontemplate
```

by editing the file manually or by running `desc::desc_set("Config/Needs/website", "poissonconsulting/poissontemplate")`.


## Installation

You can install the development version of poissontemplate from [GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("poissonconsulting/poissontemplate")
```

## Relevant resources

- pkgdown documentation about theming: https://pkgdown.r-lib.org/articles/customise.html#theming
- pkgdown documentation on template packages: https://pkgdown.r-lib.org/articles/customise.html#template-packages
