Overview of the Analysis
The purpose of this analysis is to develop a deep learning model that predicts the success of Alphabet Soup's charitable funding efforts. The goal is to create a model that accurately classifies potential recipients of funding as likely to be successful or unsuccessful, enabling more informed and efficient allocation of resources.

Results

Data Preprocessing
What variable(s) are the target(s) for your model? 
The target variable in this analysis is the binary classification label indicating the success of each funding application (e.g., "IS_SUCCESSFUL").

What variable(s) are the features for your model?
the rest of the columns are the features for the model, for example application_type, affiliation, classification, ask_amt, use_case, income_amt.

What variable(s) should be removed from the input data because they are neither targets nor features?
'Ein' and 'name' columns were removed because they are irrelevant for prediction.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I had selected 43 neurons and 3 layers and relu.

Were you able to achieve the target model performance?
Yes, 1% improved.

What steps did you take in your attempts to increase model performance?
 I increased the amount of features by increasing application type and included 200 and above and classification anything more than 20. I tested 59 neurons, 4 layers, and sigmoid.
