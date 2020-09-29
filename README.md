# Covid Case Prediction

During a pandemic, governemnt issued state-wide shutdowns could prevent overwhelming the hosptial system but timing is key. Reacting after there are too many cases can be too late. In New York state, covid-19 cases peaked after the Governer Cuomo issued state-wide shutdown. Suggesting that many people already had contracted the virus by the time of the shutdown and started showing symptoms later. 

![NY](/images/NY_labeled.png)


To prevent unnecessary increases deaths, governments need to react promptly to indications of case numbers increasing sharply. Can we predict case rises in advance?

When case numbers are looked at closely in each state, we see that cases start rising sharply 3-4 weeks prior they reach their peaks (Case numbers in Florida is plotted blow as an example. Vertical line marks 3 weeks before the peak). 

![Florida](/images/Florida.png)

Therefore, perhaps case numbers and the slope of case rise can be used to predict the number of cases 3 weeks in the future. I applied 



k-nearest neighbor 



![KNNprediction](/images/KNN3wks_beforepeak.png)


full code: [covid_prediction](https://github.com/maayaikeda/covid_case_prediction/blob/master/Covid_case_predictions.ipynb)
