## Unit 14 , Deep Learning

This assignment involves recurrent neural networks for predicting the bitcoin closing prices of the 11th day.
There will be 2 notebooks that will build RNN using deep learning tensfor flow libraries to compare prediction reports.
One will be using closing prices, and the other will be using the FNG index sentiments.
a 3 layer neural network will be used for the model fit of the X features , a window of size 10  and 30 for steps (30 days)

The findings and conclusions are as follows:
Which model has a lower loss?
The closing prices have a lower loss for this RNN
Which makes sense because closing prices are more calculated
than fng sentiments

Which model tracks the actual values better over time?
The closing prices have a closer value of predicted values
to real values for this 3 layer RNN 


Which window size works best for the model?
The windows size 10 works best because we are using a 10day window
to predict the 11th day 
