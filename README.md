# GithubRespo
Problem Statement: Was provided with the personal, historical and company data for each employee for a given period and was tasked to predict whether a current employee will be leaving the organization.

Approach: It was a generic classification problem, where some data cleaning and pre-processing, using StandardScaler to normalize the numerical data and provide a normal distribution throughout, was required whereas categorical data were encoded manually to numerical format to fit in data modelling, we were going to use.
Thereafter, I applied LogisticRegression, RandomForest and KNN algorithm to find the best fit, using F1 score, for our problem. Eventually, it was LogisticRegression that yielded better results with F1 score of 0.84. 

ShortComings: 
1. Should have looked into Boosting the learners for better growth and scores.
2. Should've included all the Quarterly Rating for each employee, instead of just the last.
3. Should've looked into the pattern of Employeee Leaving more closely with respect to date and time.


