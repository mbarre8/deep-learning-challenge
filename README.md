# deep-learning-challenge


### Data Preprocessing

* What variable(s) are the target(s) for your model?
*   The target variable is the is_successful column

* What variable(s) are the features for your model?
*   The feature variables are all other columns in the dataframe besides is_successful, name, EIN columns

* What variable(s) should be removed from the input data because they are neither targets nor features?
*   The variable that should be removed from the input data is name and EIN since they are neither targets nor features variables

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
*   We used two hidden layers with an relu activation function for both. The first hidden layer had 80 neurons. The second hidden layer had 30 neurons. And we had an output layer with sigmoid activation function with one neuron since we're using a binary classification.

* Were you able to achieve the target model performance?
*   No I was not able to achieve the target model performance of 75% accuracy. The highest accuracy level acheived was approximately 73.05%

* What steps did you take in your attempts to increase model performance?
*   The steps I took in attempts to increase model performance was reduce feature variables (by dropping status and special_consideration in additon to name and ein) which increase accuracy value a bit in the second model. In three attempt I tried to decrease bin size which did not change values much. 
