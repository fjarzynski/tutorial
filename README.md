*insert a figure here*

---------------------

# **Spatial data visualization**

## **How to visualize spatial data in a clear and transparent way**

##### *A data science tutorial by Filip Jarzyński*

### Content:

### Learning Objectives


Visualization of spatial data in R language can be a powerful tool for exploring and understanding the relationships between geographical locations and associated data. This can be done using various tools and techniques, such as choropleth maps, dot maps, and kernel density estimates. One of the most commonly used packages for visualizing spatial data in R is the 'ggplot2' package, which provides a flexible and intuitive framework for creating a variety of different types of plots. (ZDANIE O DRUGIM PAKIECIE?) And these are, among others, one of the packages we will be using today. 
To start, you will need to have the ggplot2 package installed and loaded into your R environment. You can do this by running the following code:

```{r}
library(ggplot2)
library(ggmap) (PYTANIE CZY ZALACZAC)
``` 
Keep in mind, that if you haven't downloaded any of these packages, you must use install.packages("PACKAGE NAME") command first to install the package. For example, if your R Studio can't find the ggplot2 package, you have to run the following code before executing `library(ggplot 2)`:

```{r}
install.packages("ggplot2") 
``` 

