# Covid Case Prediction

During a pandemic, governemnt issued state-wide shutdowns could prevent overwhelming the hosptial system but timing is key. Reacting after there are too many cases can be too late. In New York state, Governer Cuomo issued state-wide shutdown on 03/20/2020, however, Covid-19 cases peaked about 3 weeks later. Suggesting that many people already had contracted the virus by the time of the shutdown and started showing symptoms later. 

![NY](/images/NY_labeled.png)


To prevent unnecessary increases in deaths, governments need to react promptly to indications of case numbers increasing sharply. Can we predict case rises in advance?

When case numbers are looked at closely in each state, I noticed that cases start rising sharply 3-4 weeks prior they reach their peaks (Case numbers in Florida is plotted blow as an example. Vertical line marks 3 weeks before the peak). 

![Florida](/images/Florida.png)

Perhaps case numbers and the slope of case rise can be used to predict the number of cases 3 weeks in the future. 

Current progress:
I applied k-nearest neighbor algorithm to predict case numbers. I also used daily positive case numbers and test numbers from the Covid tracking project, and political party of the governning state as a parameter.

The model was trained using data prior to 2020-07-25 (5 weeks before the last day of collected data), and tested on the last two 2 weeks of collected data (shaded region in lighter orange).

![prediction](/images/predictions.png)


** This project is not complete. Working on using other models.




full code: [covid_prediction](https://github.com/maayaikeda/covid_case_prediction/blob/master/Covid_case_predictions.ipynb)
