# mozzie

[![Travis-CI Build Status](https://travis-ci.org/thiyangt/mozzie.svg?branch=master)](https://travis-ci.org/thiyangt/mozzie)
[![Project Status: Active ? The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Licence](https://img.shields.io/badge/licence-CC0-blue.svg)](http://choosealicense.com/licenses/cc0-1.0/)

R package for weekly notified dengue cases in Sri Lanka 

## Installation

```R
# Install the development version from GitHub
install.packages("devtools") 
devtools::install_github("thiyangt/mozzie")
library(mozzie)
```

## Example

```R
library(mozzie)
head(mozzie)
summary(mozzie)
```
