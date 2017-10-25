
<!-- README.md is generated from README.Rmd. Please edit that file -->
praiseme
========

The goal of praiseme is to deliver some lovely praise, just when you need it!

Installation
------------

You can install praiseme from github with:

``` r
# install.packages("devtools")
devtools::install_github("njtierney/praiseme")
```

Example
-------

Here's an example of using praise from praiseme

``` r
# Just you
library(praiseme)
praise()
#> [1] "You're the best, Nick"

# Or a friend!
praise("Maddy!")
#> [1] "You're the best, Maddy!"
```
