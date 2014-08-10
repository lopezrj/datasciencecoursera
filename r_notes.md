# Installing R Packages

## Display packages
a <- available.packages()

## Install packages
install.packages("package")
install.packages(c("package1","package2","package3"))

## Install packages from Bioconducotr

source("http://bioconductor.org/biocLite.R")
biocLite()

biocLite(c("GenomicFeatures",  "AnnotationDbi"))

## Load Packages
library(qglot2)  - Do not use quotes
search()

# Installing Rtools for Windows

