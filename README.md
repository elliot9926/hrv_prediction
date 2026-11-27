hypothesis testing -> is this relationship due to chance?

null hypothesis ($H_0$) and alternative hypothesis ($H_1$)

test statistic used to compute p-value (conditional probability)

## Project basics
**Null hypothesis**
HRV trends over 7 days can not predict the onset of symptomatic illness.

**Alternative hypothesis** 
HRV trends over 7 days are associated with the onset of symptomatic illness.

**approach 1**
- get a slope for hrv over each week
	- use simple linear logistic regression
- try to find slope vs. isWeekBeforeOnset
	- does a steeper downwards slope mean a higher probability of being the week before illness onset?
