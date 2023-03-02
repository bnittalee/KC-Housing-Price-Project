## King County Housing Prices: A Multiple Regression Analsis
<img src="https://github.com/bnittalee/KC-Housing-Price-Project/blob/main/Images/stephen-plopper-UmEYn_GYqFo-unsplash.jpg" width="1000" height="400">
<b>Author:</b> Brittney Nitta-Lee 

### Overview
This analysis focuses on the King County House Sales data set to build a multiple regression model that can predict house prices for homeowners who are interested in selling their home. 

### Questions
1. Which features are most highly correlated with price?
2. Which feature has the strongest correlation with the value of a home?
3. What combination of features is the best fit for a multiple regression model to predict house prices?

### Data
The King County Housing Data Set includes information about the size, location, condition, and other features of houses in Washington's King County. The dataset and variable descriptions can be found on <a href ="https://www.kaggle.com/harlfoxem/housesalesprediction">Kaggle</a>.

## Methods
Methods included preprocessing the data, performing a train-test split to create a linear reagression models with price as the target variable.

## Results
The heatmap and the scatterplot matrix of the correlation coefficients between the the value of a home and features (bathrooms, sqft_living and sqft_living15, helps visualize the relationships between the variables. According to the correlation coefficients, sqft_living has the strongest linear relationship with price while the number of bathrooms is the lowest.
<img src="https://github.com/bnittalee/KC-Housing-Price-Project/blob/main/Images/heat-map.png" width="1000" height="400">

## Recommendations 
The squarefootage of a home and number of bathrooms are the best predictors of a home's price in King County. If homeowners are able to, they should expand the square footage of their home and build additional bathrooms. 

## Limitations and Next Steps
There was a lot of preprocessing and variables we had to perform log transformations on variables to satisfy regression assumptions. Therefore, the model may not accurately predict a home's value. A future analysis could include looking at data in other counties and using an updated dataset. King County is also a huge county and it would be better to narrodown differen't areas within King County to get better results.

### For more information
For additional information, contact Brittney Nitta-Lee at bnittalee@gmail.com 