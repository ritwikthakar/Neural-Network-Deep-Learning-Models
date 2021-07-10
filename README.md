# Neural-Network-Deep-Learning-Models

### Overview of Analysis

This project attepts to estimate if applicants will be successful if funded by the Alphabet Soup Co. Alphabet Soup Co. wants to fund to companies but it needs to know in advance whether it will be successful or not. Money is on the line here and we would not want for it to go to waste.

For this I will create a neural network by using Data Manipulation, creating training and testing sets, and finally analyzing my models that I have created.

### Results

##### Data Processing

- To clean the data I removed the EIN and NAME columns since they have no value to the model.
- The varibales being considered for my model are as follows: 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT'. - I dropped "USE_CASE_Other","AFFILIATION_Other" columns.
  My Dependent varible is "IS_SUCCESFUL" since we want to try to predict this with high accuracy.
  
##### Compiling, Training, and Evaluating the Model Attempt #1

- 2 Hidden Layers
- 80 neurons (Layer1), 30 neurons(Layer2)
- Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is for nonlinear datasets.
- Removed "USE_CASE_Other","AFFILIATION_Other" columns.
[!img1](https://github.com/ritwikthakar/Neural-Network-Deep-Learning-Models/blob/main/images/img1.PNG)

