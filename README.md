
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rjd3x13

rjd3x13 offers full acces to options and outputs of X-13
(`rjd3x13::x13()`), including RegARIMA modelling (`rjd3x13::regarima()`)
and X-11 decomposition (`rjd3x13::x11()`).

The specification can be created with the functions
`rjd3x13::regarima_spec()`, `rjd3x13::x11_spec()` or

- for the pre-processing: `rjd3toolkit::set_arima()`,
  `rjd3toolkit::set_automodel()`, `rjd3toolkit::set_basic()`,
  `rjd3toolkit::set_easter()`, `rjd3toolkit::set_estimate()`,
  `rjd3toolkit::set_outlier()`, `rjd3toolkit::set_tradingdays()`,
  `rjd3toolkit::set_transform()`, `rjd3toolkit::add_outlier()`,
  `rjd3toolkit::remove_outlier()`, `rjd3toolkit::add_ramp()`,
  `rjd3toolkit::remove_ramp()`, `rjd3toolkit::add_usrdefvar()`;

- for the decomposition: `rjd3x13::set_x11()`;

- for the benchmarking: `rjd3toolkit::set_benchmarking()`.

## Installation

``` r
# Install development version from GitHub
# install.packages("remotes")
remotes::install_github("rjdemetra/rjd3toolkit")
remotes::install_github("rjdemetra/rjd3x13")
```
