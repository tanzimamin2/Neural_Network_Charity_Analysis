# Neural_Network_Charity_Analysis

## Overview of Project
### Purpose
The purpose of this analysis is to create a deep-learning neural network by using the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


## Results
Lets take a closer look at the analysis and our findings:-

### Data Preprocessing

**1) What variable(s) are considered the target(s) for your model?**
* **_Target Variable_**:- ```IS_SUCCESSFUL```

**2) What variable(s) are considered to be the features for your model?**
* The model's _**features**_ are the variables that allow a prediction or independent variables, defined by:
  * ```APPLICATION_TYPE```, ```AFFILIATION```, ```CLASSIFICATION```, ```USE_CASE```, ```ORGANIZATION```, ```STATUS```, ```INCOME_AMT```, ```SPECIAL_CONSIDERATIONS```and ```ASK_AMT```

**3) What variable(s) are neither targets nor features, and should be removed from the input data?**
* These variables should be _**removed**_:-
  * ```EIN```
  * ```NAME```

### Compiling, Training, and Evaluating the Model


**1) How many neurons, layers, and activation functions did you select for your neural network model, and why?**
* For the first attempt, two layers were used (_First layer-_ 80 Neurons, Second layer- 30 Neurons. 

  For the code to be more accurate, three layers were added and the neuron count increased.
  
  Even after adding more layers the accuracy did not increase (the accuracy stayed around 72%)
  
* For the third attempt, third layer was removed and the neuron count was increased (_First layer-_ 200 Neurons, _Second layer-_ 80 Neuron).

**2) Were you able to achieve the target model performance?**
* No

**3) What steps did you take to try and increase model performance?**
* New layers were added but did not help
* Neuron count was increased. Helped a bit, still was not able increse the accuracy over 75%

## Summary

In summary, we created a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. We used the charity_data.csv dataset with 72% accuracy. This did not meet the 75% accuracy target and the optimization methods used here did not help.

After multiple attempts, hidden layers were increased and decreased. Neuron counts were increased and decreased. But did not result in a better performance.

## Links
  * Visit this [link]() for the excel dataset and other resources.
   
