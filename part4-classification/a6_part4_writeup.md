# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
the accuracy is 68%. because the standardized sacler scales the data, by equalizing the range between data points, and the standardized the means and standard deviatios of the data set, the abscense of a standardscaler makes it so the model is far less accurate then it would be if it did have a standardscaler.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
the mdel is 88% accurate when the standardscaler is included in the code. it is accurate enough for this case, because it is mostly accurate. if the model aimed to make predictions about things that are far more serous, like predcting if someone is chronically ill, this model may not be accurate enough. however, given that this model is for the likelihood that someone will purchase a car, and the overall outcome is far less srious, this model (while it could be more accurare) is accurate enough.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
when looking at the predictions and actual results, the model seemed to to very well. of what was printed in the terminal, nothing was wrong. it's hard to say if there was a pattern, because it is unclear when the model made a mistake.

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
the prediction was correct. the woman did not buy an suv.

