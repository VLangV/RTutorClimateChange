This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

Description:
The aim of this R-Tutor set is to measure farmer adaptation to climate change in the United States. 
Therefore, agricultural and climatic data from 1950-2000 were analyzed to measure adaptation to extreme heat in corn production. 

Original Paper:
https://pubs.aeaweb.org/doi/pdfplus/10.1257/pol.20130025

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("VLangV/RTutorClimateChange")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorClimateChange)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorClimateChange")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorClimateChange",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
