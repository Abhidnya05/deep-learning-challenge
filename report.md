Report - Module 21 Challenge

AIm - The goal of this investigation is to develop a binary classifier that can forecast the success or failure of candidates that receive funding from Alphabet Soup. In order to accomplish our goal, we are utilising machine learning techniques, and we have experimented with model optimisation through parameter variation. A train set and a test set were created from the provided dataset. Overall, we were able to achieve 73% accuracy.

Our analysis can be summarise using following questions-answers

1) What variable(s) are the target(s) for your model?
- 'IS_SUCCESSFUL'
2) What variable(s) are the features for your model?
- The feature variables contains all columns from dataframe except 'IS_SUCCESSFUL', 'EIN', 'NAME' columns
3) What variable(s) should be removed from the input data because they are neither targets nor features?
- 'EIN', 'NAME'
4) How many neurons, layers, and activation functions did you select for your neural network model, and why?
- We made several attmepts by changing number of layers and activation functions to optimize our model
5) Were you able to achieve the target model performance?
- We were unable to achieve 75% accuracy 
6) What steps did you take in your attempts to increase model performance?
- We primanrly changed - 1. neurons, 2. epochs 3. number of hidden layers

Conclusion:
In general, the deep learning model predicted the classification task with an accuracy of roughly 73%. More input-output correlation in a model would probably translate into more accurate predictions. This might be accomplished by employing a model with various activation functions and iterating until a greater accuracy is attained, as well as by performing further data purification up front.
