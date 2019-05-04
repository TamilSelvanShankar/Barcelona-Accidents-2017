# Barcelona-Accidents-2017
Depending upon location and the time of the day, day of the week etc., can accident related data be predicted? List of accidents handled by the local police in the city of Barcelona is available as a dataset. It has The number of injuries by severity The number of vehicles  The location of the accident Objective: Predict the number of vehicles involved in accident.
Data:
Accidents in the city of Barcelona in 2017
Size: 10340 X 15

Attributes:

Id
District Name
Neighborhood Name
Street
Weekday
Month
Day
Hour
Part of the day
Mild injuries
Serious injuries
Victims
Vehicles involved (*)
Longitude
Latitude

Approach and Techniques:
Techniques like Linear Regression and LR with SGD,
Logistic Regression (OVR for multi-class), Logistic Regression (OVR with one new feature),
	note: Logistic Reg. always runs with L2 by default.
For class balancing-SMOTE, ADASYN (Logistic Reg.).

Metric Comparison:
Logistic Regression 
Multi-Class(OVR):
Accuracy: 68.3%
Precision: 
           class 1: 68.4%
Recall:
           class 1: 99.8%
F1 Score:
           class 1: 81.2%

Learnings:
Explored different types of Regression techniques.
For removing class imbalance, we used SMOTE and ADASYN.
When there is no linear relationship exists between the explanatory and predicted variables, Linear R gives poor R-Squared

Business use case:
Cities need to gear themselves up to handle accidents involving vehicles. This means,
Better management of traffic.
Better emergency response.
Better first-aid in the golden-hour after any accident.


