# Predicting Revenues for Apprentice Chef Inc.

## Project Description
Build a predictive model on a continuous response variable (Y-variable). This assignment encompasses feature engineering, model preparation, variable selection, and model development. Your dataset for this assignment is the Apprentice Chef, Inc. dataset from the pre-course assignment. Use REVENUE as your response variable (y-variable).

Modeling Criteria and Violation Penalties 

<b>Criterion 1 – Train-Test Gap</b><br>
Gap between training and testing scores must be less than or equal to 0.05. In train-test split, make sure your random_state is set to 219 and your test_size is set to 0.25.

Violation Penalty
If the gap is greater than 0.05, your final model points will be reduced by the amount of the gap that exceeds 0.05. For example, if the train-test gap is 0.06, your final model points will be reduced by 0.01.

If your random_state is not set to 219 or your test_size is not set to 0.25, this will be manually adjusted when your deliverable is being graded and your grade will be reduced by by 0.025. Note that this adjustment may result in a different final model R-Square than in your original submission.

<b>Criterion 2 – Response Variable Usage</b><br>
The response variable cannot be used in any form as an explanatory variable (the y-variable cannot be used on the X-side). This includes logarithmic versions of the y-variable, and features that were engineered using the y-variable.

Violation Penalty
The following will occur if the response variable was used as an explanatory variable:

The model will be rescored after such variables has been removed. This will likely result in a major reduction in your final score, so be careful!
The best model in your final model table that does not include the y-variable on the X-side will be assessed.
Your grade for this deliverable will be reduced by one letter grade (-10 points).
 
<b>Criterion 3 – Model Types</b><br>
Model types are appropriate for the task at hand and come from scikit-learn (other packages and/or engines are not permitted). However, you may use statsmodels to evaluate your model statistics, as long as your final model is in scikit-learn. Note that you are permitted to adjust the optional arguments of the permitted model types.

Permitted Model Types
You may only use the model types presented in class and must use them from statsmodels or sklearn.

Violation Penalty
Final models that are not in the list of permitted model types will be discarded and the last appropriate model that ran in your code will be used as your final model. Final model points will be reduced by 0.025.

<b>Criterion 4 – Errors, Code Comments and  Markdown</b><br>
For this assignment, aim for a minimum one quality comment for every 5 lines of code.

Violation Penalty
Not being well-commented will reduce your final model points by 0.025.
Not being within the markdown limit will reduce your final model points by 0.025.
Submitting a code with at least one error will reduce your final model points by 0.025.

<b>Criterion 5 – Code Processing Time</b><br>
Your code must process from beginning to end in 60 seconds or less, based on your computer’s processing speed. There is no requirement to calculate processing time in your code as this can be done by hand (your code is very likely to be significantly under the processing time limit).

Violation Penalty
Going over the processing limit will result in a 0.025 reduction in model points.
 
<b>Criterion 6 – Model Output</b><br>
Model results are outputted as a dynamic string (i.e., f-string) at the end of your script. This must be the very last thing that your Jupyter Notebook outputs. DO NOT write this in a markdown cell or export as an Excel file. This must be a dynamic string.

Output table of candidate models is well-formatted and contains the following information:
- Model Type
- Training Score
- Testing Score
- Train-Test Gap
- It is clear which model is your final model (label it accordingly). The final model MUST be labeled in your dynamic string to meet this criterion.

Violation Penalty
Not including all of the above information in a well-formatted dynamic string will result in a 0.025 reduction in model points.
If it is unclear which model was selected as the final model, the following will occur, the last model in the dynamic string will be utilized as your final model.

<b>Criterion 7 – X-Variable Usage</b><br>
The original and logarithmic versions of an x-variable may not be used in the same model. You must choose one or the other. This does not include engineered features based on these variables.
No exponential or polynomial versions of the x-variables are allowed. In other words you are not allowed to square any of the x-variables in feature engineering (use any other exponents on them).
 
Violation Penalty
If either of the above are violated, all but the original version of the x-variable will be removed from your model and it will be rerun again. Your final model points will also be reduced by 0.025.

<b>Criterion 8 - Full Dataset Usage</b><br>
You are not permitted to remove or modify any observations from the original dataset, with the exception of imputing missing values (you are not permitted to remove observations with missing values). Also, your Jupyter Notebook must be able to be run from the original dataset (no feature engineering or alterations in Excel or other tools are permitted). However, you may engineer new features (columns) and log-transform existing features.

Violation Penalty
If the above is violated, your Jupyter Notebook will be rerun from the original dataset and any errors that result from this will be subject to Criterion 4 above. Your final model points will be reduced by 0.025.
 
 ## Project Outcome
Developed a regression model to accurately predict revenues with an R-squared of 0.82
