# Housing Prices Modeling


### Project Overview
The business problem is defined as follows: a real estate development firm is looking to launch its latest development project in Washington State and is looking at its most populous county – King County, as its target market. 
The objective, naturally, is profit and the firm wants to understand which factors it should focus it’s consideration on during the development process, in order to maximize the chances of future sales.  Accordingly, the analysis below is focused on identifying features that have a considerable impact on pricing. 

![alt text](https://github.com/anaulianova/Housing_Prices_Modeling/blob/main/images/shutterstock_136157789.jpg)


### Data
>	House Sales in King County, USA (2014 – 2015), (Source: Kaggle); 
>	Common Point of Interest for King County, (source: ArcGIS Hub)

### Methodology
This project uses the OSEMiN (Obtain, Scrub, Explore, Model, Interpret) methodology and provides a possible linear regression model to predict housing prices in King County, WA. 

### Results

After examining the variables obtained in the datasets, my model has determined that the grade of the housing unit and the presence of a waterfront view are important factors influencing the prices of houses in King County. The model fits the data approximately 62.7% of the time, with a 95% degree of certainty. 

The model does have a medium positive skew to it. It conforms to the assumptions of normality (with outliers in the right tail) and homoscedasticity (with a Durbn-Watson score of 1.99). 

With regards to linearity, the model had several multicolinear variables that accounted for approximately 5% of its accuracy, which were subsequently removed. 

Finally, the latitude and longitudes were interestig variables as their removal dropped the model accuracy to below 60%, however given the time restrictions, this model could not be expanded to delve into these variables in more detail. 

##### Features

> Grade attributed to house: grades below 8 showed a negative coefficient, hence a negative relatinship to prices. As the grade grows, so the does its coefficient. 

> Waterfront View: the presence of a waterfront view was shown to increase housing prices in King County, WA. 



### Future Work
Provided more time, future modeling could include looking more closely at the effect of common points of interest on housing prices in area, not solely by their presence in the neighborhood, but by the scale of that present as well (For example, separating primary schools from university, and looking at which areas have a stronger concentration of restaurants or the like). 
Within the presently defined business problem, it would also be interesting, provided the data, to explore the evolution of housing prices over time, as well as the change in influential factors and trends. 


