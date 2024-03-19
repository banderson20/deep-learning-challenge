# deep-learning-challenge

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
  <br>The target of my model was the variable IS_SUCCESSFUL</br>
What variable(s) are the features for your model?
  <br>The variables that are the features of my model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMT. </br>
What variable(s) should be removed from the input data because they are neither targets nor features?
 <br>The variables that should be removed from the input data are the columns EIN and NAME.</br>


Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
  <br>I selected  </br>
Were you able to achieve the target model performance?
<br>Yes I was able to achieve the target model preformance uisng the keras_tuner libary to tune the model as best it can.</br> 
What steps did you take in your attempts to increase model performance?
<br>I used the keras_tuner to optimize the model as best as I could.</br>
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
<br>In summary this deep learning model isn't the best at predicting whether a loan applicant will be successful as it got an accuracy of .75. I would recommed uisng a random forest model as it is very good at prediction as well as showing which features are the most important for the models success.</br>
