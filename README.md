
# importR

![](swan-gba007e09d_640.jpg)

The goal of importR is to create an R data frame from 
external data in SAS, SPSS, or Stata binary files, Excel
Workbooksm or delimited text files
.

## Installation

You can install the importR from with:

``` r
if(!require("remotes")){
  install.packages("remotes")
  library("remotes")

remotes::install_github("importR"")
```

## Example

You can import data file using

``` r
library(importR)
mydata <- import()
```

