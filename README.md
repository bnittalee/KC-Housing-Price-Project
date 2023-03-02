## King County Housing Prices: A Multiple Regressions Analsis
<img src="https://github.com/AvonleaFisher/Predicting-King-County-House-Prices-with-Multiple-Regression-Analysis/blob/master/correlates_with_price.png">
<b>Author:</b> Brittney Nitta-Lee 

### Problem:
The aim of this analysis is to build a multiple regression model that can predict house prices with the greatest accuracy possible. The results can inform home owners interested in selling their homes about the most important factors to consider for improving sale prices.
### Data
The King County Housing Data Set contains information about the size, location, condition, and other features of houses in Washington's King County. The dataset and variable descriptions can be found on <a href ="https://www.kaggle.com/harlfoxem/housesalesprediction">Kaggle</a>.
## Methods
After exploring and preprocessing the data, simple and multiple linear regression models were built in OLS statsmodels, with price as the dependent variable. 
## Results
Together, square footage, grade and bathrooms are the best predictors of a house's price in King County. These features were included in the final multiple regression model. The model satisfied all multiple regression assumptions, and p-values for each predictor variable were below .05. The r-squared value of the model was .529.

<img src="https://github.com/AvonleaFisher/Predicting-King-County-House-Prices-with-Multiple-Regression-Analysis/blob/master/correlates_with_price.png">

>Features were selected based on the strength of their linear relationship with price, and multicollinear features were excluded.

## Recommendations 
Homeowners interested in selling their homes should focus on improving the design and quality of construction of their homes, which may in turn improve their home grade. If possible, they should also expand the square footage of living space on the lot, perhaps by building additional bathrooms. The square footage of neighbors' living space is also a strong positive predictor of price, but homeowners likely have less control over this factor. Homeowners may further increase the sale price of their homes by encouraging neighbors to also expand the square footage of their living space. 
## Limitations and Next Steps
The model does have some limitations: given that some of the variables needed to be log-transformed to satisfy regression assumptions, any new data used with the model would have to undergo similar preprocessing. Additionally, given regional differences in housing prices, the model's applicability to data from other counties may be limited. Given that outliers were removed, the model may also not accurately predict extreme values. Future analysis should explore the best predictors of the prices of homes outside of King County, as well as homes with extreme price values.
### For further information
Please consult the <a href ="https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r">King County Residential Glossary of Terms</a> for further information about the data. For inquiries about this project, please contact me at fisheravonlea@gmail.com or via my [LinkedIn profile](https://www.linkedin.com/in/avonlea-fisher/).
