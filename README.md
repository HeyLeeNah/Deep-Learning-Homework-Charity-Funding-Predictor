# Deep-Learning-Homework-Charity-Funding-Predictor

•What variable(s) are considered the target(s) for your model?

The target variable that used was the "IS_SUCCESSFUL" column (Was the money used effectively)


•What variable(s) are considered the feature(s) for your model?

EIN and NAME—Identification columns.
However, I kept 'NAME' for optimization work



•How many neurons, layers, and activation functions did you select for your neural network model, and why?

I used three hidden layers with 100, 30, and 10 neurons because having more layers usually yields a higher accuracy. I used the “relu” activation for the first and “sigmoid” for the others, because since we used pd.get_dummies all the train and test data were represented by zero and ones, and “sigmoid” was a better fit for that.


•Were you able to achieve the target model performance?
After optimizing the model, I was able to achieve the target model performance of accuracy higher than 75%, 0.7897, higher than my first try which was at 0.7284.


•What steps did you take to try and increase model performance?
I played around with the number of features, bins and neurons, I added the identifier 'NAME’.
