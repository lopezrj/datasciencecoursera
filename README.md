datasciencecoursera
===================

Files from Data Specialization

## GIT

Four databases: workspace, index, local repository, remote repository

###  Add
* git add -a               (From workspace to local repository)
* git commit -m "message"  (From index to local repository)
* git push                 (From local repository to remote repository)

### Revert
* git pull or rabase       (From remote repository to workspace)
* git fetch                (From remote repository to local repository)
* git chekout HEAD         (From local repository to workspace)
* git chekout              (From index to workspace)

### Compare
* git diff HEAD            (From local repository to workspace)
* git diff                 (From index to workspace)

### Branch

To create a branch:
  git checkout -b branchname

To see what branch you are on:
  git branch

To switch back to the master branch:
  git checkout master

### Setup

 * git remote set-url origin git@github.com:my_user_name/my_repo.git

## Installing R Packages

### Display packages
a <- available.packages()

### Install packages
install.packages("package")
install.packages(c("package1","package2","package3"))

### Install packages from Bioconductor

source("http://bioconductor.org/biocLite.R")
biocLite()

biocLite(c("GenomicFeatures",  "AnnotationDbi"))

### Load Packages
library(qglot2)  - Do not use quotes
search()

## Installing Rtools for Windows
