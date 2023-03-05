## King County Housing Prices: A Multiple Regression Analysis
<img src="https://github.com/bnittalee/KC-Housing-Price-Project/blob/main/Images/stephen-plopper-UmEYn_GYqFo-unsplash.jpg" width="1000" height="400">
<b>Author:</b> Brittney Nitta-Lee 

### Overview
Compass Real Estate wants to host a class for homeowners who are interested in selling their home. This analysis will be focusing on the King County House Sales dataset to find information on ways to increase the value of their home. 

### Questions
1. Which features are most highly correlated with price?
2. Which feature has the strongest correlation with the value of a home?
3. Does grade or condition of a house contribute to the value of a home??

### Data
The King County Housing Data Set includes information about the size, location, condition, and other features of houses in Washington's King County. The dataset and variable descriptions can be found on <a href ="https://www.kaggle.com/harlfoxem/housesalesprediction">Kaggle</a>.

## Methods
Methods included preprocessing the data, performing a train-test split to create a linear reagression models with price as the target variable.

## Results
The heatmap and the scatterplot matrix of the correlation coefficients between the the value of a home and features (bathrooms, sqft_living and sqft_living15, helps visualize the correlation with price. According to the correlation coefficients, sqft_living has the strongest linear relationship with price while the number of bathrooms is the lowest.
<br><center><img src="https://github.com/bnittalee/KC-Housing-Price-Project/blob/main/Images/heat-map.png" width="500" height="400"></br> 

## Recommendations 
If homeowners are able to, they should expand the square footage of their home and buildadditional bathrooms. Another focus is the grade or construction quality of the home. Homeswith higher design quality have more value. And the condition of the home should have no signsof damage or repair. 

## Limitations and Next Steps
There was a lot of preprocessing and variables we had to perform log transformations on variables to satisfy regression assumptions. Therefore, the model may not accurately predict a home's value. A future analysis could include looking at data in other counties and using an updated dataset. King County is also a huge county and it would be better to narrodown differen't areas within King County to get better results.

### For more information
For additional information, contact Brittney Nitta-Lee at bnittalee@gmail.com 
