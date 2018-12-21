# COURSERA: BUILDING R PACKAGES
Peer-graded Assignment   
Junaid Khan   
email: jrkhan011@gmail.com   
GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007   


## Create an Example Package in R 

Package: fars
GitHub:  https://github.com/athos2113/FarsAnalysis

## Data Source

The functions will be using data from the US National Highway Traffic Safety 
Administration's [Fatality Analysis Reporting 
System](https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars),
which is a nationwide census providing the American public yearly data regarding
fatal injuries suffered in motor vehicle traffic crashes.

## Review Criteria

For this assignment you'll submit a link to the [GitHub repository](https://github.com/athos2113/FarsAnalysis) which contains
your package. This assessment will ask reviewers the following questions:

* Does this package contain the correct [R file(s) under the R/ directory](https://github.com/athos2113/FarsAnalysis/tree/master/R)?   
* Does this package contain a 
[man/](https://github.com/athos2113/FarsAnalysis/tree/master/man) with directory
corresponding documentation files?
* Does this package contain a 
[vignette](https://github.com/athos2113/FarsAnalysis/blob/master/vignettes/fars_vignetter.Rmd) 
which provides a meaningful description of the package and how it should be 
used?
* Does this package have at least one test included in the [tests/](https://github.com/athos2113/FarsAnalysis/tree/master/tests/testthat) directory?
* Does this package have a [NAMESPACE](https://github.com/athos2113/FarsAnalysis/blob/master/NAMESPACE) file?
* Does the README.md file for this directory have a [Travis badge](https://travis-ci.org/EnriquePH/FARS)?
* Is the build of this package passing on [Travis badge](https://travis-ci.org/athos2113/FarsAnalysis)?
* Are the build logs for this package on [Travis badge](https://travis-ci.org/athos2113/FarsAnalysis) free of any errors, warnings, or notes?


## Links:
* [Writing an R package from scratch](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)    
* [Github: roxygen2](https://github.com/klutometis/roxygen#roxygen2)   
* [Common `roxygen2` tags](https://bookdown.org/rdpeng/RProgDA/documentation.html#common-roxygen2-tags)
* [Text formatting reference sheet](https://cran.r-project.org/web/packages/roxygen2/vignettes/formatting.html)
* [Writing R Extensions](https://cran.r-project.org/doc/manuals/R-exts.html#Creating-R-packages)
* [Travis: Building R packages](https://docs.travis-ci.com/user/languages/r/)
* [Vignettes: long-form documentation](http://r-pkgs.had.co.nz/vignettes.html)
* [Package Development with devtools Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2015/03/devtools-cheatsheet.pdf)
* [Customizing Package Build Options](https://support.rstudio.com/hc/en-us/articles/200486518-Customizing-Package-Build-Options)
* [Testing packages](http://r-pkgs.had.co.nz/tests.html)
