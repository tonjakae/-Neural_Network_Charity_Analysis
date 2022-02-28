# Neural Network Charity Analysis
## Overview of the Analysis
The purpose of this project is to create a binary classifier utilizing machine learning.  The outcome will tell us if it is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Using The Tensorflow Library and the Keras Model we will build a Neural network and attempt to train the network with the given metadata.

## Results 

### Data Preprocessing 

#### 1.) What variable(s) are considered the target(s) for your model?

IS_SUCCESSFUL is a target for my model. Because the purposer of the analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

#### 1.) What variable(s) are considered to be the features for your model?

  - APPLICATION_TYPE
  - AFFILIATION 
  - CLASSIFICATION
  - USE_CASE
  - ORGANIZATION
  - STATUS
  - INCOME_AMT,
  - SPECIAL_CONSIDERATIONS
  - ASK_AMT

#### 2.) What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN
  - NAME

### Compiling, Training, and Evaluating the Model

#### 3.) How many neurons, layers, and activation functions did you select for your neural network model, and why?

  ![image](https://user-images.githubusercontent.com/88631769/148705050-5284735d-2753-4a08-97aa-76bf616708c5.png)

 
#### 4.) Were you able to achieve the target model performance?

  No, the highest accuracy I could achieve is 73%. 
  
#### 5.) What steps did you take to try and increase model performance? 
  
  Adding more hidden layers and changing the activation function for the hidden layers. 
  
### Summary 

The deep learning neural network model did not reach the target of 75% accuracy after 3 attemps. The highest result we could get is 73%. To achieve a higher accuracy, more data needs to be acquired. In a binary classification, we could use a supervised machine learning model to combine numerous decision trees. 
