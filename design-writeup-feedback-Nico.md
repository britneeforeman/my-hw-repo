### ***Design Write-up Feedback***

***Nico Van de Bovenkamp***

***

***What kind of machine learning task is this?***  
I don't think of this a logistic regression (ie. classification task). Given the setup, if you are trying to use the information on the song to predict the popularity (the value from 0.0 - 1.0), it is a regression task. However, depending on how you want to structure it, it could be classification task. You could take the rating and mark it as popular by being above a certain threshold or you could mark an indicator if the song had increased in popularity over a time interval or one of many of other structures! Does this make sense?

***On risks***  
There are risks on the modeling and data side of the problem, but there are other risks to consider. Primarily, you could build a model that doesn't accurately encompass the true indicators of popularity and suggest to artists, or their managers, that they should be touring for X amount of time or in Y types of places, when in fact it is not true! This could result in much worse outcomes than just the risk of the model not working.

**Questions:**

* Is there some external or additional data you can add about the artists? Is there any information you can collect on the type of listener/areas which they performed best or are the most liked? In other words, what other data can you include that will allow you to say that all these factors actually will lead to a certain (or certain increase in) popularity level.
* How are you going to process this data to be included in the model?
* What type of model do you think you will build?
* What does the distribution of the popularity look like?
* Are there certain interactions of variables that could be predictive of popularity? A ratio, maybe, of certain variables? 
