![Travis build status](https://travis-ci.com/imbi-heidelberg/DescrTab2.svg?branch=master)
[![codecov](https://codecov.io/gh/imbi-heidelberg/DescrTab2/branch/master/graph/badge.svg)](https://codecov.io/gh/imbi-heidelberg/DescrTab2)

# DescrTab2
## Publication quality descriptive statistics tables with R

This package provides functions to create descriptive statistics tables for continuous and categorical variables. By default, it calculates summary statistics such as mean, standard deviation, quantiles, minimum and maximum for continuous variables and relative and absolute frequencies for categorical variables. DescrTab2 features a sophisticated algorithm to choose appropriate test statistics for your data and provides p-values. On top of this, confidence intervals for group differences of appropriated summary measures are automatically produces for two-group comparison.

Tables generated by DescrTab2 can be integrated in a variety of document formats, cluding .html, .tex and .docx documents. DescrTab2 also allows printing tables to console and saving table objects for later use.

You can install DescrTab2 from github by typing
```
devtools::install_github("https://github.com/imbi-heidelberg/DescrTab2")
```
into your R console.

For usage instructions and detailed documentation, check out our documentation page:

https://imbi-heidelberg.github.io/DescrTab2/
