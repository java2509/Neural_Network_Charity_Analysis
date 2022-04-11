#### Neural Network Charity Analysis

### Overview of the analysis: 

### Purpose:

Beks is going to use her knowledge of machine learning and neural networks to help Alphabet Soup predict whether the organizations that have received funding will be successful if funded.

### Results: 

Data Preprocessing:
 
1.) What variable(s) are considered the target(s) for your model?

   The target variable for this model is the "IS_SUCCESSFUL" COLUMN

2.) What variable(s) are considered to be the features for your model?

   The features of the model are:

   - APPLICATION_TYPE          
   - AFFILIATION               
   - CLASSIFICATION            
   - USE_CASE                  
   - ORGANIZATION              
   - STATUS                    
   - INCOME_AMOUNT                
   - SPECIAL_CONSIDERATIONS     
   - ASK_AMOUNT                   

3.) What variable(s) are neither targets nor features, and should be removed from the input data?

   NAME and EIN were removed as it does not add to the accuracy to the model. 

Compiling, Training, and Evaluating the Model:

1.) How many neurons, layers, and activation functions did you select for your neural network model, and why?

The orginal model had neurons and layers to to match the output of the starter code i.e 80 and 30, I used the 

2.) Were you able to achieve the target model performance?

No, it would be just under 75%

3.) What steps did you take to try and increase model performance?

- Added a third hidden layer
- Additional nuerons were added to the hidden layer
- The epochs were increased to 300
- The activation for the outer layer from "sigmoid" to "tanh" 


### Summary: 


Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification 

problem, and explain your recommendation.
