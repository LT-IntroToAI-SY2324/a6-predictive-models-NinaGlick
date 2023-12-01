# Part 2 - Training and Testing Data Writeup

After completing `a6_part2.py` answer the following questions

## Questions to answer

1. What makes this model more effective than the model you created in the previous lesson?
this model presents far more data than the last model. the first model only showed the original and predicted data, but this model had testing data, training data, and predictions. more data with more testing made this model more effective in presenting relavent data.

2. What does the R squared coefficient tell you about the model?
r squared is the correlation coefficient of the data.it is indicative of the fact that age does not have a super sstong effect on blood pressure.


3. Would you say that your model is accurate? What evidence supports your conclusion? Consider the meaning of the predicted and actual values in the context of the chart below from the American Heart Association’s website on understanding blood pressure.
the predicted and actual values differ not super significantly, but enough to change the classification of a person's blood pressure. for example, with the x value 25, the predicted y value is 119.27, while the actual value is 125. this can lead to issues, because if someone is to use this model to see their blood pressure status, they will be told that their blood pressure is normal, when in reality it is elevated. For this reason, the model is not toally accurate, and even potentially dangerous.