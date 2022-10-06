# -Neural_Network_Charity_Analysis

![image](https://user-images.githubusercontent.com/106290364/194185815-d1f9a5cb-6b13-478d-ba0c-446aa7706b2a.png)

## Purpose
Alphabet Soup, wants to predict where to make investments. The goal is to use machine learning and neural networks to apply features on a provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results

What variable(s) are considered the target(s) for your model?
Checking to see if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.

What variable(s) are considered to be the features for your model?
The IS_SUCCESSFUL column is the feature chosen for this dataset.

What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME columns will not increase the accuracy of the model and can be removed to improve code efficiency.

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the optimized model, layer 1 started with 120 neurons with a relu activation. For layer 2, it dropped to 80 neurons and continued with the relu activation. From there, the sigmoid activation seemed to be the better fit for layers 3 (40 neurons) and layer 4 (20 neurons).

Were you able to achieve the target model performance?
The target for the model was 75%, but the best the model could produce was 72.7%.

What steps did you take to try and increase model performance?
Columns were reviewed and the STATUS and SPECIAL_CONSIDERATIONS columns were dropped as well as increasing the number of neurons and layers. Other activations were tried such as tanh, but the range that model produced went from 40% to 68% accuracy. The linear activation produced the worst accuracy, around 28%. The relu activation at the early layers and sigmoid activation at the latter layers gave the best results.

## Summary 
The models accuracy ended up being 72.8%. The best way to increase the accuracy of your model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.
