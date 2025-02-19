# admiralpeds <img src="man/figures/logo.png" align="right" width="200" style="margin-left:50px;"/>

<!-- badges: start -->

[![pharmaverse admiralpeds Badge](http://pharmaverse.org/shields/admiralpeds.svg)](https://pharmaverse.org)
[![CRAN status](https://www.r-pkg.org/badges/version/admiralpeds)](https://CRAN.R-project.org/package=admiralpeds)
[![Test Coverage](https://raw.githubusercontent.com/pharmaverse/admiralpeds/badges/main/test-coverage.svg)](https://github.com/pharmaverse/admiral/actions/workflows/code-coverage.yml)

<!-- badges: end -->

Pediatrics extension package for ADaM in R Asset Library `{admiral}`

## Purpose

To provide a complementary (to `{admiral}`) toolbox that enables users
to develop specifics for pediatric clinical trials.

## Installation

The package is available from CRAN and can be installed with:

```r
install.packages("admiralpeds")
```

To install the development version of the package from GitHub run:

```r
# install.packages("devtools")
devtools::install_github("pharmaverse/admiralpeds")
```

### Dependencies

The latest version of the package works with the latest versions of the
packages stated in `DESCRIPTION`.

If a previous version of the package should be used, it is recommended
to use latest version of the dependencies at the point of time when the
previous version of {admiralpeds} was released.

## Scope

-   Build a toolbox of re-usable functions and utilities to create
    pediatrics-specific ADaM datasets in R in a modular manner.
-   All functions are created based upon the ADaM Implementation Guide
    and aim to facilitate the programming of ADaM dataset standards.
-   Initially the package will focus on Anthropometric indicators (i.e.
    child growth/development charts).

## Expectations

`{admiralpeds}` is expected to complement `{admiral}` and provide
functions to help with the creation of analyses required
for pediatric trial ADaMs.

## References and Documentation

-   Please refer to the [References and
    Documentation](https://pharmaverse.github.io/admiral/index.html#references-and-documentation)

## R Versions

Here's a summary of our strategy for this package related to R versions:

-   R versions for developers and users will follow the same as
    `{admiral}` core package.
-   For development the `main` branch of `{admiral}` core is used as a
    dependency. For releasing a new `{admiralpeds}` version it must run
    using the latest released `{admiral}` core version.

## Contact

We use the following for support and communications between user and
developer community:

-   [Slack](https://pharmaverse.slack.com/) - for
    informal discussions, Q&A and building our user community. If you
    don't have access, use this
    [link](https://join.slack.com/t/pharmaverse/shared_invite/zt-yv5atkr4-Np2ytJ6W_QKz_4Olo7Jo9A)
    to join the pharmaverse Slack workspace
-   [GitHub Issues](https://github.com/pharmaverse/admiralpeds/issues) -
    for direct feedback, enhancement requests or raising bugs
