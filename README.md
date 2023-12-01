# Deep-Learning-Challenge

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
- The model is the 'IS_SUCCESSFUL' boolean

What variable(s) are the features for your model?
- 'APPLICATION_TYPE','AFFILIATION','CLASSIFICATION','USE_CASE','ORGANIZATION','STATUS','INCOME_AMT','SPECIAL_CONSIDERATIONS','ASK_AMT'


What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model.
- Both 'EIN' and 'NAME' are not targets nor features and should be removed from the input data


How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The initial layer had 80 neurons, the second had 22, and the third had 11. After trying different ways to make the model work better, I tested adding a fourth hidden layer. I discovered that the number of neurons per layer I had initially was just right. Also, I found that using tanh and relu activation functions worked best for achieving high performance.

Were you able to achieve the target model performance?
- No

What steps did you take in your attempts to increase model performance?
- I added more layers, removed more columns, added additional hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
- Overall, the deep learning model was around 73% accurate in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by doing additional data cleanup up front, as well as by using a model with different activation functions and iterating until higher accuracy is reached
