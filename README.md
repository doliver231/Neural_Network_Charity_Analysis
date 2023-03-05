# Neural_Network_Charity_Analysis

## Objective

Using Machine Learning and Neural Networks for this project, I used the features in the dataset to create a binary classifier that will help to predict if the applicants that will be funded by a Charitable organization called Alphabet Soup will be successful. For this analysis we had a dataset containing various measures on 34,000 organizations that have been funded by Alphabet Soup. This project compromised of the following 3 steps:

* Preprocessing the data for the neural network
* Compile, Train and Evaluate the Model
* Optimizing the model

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

In the optimized model, I added a third hidden layer. Layer 1 had 100 neurons, layer 2 had 30 neurons, and layer 3 had 10 neurons. All layers used relu activation functions. Proceeding this model was another version with the same amount of neurons but changed one activation function from relu to sigmoid. Lastly, the rest of the activation functions were changed to sigmoid to observe any effects.

## Summary

The model ended up with the accuracy score of 72.5-72.6% after optimization, which wasn't much change at all from the original model. The initial neural network had a accuracy score of 72.6%. There is a possibilty of the model being overfitted, the more hidden layers and neurons being added. We could further optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is because random forest is a robust model due to their sufficient number of estimators and tree depth. They can be useful when trying to avoid overfitting the model.
