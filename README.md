# Group 6 Final Assessment 

### Introduction
* The purpose of this project was to implement an interpretable machine learning (ML) model that takes into consideration real-world problems in ML, such as security, privacy, and discrimination.
* The type of ML model that was used in this project was an explainable boosting machine model (EBM) which is a tree-based, cyclical gradient boosting generalized additive model (GAM) with automatic detection that is just as accurate as a blackbox model while remaining interpretable. 
* The follwing group members that worked on developing the EBM model include Runzhe Tang, Qian Xie, and Matias Roca. 

### Intended Use
* Describe the business value of your group’s best remediated model
* Describe how your group’s best remediated model is designed to be used
* Describe the intended users for your group’s best remediated model
* State whether your group’s best remediated model can or cannot be used for any additional
purposes

# IMAGES EXAMPLE
![](images/demo.png)


### Training Data
* The Home Mortgage Disclosure Act (HDMA) training data was downloaded from this Github repository: https://github.com/jphall663/GWU_rml/tree/master/assignments/data.
* The data was split into train and validation partitions using a 0.7 split ratio or 70% train and 30% test split. 
* Training data had a total of 112,253 rows and 23 columns while the validation data had a total of 48,085 rows and 23 columns. 
* The following table below explains the meaning of all the training data columns: 

Variable  | Meaning
------------- | -------------
high_priced  | Binary target, whether (1) or not (0) the annual percentage rate (APR) charged for a mortgage is 150 basis points (1.5%) or more above a survey-based estimate of similar mortgages. 
conforming  | Binary numeric input, whether the mortgage conforms to normal standards (1), or whether the loan is different (0), e.g., jumbo, HELOC, reverse mortgage, etc.
debt_to_income_ratio_std  | Numeric input, standardized debt-to-income ratio for mortgage applicants.
debt_to_income_ratio_missing  | Binary numeric input, missing marker (1) for debt to income ratio std.
income_std  | Numeric input, standardized income for mortgage applicants.
loan_amount_std  | Numeric input, standardized amount of the mortgage for applicants.
intro_rate_period_std  | Numeric input, standardized introductory rate period for mortgage applicants.
loan_to_value_ratio_std  | Numeric input, ratio of the mortgage size to the value of the property for mortgage applicants.
no_intro_rate_period_std  | Binary numeric input, whether or not a mortgage does not include an introductory rate period.
property_value_std  | Numeric input, value of the mortgaged property.
term_360  |  Binary numeric input, whether the mortgage is a standard 360 month mortgage (1) or a different type of mortgage (0).

### Evaluation Data 
* State the source of evaluation (or test) data
* State the number of rows in evaluation (or test) data
* State any differences in columns between training and evaluation (or test) data

### Model Details
* State the columns used as inputs in your group’s best remediated model
* State the columns used as targets in your group’s best remediated model
* State the type of your group’s best remediated model
* State the software used to implement your group’s best remediated model
* State the version of the modeling software for your group’s best remediated model
* State the hyperparameters or other settings of your group’s best remediated model

### Quantitative Analysis
* State the metrics used to evaluate your group’s best remediated model
* State the values of the metrics for training, validation, and evaluation (or test) data – evaluation (or test) metrics come from the most recent class full evaluation results, link under Assignment 1.
* Provide at least one plot or table from each weekly assignment for a total of at least six plots,
that must include the global variable importance and partial dependence of your group’s best
remediated model.
* Address other alternative models considered

### Ethical Considerations
* Describe potential negative impacts of using your group’s best remediated model:
    * Consider math or software problems
    * Consider real-world risks: who, what, when and how?
* Describe potential uncertainties relating to the impacts of using your group’s best remediated
model:
  * Consider math or software problems
  * Consider real-world risks: who, what, when and how?
* Describe any unexpected or results encountered during training
