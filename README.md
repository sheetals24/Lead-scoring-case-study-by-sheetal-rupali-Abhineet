# Lead-scoring-case-study-by-sheetal-rupali-Abhineet
Problem Statement:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. The company requires us to build a model wherein we need to assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance.
Goals of the Case Study:
1.	Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads.
2.	Need to make recommendations based on the model. 
Solution Approach:
I.	Data Preparation, Cleaning and EDA
II.	Test-train Split and Scaling
III.	Model Building
IV.	Model Evaluation
V.	Predictions on the Test Dataset
VI.	Conclusion
	Final Observation:

o	Train Dataset:
Accuracy	0.91
Sensitivity	~ 0.81
Specificity	0.97
Precision	0.94
Recall	0.81

o	Test Dataset:
Accuracy	0.90
Sensitivity	~ 0.95
Specificity	0.87
Precision	0.80
Recall	0.95


	Recommendations
X-Education will have to mainly focus important features responsible for good conversion rate which are as follows:
o	Occupation_Working Professional: The company should focus on working professionals as these leads have higher lead conversion rate.
o	Last Activity_SMS Sent: Leads whose last activity is sms sent can be potential leads for company.
o	Occupation_Unemployed: Occupation is 'Unemployed' feature has a good conversion rate. Company can target this feature as in order to get employed people want to upskill themselves.
o	Tags will revert after reading the mail: This feature also has a good Conversion rate.
