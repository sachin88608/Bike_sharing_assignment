# Project Name
> Build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General_Information](#General_Information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#Contact)

## General_Information
- Build a multiple linear regression model for the prediction of demand for shared bikes
- Dataset (day.csv)


## Conclusions
- In 2019 the price of rental bikes is more as compare to 2018
- In season Fall and winter has reahed maximum sales (Our demand is high in the season of Fall and Winter)
- In the months of July, september and october reached the max sales
- Wednesday and Friday got the maximum sales (Friday because end of the week)
- Because of the above data weekday has more number of sales as compare to weekend/holiday.
- People go for outing on bikes more on when the weather is mostly Partly Cloudy
- So, the business need to focus more on Weekdays (Mostly on wednesday and Friday) in the months of July, september and october then they can increase the revenue of the company.

- Final Model r2 = 0.82 and mse is 0.0085.



## Technologies Used
- pandas
- numpy
- warnings
- matplotlib.pyplot
- seaborn
- sklearn
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import MinMaxScaler
- from sklearn.metrics import r2_score
- from sklearn.feature_selection import RFECV ##Recursive feature elimination with cross-validation to select features.
- import statsmodels.api as sm
- from statsmodels.stats.outliers_influence import variance_inflation_factor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@sachin88608] - feel free to contact me!