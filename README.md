
<!-- README.md is generated from README.Rmd. Please edit that file -->



# TMwR

<!-- badges: start -->
<!-- badges: end -->

This repository contains the source for [_Tidy Modeling with R_](https://tmwr.org). The purpose of this book is to demonstrate how the [tidyverse](https://www.tidyverse.org/) and [tidymodels](https://www.tidymodels.org/) can be used to produce high quality models.

# Reproducing the book or results

First, you'll need to install the required packages. To do this, first install the `remotes` package:

``` r
install.packages("remotes")
```

Then use this to install what you need to create the book: 

``` r
remotes::install_github("topepo/TMwR")
```

Although we rigorously try to use the current CRAN versions of all packages, the code above may install some development versions. 

The content is created using the `bookdown` package. To compile the book, use:

```r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

This will create the HTML files in a directory called `_book`. **Note** that, before the first compile, you'll need to make `_book` and copy the `premade` directory in this repository to `_book` so that existing diagrams will be found. 


# Contributing

This project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

_Tidy Modeling with R_ is currently a work in progress. As we create it, the code here is updated. This openness also allows users to contribute if they wish. Most often, this comes in the form of correcting typos, grammar, and other aspects of our work that could use improvement. Instructions for making contributions can be found in the [`contributing.md`](https://github.com/topepo/TMwR/blob/master/contributing.md) file.

- If you think you have encountered a bug or typo in this book, please submit [an issue](https://github.com/tidymodels/parsnip/issues) or [a PR](https://github.com/topepo/TMwR/pulls). 

- For questions and discussions about tidymodels packages, modeling, and machine learning, please [post on RStudio Community](https://rstd.io/tidymodels-community).

- Either way, learn how to create and share a [reprex](https://rstd.io/reprex) (a minimal, reproducible example), to clearly communicate about your code.

- Check out further details on [contributing guidelines for tidymodels packages](https://www.tidymodels.org/contribute/) and [how to get help](https://www.tidymodels.org/help/).
