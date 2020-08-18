<!-- README.md is generated from README.Rmd. Please edit that file -->

[Winnipeg workshop: Handling missing data in `R` with `mice`](http://amices.github.io/Winnipeg/)
================================================================================================

Overview
--------

This site contains materials for the Biostatistics Workshop *Handling
missing data in `R` with `mice`* the 45th Annual Meeting of the
Statistical Society of Canada, dated Sunday, June 11, 2017, located in
Winnipeg E3 - 270 (EITC).

Motivation
----------

Nearly all data analytic procedures in R are designed for complete data,
and many will fail if the data contain missing values. Typically,
procedures simply ignore any incomplete rows in the data, or use ad-hoc
procedures like replacing missing values with some sort of “best value”.
However, such fixes may introduce biases in the ensuing statistical
analysis.

Multiple imputation is a principled solution for this problem. The aim
of this workshop is to enable participants to perform and evaluate
multiple imputation using the R package `mice`.

Contents
--------

The workshop will consist of 5 sessions, each of which comprises a
lecture followed by a computer practical using `R`:

1.  Session I: Introduction, issues raised by missing data, and towards
    a systematic approach
2.  Session II: Introduction to multiple imputation
3.  Session III: Multivariate missing data (joint model approach,
    chained equations)
4.  Session IV: Imputation in practice (large data sets, hierarchical
    data, non-linearities, interactions)
5.  Session V: After imputation, guidelines for analysis and reporting

How to prepare
--------------

Please remember to bring your own laptop computer and make sure that you
have write-access to that machine (some corporate computers do not allow
write access) or that you have the following software and packages
pre-installed.

------------------------------------------------------------------------

1.  Download and install the latest version of `R` from [the R-Project
    website](https://cloud.r-project.org)
2.  Download and install the most recent version of
    `RStudio Desktop (Free License)` from [RStudio’s
    website](https://www.rstudio.com/products/rstudio/download3/). This
    is not necessary, per se, but it is highly recommended as `RStudio`
    delivers a tremendous improvement to the user experience of base
    `R`.
3.  Install the following packages:
    [`mice`](https://cran.r-project.org/web/packages/mice/index.html),
    and
    [`lattice`](https://cran.r-project.org/web/packages/lattice/index.html)

-   You can simply install packages from within `RStudio` by navigating
    to `Tools > Install Packages` in the upper menu and entering
    `mice, lattice` into the `Packages` field. Make sure that the button
    `Install dependencies` is selected. Once done, click `Install` and
    you’re all set.
-   Or, from within `R` or `RStudio`, copy, paste and enter the
    following code in the console window (by default the top-right
    window in `RStudio` / the only window in `R`):

``` r
install.packages("mice")
install.packages("lattice")
```

------------------------------------------------------------------------

Workshop materials
------------------

1.  [Lectures](Lectures/Winnipeg.pdf)
2.  [Handout](Lectures/WinnipegHandout.pdf)
3.  [Practical I](Practicals/Practical_I.html)
4.  [Practical II](Practicals/Practical_II.html)
5.  [Practical III](Practicals/Practical_III.html)
6.  [Practical IV](Practicals/Practical_IV.html)
