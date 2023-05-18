# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    * Creating a machine learning model to predict healthy vs risky loans
* Explain what financial information the data was on, and what you needed to predict.
    * this model uses the following variables to predict: loan_size, interest rate, income, debt, etc.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    * there are much more good loans than bad. 
* Describe the stages of the machine learning process you went through as part of this analysis.
    * created features, split data, fit trained model, make predictions on test data. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
    * used a logistic regression model. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy of 99% overall. Precision of ~93.5%, recall of ~95%



* Machine Learning Model 2:
  * Accuracy of 99%, precision of ~93.5%, recall of ~99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
    * The second model performs best based on our classification report. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
    * its more important to predict risk correctly. i would rather predict risky and deny the loan but it would have been good. 

If you do not recommend any of the models, please justify your reasoning.
