# CMSE-202-Group-Project-Sports-


Ethan - I was responsible for adjusting a dataset from kaggle so that it sorted the stats out by each quarterback. I also used a querey to sort through the data to eliminate seasons where the quarteback didn't throw very many passes, either due to being a backup, or injured. This was completed by using a group by command to sort through the data and using a querey command to remove the undesired rows from the sorted dataset.


Sarah Koehler - I used stats from quarterbacks' rookie season in recent years to determine whether the their rookie season was successful. With the values of the whether the quarterback was successful or not, I created a model with the quarterbacks' college stats to predict whether they would be successful or not. I created both a logistic regression model and SVM model. I used the college stats from quarterbacks that are likely to be drafted this year in the two different models to try to predict whether the player will have success in their rookie season. 

The code for this is in the cfb_to_rookie_season.ipynb file. The code should be run in order. The code goes through and determines which quarterbacks' rookie seasons were successful. The threshold was for the quarterback's rookie season rate to be above the average rate of all the rookie quarterbacks and for their amount of pass attempts to be above 100. The logistic regression model is created first and then the SVM model is created through the statsmodels and sklearn libraries. Then the code uses the quarterbacks that should be drafted to predict whether they will be successful.

```python

```
