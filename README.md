# Neural_Network_Charity_Analysis

## Objective

## Results

### Data Preprocessing

What variable(s) are considered the target(s) for your model?

* "IS_SUCCESSFUL"

What variable(s) are considered to be the features for your model?

* "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"

What variable(s) are neither targets nor features, and should be removed from the input data?

* "EIN" and "NAME"

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

In my inital model, I started with my first inital hidden layer with 80 neurons and relu activation function. The second hidden layer consisted on 30 neurons and the same activation function. The output layer used a sigmoid activation function.

![Inital Model](https://github.com/doliver231/Neural_Network_Charity_Analysis/blob/main/Images/keras_model.png)

In the optimized model, I added a third hidden layer. Layer 1 had 100 neurons, layer 2 had 30 neurons, and layer 3 had 10. All layers used relu activation functions. Another opitimized model

## Summary

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.




0.7258, 0.5564 loss
0.7256, 0.5608 loss
0.7254, 0.5550 loss
0.7263, 0.5532 loss
