### Neural Network Charity Analysis

# Overview of Analysis:
With Neural Networks and Machine Learning, we created a binary classifier that will predict if applicants that were funded by the Alphabet Soup will be successful or not.
This project had 3 steps which were
* 1. Preprocessing the data for the neural network
* 2. Compile, Train, and Evaluate the model
* 3. Optimize the model

# Results
# Data Preprocessing
* 1. The IS_SUCCESSFUL column was the target of this model
* 2. Other variables considered for the model features were: every column except IS_SUCCESSFUL which is our goal so the other ones will be dropped.
* 3. There were a few variables that were not either targets or feautres for the dataset: we dropped the EIN, NAME columns because there was no impact to the outcome.

# Compiling, Training and Evaluating the Model
For the neural networks there were 2 hidden layers.

# Summary
The model ended with a 50% accuracy score after optimization.
