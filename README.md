# Module 21: Deep Learning Challenge

### Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organisations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organisation, such as:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organisation classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organisation type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Report

### Overview 
The purpose of the analysis is to assist identifying organisations for funding. 

### Results

#### Data Preprocessing

- What variable(s) are the target(s) for your model?
    - Target variable is the 'IS_SUCCESSFUL' data 
- What variable(s) are the features for your model?
    - Feature varaibles included data from other columns in the dataframe 
- What variable(s) should be removed from the input data because they are neither targets nor features?
    - The 'EIN' and 'NAME' columns were removed as they were not relevant and considered ID columns (neither a target or feature)

#### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - For the first attempt, 10 neurons in the first layer and 5 neurons in the second layer were used with 100 epochs. The values were random to obtain a starting point for the model 
- Were you able to achieve the target model performance?
    - Model accuracy of > 75% wasn't achieved 
- What steps did you take in your attempts to increase model performance?
    - Added another hidden layer for a total of 3 hidden layers from 2 hidden layers 
    - Varying number of neurons to a hidden layer 
    - Increased number of epochs to the training regimen to 200 from 100 

### Summary
Model accuracy above 75% wasn't achieved. Increased model accuracy could be achieved by obtaining additional data,  or using a model with varying activation functions and further iterations. 


