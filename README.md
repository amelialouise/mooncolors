
# mooncolors

<!-- badges: start -->
<!-- badges: end -->

This R package provides a dataset of colors corresponding to 48 different colors of the Moon. 

![The color palette.](moon_palette.png)

The colors were extracted from photographs of the Full Moon taken by [Marcella Giulia Pace](https://greenflash.photo/greenflash-gallery/greenflash-gallery/portfolio/colors-of-the-moon/) over a ten year period. The pixels selected were near the [Albategnius Crater](https://en.wikipedia.org/wiki/Albategnius_(crater)).

## Installation

You can install mooncolors from GitHub using the devtools package:

``` r
devtools::install_github("amelialouise/mooncolors")
```

## How to use

Loading the package using `library(mooncolors)` gives you access to the `mooncolors` variable. This variable contains a vector of 48 color hexcodes.

``` r
library(mooncolors)
print(mooncolors)
```
