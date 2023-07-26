# *Report on The Neural Network Model Performance for Alphabet Soup*

## *Overview of the Analysis:*

The purpose of this analysis was to create a deep learning model using a neural network to solve a classification problem for Alphabet Soup. Tho goal was to predict whether a funding application from various organizations would be successful, enabling Alphabet Soup to make more informed decisions about which applicants to funds.

## *Results:*

### *Data Preprocessing:*

* *Target variable for the model:* The target variable for the model is the "IS_SUCCESSFUL", was the money used effectively, represented as a binary value (1 for successful, 2 for not).
* *Feature variables for the model:* The features for the model are various parameters and characteristics of the funding applications, such as application type, classification, organization type, affiliated sector of industry, and other relevant information.
** Variables to remove from the input data:* Variables that are neither targets nor features, such as name and unique identifiers, were removed to ensure data cleanliness and improve model performance.

### *Compiling, Training, and Evaluating the Model:*

* *Neurons, Layers and Activation Functions:* The specific configuration of neurons, layers, and activation functions is crucial for the neural network model's performance. The third model had three hidden layers with 80, 80, and 20 neurons, respectively, and utilized ReLU and Tanh activation functions. However, to improve the model's accuracy, the architecture can be modified.

* *Model Performance:* The target model performance was defined based on desired accuracy. The model was considered successful if it achieved an accuracy of at least 85%. The model has current accuracy of 55%.
  
* *Steps to Increase Model Performance:*
  * Experimented with different configurations of neurons, hidden layers, and activation functions.
  * Added/reduced the number of epochs to the training regimen.
  * Experimented with the optimizer.
  * Decreased the number of values for each bin in the data.
 
## *Summary:*

The current deep learning model achieved an accuracy of 55%, which falls below the target performance. By implementing the steps for model improvement, I aim to achieve a higher accuracy to make more accurate predictions on funding application approvals.
Recommendation for a Different Model: The final model selection should be based on extensive experimentation, hyperparameter tuning, and cross-validation to ensure it generalizes well to unseen data. Continuously iterating and optimizing the model based on empirical results will lead to improved predictive capabilities for funding application approvals.
