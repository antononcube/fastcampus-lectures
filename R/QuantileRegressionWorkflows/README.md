# Quantile Regression Workflows 

**Mission statement:**

The goals of this (workshop) lectures are to:

- Introduce the theoretical background of Quantile Regression (QR),

- Demonstrate QR's practical (and superior) abilities to deal with "real life" time series data

- Teach how to rapidly create QR workflows using R

## Notebooks

Here are HTML preview links to the notebooks:

1. [Introduction to Quantile Regression](https://htmlpreview.github.io/?https://github.com/antononcube/fastcampus-lectures/blob/master/R/QuantileRegressionWorkflows/notebooks/01-Introduction-to-Quantile-Regression.nb.html)

2. [Quantile Regression Packages](https://htmlpreview.github.io/?https://github.com/antononcube/fastcampus-lectures/blob/master/R/QuantileRegressionWorkflows/notebooks/02-Quantile-Regression-Packages.nb.html)


## Packages

The QR packages used are `quantreg` and `QRMon`.

To install them use the commands:

```r
install.packages("quantreg")
#install.packages("devtools")
devtools::install_github(repo = "antononcube/QRMon-R" )
```

## References

[RK1] Roger Koenker,
["Quantile Regression in R: a Vignette"](https://cran.r-project.org/web/packages/quantreg/vignettes/rq.pdf),
(2010), 
[CRAN](https://cran.r-project.org).

[RK2] Roger Koenker,
["Censored Quantile Regression Redux"](https://cran.r-project.org/web/packages/quantreg/vignettes/crq.pdf).
(2008), 
[CRAN](https://cran.r-project.org).

[AA1] Anton Antonov,
["Rapid making of Quantile Regression workflows"](https://htmlpreview.github.io/?https://github.com/antononcube/QRMon-R/blob/master/notebooks/rapid-making-of-qr-workflows.html),
(2019),
[GitHub/antononcube](https://github.com/antononcube).
