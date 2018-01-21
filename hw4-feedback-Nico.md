### ***Project 4 Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Great work on this assignment! You walked through the key layout of the problem, your data, your analysis, results, and future things to explore. When you are walking through your analysis, it's nice, at times, to present some issues that you ran into when working on this problem (why is this problem... a problem?!). Another recommendation is for a few more plots that are associated with your model. For example, a decision tree diagram, model performance, roc curves, etc.!


***Imputing means***  
Looks like you dropped the nulls (nice), but you didn't impute the means? As we discussed in class, depending on how much data is missing, you can do this in many ways: Imputer, fillna() method, lambda functions, etc.!

```python
Series.fillna(np.mean([THAT SERIES]), inplace=True)
```
