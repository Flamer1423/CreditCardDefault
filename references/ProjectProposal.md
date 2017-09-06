Project Proposal
-----------------

Many financial institutions provide lending options to their membership as an added revenue stream for continued operations. Lending on scale, however, holds a tremendous amount of financial risk and can cause disastrous loss to an organization if not well controlled and frequently evaluated. As a result, financial institutions need accurate projections of expected  loan losses on their lending portfolios. I aim to create a program that can predict a credit card portfolio’s default performance; which loans are most likely to charge off and what are the most prevalent factors to predict default. By data mining and modelling UCI’s open source credit card default dataset, I will apply my research to my Credit Union’s relevant credit card data. This will allow my organization to set repayment expectations and better allocate funds in their allowance for loan losses.

To solve this problem, I will follow the CRISP-DM process.
1. Understanding
    - Business
        * Establish the business problem 
        * Identify target
    - Data 
        * Extract and load from UCI’s open source csv dataset to dataframe
        * Characterize data & analyze data on basic level
2. Prepare
    - Clean - Remove and/or fix missing/incomplete data
    - Sample - Consider size of dataset and take smaller representative sample if necessary. Determine whether the class probability is imbalanced.
    - Scaling - Identify if preprocessed data contains attributes with varying quantities or scales. Transform to a standard scale if necessary
    - Attribute Decomposition - Identify if there are complex - attributes that need to be split into constituent parts that would be useful to a machine learning algorithm
    - Aggregation - Identify features that can be combined into an aggregate number for more meaningful analysis
3. Hypothesize and Model
    - Exploratory Data Analysis
        * Inferential Statistics
        * Data Visualizations
    - Binomial Classification
        * Decision Tree
        * Logistic Regression
        * Support Vector Machine
3. Evaluate
    - Examine results
    - Calculate Accuracy
        * Confusion Matrix
        * ROC (Receiver Operating Characteristic)


I will expect to complete project after providing the following deliverables.
- Project code
    * Well documented code used to solve problem
- Report
    * Document explaining problem, approach, findings, and recommendations
- Presentation
    * Slide deck that can be shared with relevant audience to concisely convey report items 	