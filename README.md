# Neural_Network_Charity_Analysis

## The purpose of this analysis was to assist a foundation in predicting where they should place their investments using neural networks and machine learning. 

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
- Removed EIN and Name columns as these were identification columns with no bearing on the accuracy of the model.
- The IS_SUCCESSFUL column was the featured target variable of this analysis as it indicates if funding was successful.


### Compile, Train, and Evaluate the model
- Removed STATUS and SPECIAL_CONSIDERATIONS columns
- The 75% accuracy score was not reached.
- Most successful model was the model in which 9 hidden layers were used starting with 90 units and decreasing units per layer by 10. This resulted in 53% accuracy.
