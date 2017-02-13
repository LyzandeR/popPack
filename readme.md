## popPack

This is a package which has only one goal. To install most of (if not all) the popular packages in R. 

It contains no useful functions.

The packages (all dependencies will also be installed) are in the _imports_ list and not in the _depends_. This
means that they will be downloaded and installed but will not be attached if the package is loaded (why would
you load popPack anyway).

## How to Install

You need `devtools` to install this package (`install.packages('devtools')` from the R console). Then just type on 
your console:

```{r}
devtools::install_github('lyzander/popPack')
```

## List of included packages

* httr
* jsonlite
* ggplot2
* dplyr
* highcharter
* data.table
* caret
* randomForest
* sparklyr
* e1071
* Hmisc
* rmarkdown
* colf
* ggvis
* shiny
* htmlwidgets
* lme4
* reshape2
* tableHTML
* RSelenium
* stringi
* tm
* roxygen2
* testthat
* xgboost
* FNN
* htmltools
* revealjs
* xts
* lubridate
* plotly
* Matrix
* car
* DEoptimR
* gridExtra
* microbenchmark
* xlsx
* openxlsx
* rgl
* tidyr
* gtable