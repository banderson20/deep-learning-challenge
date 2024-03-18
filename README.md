# deep-learning-challenge

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
  The target of my model was the variable IS_SUCCESSFUL
What variable(s) are the features for your model?
  The variables that are the features of my model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMT. 
What variable(s) should be removed from the input data because they are neither targets nor features?
  The variables that should be removed from the input data are the columns EIN and NAME.


Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
  I selected 
Were you able to achieve the target model performance?
Yes I was able to achieve the target model preformance uisng the keras_tuner libary to tune the model as best it can. 
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
