# Term Deposit Marketing

The ability to find customers who are willing to purchase a companies product is an invaluable tool for any industry. Cold calling potential customers, while providing a lot of data, likely results in a lot of failed attempts in making a sale. Being able to distinguish any features that could help increase the success rate of sales would save companies a lot of time and money. With the large amount of data sales calls provide, machine learning can be used to find the customers that are more likely to result in successful sales. Ultimately, I am looking for ways to improve the success rate for calls made to customers which can be leveraged to other products that are offered.

## Data

The data comes from the marketing efforts of a European banking institution. The marketing campaign involves making a phone call to a customer, often multiple times to ensure a product subscription, in this case a term deposit. Term deposits are usually short-term deposits with maturities ranging from one month to a few years. The customer must understand when buying a term deposit that they can withdraw their funds only after the term ends.
> **Age:** Age of customer  
> **Job:** Type of job  
> **Marital:** Marital status   
> **Education:**  
> **Default:** Has credit in default?  
> **Balance:** Average yearly balance, in euros  
> **Housing:** Has a housing loan?  
> **Loan:** Has personal loan?  
> **Contact:** Contact communication type  
> **Day:** Last contact day of the month  
> **Month:** Last contact month of year  
> **Duration:** Last contact duration, in seconds  
> **Campaign:** Number of contacts performed during this campaign and for this client (includes last contact)  

## Visualizations

<img src="https://i.imgur.com/2hE8HTl.jpg">

<img src="https://i.imgur.com/Vd3SIUZ.jpg">

<img src="https://i.imgur.com/QITs9xW.jpg">

<img src="https://i.imgur.com/PBX0Pua.jpg">

<img src="https://i.imgur.com/hj828UI.jpg">

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
The best performing model is xgboost with a training and testing accuracy of 93.5%. The model has an extremely high accuracy rate and I would be confident in the model to predict whether or not a future customer will be interested in the marketing campaigns products. 

The most predictive factor in whether or not a customer will sign up for a term deposit is the duration of the phone call. The average duration of a phone call for customers who sign up for a term deposit is 11 minutes while the average duration for customers who are not interested is 3-4 minutes. If the campaign is able to engage the customer past the 4 minute mark and keep them interested in the product the success rate for sales should increase.
 
The subsets of customers to focus on to maximize sign ups are students, customers with a tertiary education, or single customers. 









ZmmPrClHaZXkvJE4
