# Neural Network Charity Analysis
## Overview of the Analysis
The purpose of this project is to create a binary classifier utilizing machine learning.  The outcome will tell us if it is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Using The Tensorflow Library and the Keras Model we will build a Neural network and attempt to train the network with the given metadata.

## Results

#### Data Preprocessing
##### The successful target variable for this analysis and model is the IS_SUCCESSFUL field.

### The following variable(s) should be considered on features model

* ORGANIZATION
* STATUS
* INCOME_AMT
* SPECIAL_CONSIDERATIONS
* ASK_AMT
* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* USE_CASE

### The following variable(s) should be removed from input and data.

* NAME
* EIN

#### 3.) How many neurons, layers, and activation functions did you select for your neural network model, and why?

![image](https://user-images.githubusercontent.com/87340105/155933040-fb275621-fecf-4278-a890-692c13eba275.png)

#### 4.) Were you able to achieve the target model performance?

Unfortunately, I was not able to opptimize the model to achieve the predicted accuracy of 75%. The model maxed at 73% 

![image](https://user-images.githubusercontent.com/87340105/155932917-6c97d313-814c-460b-81d5-9d52d4a19cfb.png)

  
#### 5.) What steps did you take to try and increase model performance? 
  
Added more hidden layers, dropped columns, additional neurons added
  
### Summary 

Overall the neural network model did well with at least a 73% accuracy rate. I would recommend using the Random Forest classifier. The output and feature selection of this model are easy to understand. The data in this analysis is not to complex to need a deep learning model. 
