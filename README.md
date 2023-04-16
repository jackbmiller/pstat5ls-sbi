# pstat5ls-sbi
 An R package for PSTAT 5LS at the University of California, Santa Barbara. Based on the stats250sbi package developed by my colleagues Nick Seewald and Elaine Hembree for Stats 250 while I was teaching at the University of Michigan.

## Installation

This package is not available on CRAN, and must be installed via GitHub using the `remotes` package. To install `pstat5ls-sbi`, run the following code in your R console:

```{r}
install.packages("remotes")
remotes::install_github("jackbmiller/pstat5ls-sbi")
```

To use the package, make sure the following line of code is run every time you start R, or by making sure it is in the setup chunk of your R Markdown document:

```{r}
library(pstat5ls-sbi)
```
