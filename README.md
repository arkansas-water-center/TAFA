# TAFA
Trend Analysis with Flow Adjustment

This repository contains the 'TAFA' package for R. TAFA is a trend-analysis process for water quality data, but the procedure could be generalized to other applications.

TAFA utilizes an iterative K-fold cross-validation procedure to select an optimal smoothing parameter for LOESS for the given dataset. TAFA then carries out the flow-adjustment and trend analysis procedure (i.e., linear regression, but can be extended to other trend tests).
Once installed, see ?tafa for details and an example.

This package is the result of a study by Simpson and Haggard (2016). For installation in R, see below.

Citation
----------

Simpson, Z.P. and B.E. Haggard. 2016. An optimized procedure for flow-adjustment of constituent concentrations for trend analysis. In preparation.


Installation
----------

```r
install.packages("devtools")
devtools::install_github("arkansas-water-center/TAFA")
library("TAFA")
```