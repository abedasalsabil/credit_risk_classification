# credit_risk_classification

The jupyter notebook is available in the credit_risk folder.

##Overview
The purpose of my analysis was to use various techniques to train and evaluate a model based on loan risk. 

##Results  
With Original data
* accuracy: 0.99
* healthy loan precision: 1.00
* high risk loan precision: 0.87
* healthy loan recall: 1.00
* high risk loan recall: 0.89

With Random OverSampler
* accuracy: 0.99
* healthy loan precision: 0.99
* high risk loan precision: 0.99
* healthy loan recall: 0.99
* high risk loan recall: 0.99

##Summary
I would not recommend this model to be used by the company, because when the model was used with very large samples, the model produced the same answer across all spectrums, with a score of 0.99. The model however could potentially work well with smaller datasets as it produces more accurate results as shown in the bulleted list provided.
