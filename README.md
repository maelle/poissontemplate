
# poissontemplate

<!-- badges: start -->
[![R-CMD-check](https://github.com/poissonconsulting/poissontemplate/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/poissonconsulting/poissontemplate/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

poissontemplate provides a custom [pkgdown](https://pkgdown.r-lib.org/) template for Poisson consulting packages. 
Please don’t use it for your own package.

## Installation

You can install the development version of poissontemplate from [GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("poissonconsulting/poissontemplate")
```

## Setup

In every package where you need to set up poissontemplate usage, run

``` r
poissontemplate::use_poisson_pkgdown()
```

Then contact the owner of Poisson consulting Plausible account to have a domain set up.
Once it is done, amend and add the following lines to the pkgdown configuration file:

```yaml
includes:
    in_header: |
      <script defer data-domain="{YOUR DOMAIN},poissonconsulting.ca" src="https://plausible.io/js/plausible.js"></script>  
```

## Relevant resources

- pkgdown documentation about theming: https://pkgdown.r-lib.org/articles/customise.html#theming
- pkgdown documentation on template packages: https://pkgdown.r-lib.org/articles/customise.html#template-packages
