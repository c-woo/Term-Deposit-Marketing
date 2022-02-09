# Term Deposit Marketing

I'll be attempting to accurately predict whether or not a customer of a European banking institution will sign up for a term deposit. 

## Visualizations

<img src="https://i.imgur.com/2hE8HTl.jpg">

<img src="https://i.imgur.com/Vd3SIUZ.jpg">

## Models Used for Predictions

The models I tested are:<br>
* Logistic Regression
* Random Forest
* LightGBM
* XGBoost

## Logistic Regression
Accuracy: 93.3%

## Random Forest
Accuracy: 93.2%

## LightGBM
Accuracy: 93.2%

## XGBoost
Accuracy: 93.5%


## Conclusion
the best performing model is xgboost with a training and testing accuracy of 93.5%. The model has an extremely high accuracy rate and I would be confident in the model to predict whether or not a future customer will be interested in the marketing campaigns products. 

The most predictive factor in whether or not a customer will sign up for a term deposit is the duration of the phone call. The average duration of a phone call for customers who sign up for a term deposit is 11 minutes while the average duration for customers who are not interested is 3-4 minutes. If the campaign is able to engage the customer past the 4 minute mark and keep them interested in the product the success rate for sales should increase.
 
The subsets of customers to focus on to maximize sign ups are customers with a tertiary education. These customers sign up about 9% of the time where as customers with a secondary education only sign up about 7% of the time.