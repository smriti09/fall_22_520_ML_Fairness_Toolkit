# Comparison of ML_Fairness_Toolkit

Machine learning bias is observed when the data the model is trained on has any over or under-representation of one or many labels. When trained on such data the model unintentionally produces a biased algorithm which puts limitations on the model's accuracy. When training on skewed, imbalanced data or insufficient data, machine learning algorithms tend to give a biased outcome and hence reduce the efficiency of the model. Today there are many open-source machine learning algorithm fairness tools that address this data bias problem and contain a comprehensive set of fairness metrics for evaluating data-sets and machine learning models. They have algorithms to mitigate bias in data-sets at the pre-processing and model training stages. In this paper, we will study two such tools namely AI Fairness 360 by IBM and Verify ML for training our model to mitigate any bias in the data. We plan to give a comprehensive study of both tools to compare the ease with which the user can train a model. We support our claims through an experimental analysis of the Compas data-set which we trained on both these tools to study the bias mitigation algorithms. We trained the model using different algorithms provided by each individual library and evaluated the results using the bias metric each tool offered.   

Our aim is to compare 2 ML fairness tools for checking the types of biases the tools evaluate and the fairness tests they perform.
○ AI Fairness 360
○ VerifyML



python=3.7

Installations we have done so far:
>> pip install verifyml

>> pip install aif360
