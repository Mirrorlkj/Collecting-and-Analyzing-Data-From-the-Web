# Collecting and Analyzing Data From the Web

## Introduction

The repo consists of two parts.

* The first part focuses on exploring the relationship between population density and average life expectancy.
* The second part uses the API to obtain Near Earth Asteroid Information from NASA and demonstrates the relationship between absolute magnitude and Potentially Hazardous Asteroid.

## Required packages

The following packages are needed for reproducing the work:

```r
library(tidyverse)
library(geonames)
library(gapminder)
library(countrycode)
library(broom)
library(modelr)
library(knitr)

# only be used in Part 2
library(httr)
```

## Links to the assignment documents

* Part 1: Geonames
  + [R Markdown document](geonames.Rmd)
  + [pdf document](geonames.pdf)
* Part 2: NASA
  + [R Markdown document](nasa.Rmd)
  + [pdf document](nasa.pdf)
