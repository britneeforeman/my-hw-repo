### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Another fantastic homework assignment! You wrote some nice, clean code and gave exact answers to each question -- well done! Also, nice call out to specific models re: decision tree. That is definitely one model that you could use, and it's one that would give you a lot of insight into breaking down the problem (what is the most important factor for getting into grad school?). In the next assignment, we will be doing some modeling. The homework will have you do a logistic regression, but I want you to try both a logistic regression and a decision tree! We won't have covered it much yet, if at all, but if you are familiar then you should do it!


**Some Notes**

* Very pythonic code here, so nice! `np.round(df_raw.describe(), 2).T`

**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. In your bonus, you mention imputing 0's into the missing values. If you do this, you will retain your data, but you would be imputing that information into your model and disturbing the distribution unnecessarily. In other words, these models are really dumb, but really powerful and effective, so if you tell it that there are these students that have say a GPA of 3.5, a GRE of 0, and a prestige school of 2, then your model will be trying to create the best way to include that info!

Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html
