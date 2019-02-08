# R-Empirical-Real-Estate

Author: Marco Hassan 

Semester exercise for a lecture in Empirical Real Estate Finance at the University of St. Gallen.

The goal is to apply standard statistical techniques and spatial regressions to dataset involving real estate properties and to map them accordingly through the leaflet package.

# Assignment 1

This assignment reports basics statistics for a series of USA properties.

Moreover in the code I get coordinates for Swiss properties through the ggmap package using google databases and given that I plot the properties in Switzerland accordingly to the property value through the leaflet package that allows to customize maps interactively zooming into the map.

![image](https://user-images.githubusercontent.com/42472072/52440568-27070080-2b27-11e9-9106-87989ba24c7f.png)


# Assignment 2

This assignment uses the Melbourne dataset available on Kaggle under the following link.

___________________________________________________________
https://www.kaggle.com/anthonypino/melbourne-housing-market
___________________________________________________________

Based on that I run a hedonic regression to understand the most determinant factors determining the price in Melbourne city.

Based on the lm package I explore the assumption for a BLUE OLS estimator.


![image](https://user-images.githubusercontent.com/42472072/52441218-c5479600-2b28-11e9-8b4b-7a56e6b6e0b8.png)


Finally I plot the price in the city through the leaflet package that allows to zoom in the area and move among quartiers. 

![image](https://user-images.githubusercontent.com/42472072/52441190-bb259780-2b28-11e9-8804-6d8a83d5fd7c.png)



# Assignment 3

Contains standard panel regression controlling for time fixed effects and state fixed effects in german Budesländer.

# Assignment 4

Given a map in .shp format available uploaded in the directory and a dataset for the different swiss cantons I modelled a knn-neighbour model to capture the spatial deopendencies in for spillover effects among the regions.


![image](https://user-images.githubusercontent.com/42472072/52441579-b1506400-2b29-11e9-9987-b6c078145e42.png)


Based on this I manually programmed a spatial autocorrelated model and I calculated the effect of an exogenous effect of a population growth shift in some northern eastern canton.

I plotted subsequently the spillover effect of such a growth rate shift in the region.

![image](https://user-images.githubusercontent.com/42472072/52441808-58350000-2b2a-11e9-826b-ad7a3d574674.png)

