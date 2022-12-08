*insert a figure here*

---------------------

# **Spatial data visualization**

## **How to visualize spatial data in a clear and transparent way**

##### *A data science tutorial by Filip Jarzyński*

### Content:

### Learning Objectives

# 1. Introduction
Visualization of spatial data in R language can be a powerful tool for exploring and understanding the relationships between geographical locations and associated data. This can be done using various tools and techniques, such as choropleth maps, dot maps, and kernel density estimates.

One of the most commonly used packages for visualizing spatial data in R is the `ggplot2` package, which provides a flexible and intuitive framework for creating a variety of different types of plots. `ggplot2` is a part of the `tidyverse` collection (that is why we will load it using `library(tidyverse)` command). 

The second package, `rworldmap` provides tools for plotting data onto global maps. It includes functions for plotting data onto maps of different projections, as well as for plotting latitude and longitude data. The `rworldmap` package also includes functions for working with country and region boundaries, and for adding additional layers of data to maps. We can distinguish three fundamental functions available:
* `joinCountryData2Map()` - links your data to the map 
* `mapCountryData()` - plots a map of country data 
* `mapGriddedData()` - plots a map of gridded data


And these are, among others, one of the packages we will be using today. 

To start, you will need to have the `rworldmap` and `tidyverse` packages installed and loaded into your R environment. You can do this by running the following code:

```{r}
# load the required packages

library(tidyverse) # includes ggplot and dplyr for data visualisation and manipulation
library(rworldmap) # mapping global data 
``` 
Keep in mind, that if you haven't downloaded any of these packages, you must use install.packages("PACKAGE NAME") command first to install the package. For example, if your R Studio can't find the `rworldmap` package, you have to run the following code before executing `library(rworldmap)`:

```{r}
install.packages("rworldmap") 
``` 



