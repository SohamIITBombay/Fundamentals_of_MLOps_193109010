## Part 1:
1. AIOps vs. MLOps
Although ML is just one application of AI, AIOps and MLOps have stark differences within an organization.<br>
AIOps is concerned with improving the efficiency of IT operations. The imporovement in efficiency is achieved by automating several IT tasks such as incident diagnostics, Management diagnostics, root cause analysis, anomaly detection with the help of AI. The trained AI models are fed with the data coming from IT operations and in turn it gives the technical teams high quality information that is easy to understand. This helps in getting to a solution faster too.<br>
MLOps is concerned only with bridging the gap between ML experimentation and ML production. It looks to overcome the gap between data science, ML team and the IT team (Operations team) so as to get the ML models into production faster and more often.

&nbsp;&nbsp;&nbsp;&nbsp;With MLOps, the aim is to speed up the process of getting ML models into production whereas with AIOps, the aim is to speed up the IT operations with the help of AI. AIOps directly applies AI/ML to the IT operations whereas MLOps is more about streamlining the building, deployment and maintenance of the ML algorithms rather than focussing heavily on these algorithms alone.

2. Interpretable Machine Learning:
Interpretability is defined as the degree to which a human can understand the cause of a decision. A highly interpretable machine learning model would mean that it would be easier to understand and explain why a certain prediction was made. We need interpretability in ML models for several reasons such as understanding phenomena, satisfying human curiosity, knowing feature importance etc. <br>
Linear regression being linear by definition, it is highly interpretable. Linear regression model predicts the target as a weighted sum of the features. The weights from this linear combination of input features are evaluated after training the algorithm and the interpretation of these weights depends on the nature of the input variable:
- Numerical Feature - Increasing a numerical feature by 1 increases the target outcome by the corresponding weight. <br>
So e.g. if a weight of a feature is say 100, increasing the feature value by 1 would increase the target by 100.
- Binary Feature - Changing the state of the binary variable (from 0 to 1 or from 1 to 0) changes the target variable's value by the corresponding weight. <br>
SO e.g. if a weight of a binary feature is -5 and current state of the feature is 0; Then the target value decreases by 5 if state of the feature changes to 1.
- Intercept - In the case where all the feature values are zero, the target variable takes the value of the intercept. In real world, this has no meaning. Only if the input features are standardized, it would mean that when the feature values are at their mean, the target value changes by the value of intercept.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;Linear regression has several markers indicative of its interpretability:
- R-square value: R^2 = 1 - (Squared sum of errors/Sum of variance) - Indicates proportion of variance explained by the model
- t-statistic: it is the estimated weight scaled by its corresponding standard error.
<br>
<br>

## Part 2:
![image](AWS_console.png)
