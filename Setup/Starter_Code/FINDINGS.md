# Answers to the questions asked:

### Which model has a lower loss? (REVISED)
The closing_price model had a lower loss within every epoch. The fng model had a maximum loss of .0427 for an epoch, while the closing_prices model 
had a maximum epoch loss of .0283.

### Which model tracks the actual values better over time? 
The closing_prices model was what had tracked the actual values in a more accurate manner compared to the fng model. With both using the same parameters leading into the predictions, this was a surprise to me considering the evaluations also had the scores in reverse. fng model had a evaluation score
that was higher than the closing_prices model evaluation, yet this didn't give an accurate forecast of the more reliable model.

### Which window size works best for the model?  (NEED 2 REDO)
Despite the question asking for a 10 day window, this seemed to be less effective at giving more accurate predictions for the fng model compared to the 
3 day window. The gap between the starting prices for predicted and real values had actually close somewhat when shortening the length of the window size from 10 to 3 for not only the fng model, but the closing_prices model as well. So due to this result, I have the results for the models using a three day window. 

Tested: 1, 3, 10

