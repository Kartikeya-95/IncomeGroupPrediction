This repository contains Predictive Analysis of Census Income Data Set, credit to UCI Machine Learning Repository.
In the data set we have Income Group as label and all other variables are dependent on the label, as they contribute towards
the prediction of Income Group.

If we hyphothise the variables that are responsible for change in Income of a person, the following parameters come to our mind:
1. Age - income will move upwards with age, as the productivity increases with age until a point where it starts going down
2. Education - Higher education results in higher pay
3. Experience - People with higher experience are high earners
4. Occupation - it also affects the income, different occupations have different pay
5. Location - if you are working in a metro city or urban area you will be earning more than the one working in rural or village area
6. JobType - whether you are permanent or temporary
7. Working Hours - people who are working more will be earning more
8. Native Country - country also affects the income, people from rich and economically strong country will be earning more than 
   developing and small countries
   
 There can be many more parameters that we can hyphothise which affects the Income of a person like Workclass, Relationship, Race, Sex, 
 MartialStatus, Skills, Company, LandOwned, CollegeType etc.
 
 Here, we used 10 of these variables which contribute towards Income Group namely Age, Workclass, Education, Martial-Status, Occupation,
 Relationship, Race, Sex, Hours-Per-Week and Native-Country. 
 
 We first need to generate the hyphothesis, right after we get the problem definition, because in that way data collection will become 
 easier and specific. Also, we will not be biased towards what is available. There is so much data available for a particular field/domain 
 and it will require so much effort to analyze it before moving further. Collecting the data based on the hyphothesis will make it easier 
 for us to analyze the data.
 
 Here, label is categorical(2 categories), so it is a classification problem. We can apply LogisticRegression, SVM/Kernel SVM, k-NN, 
 Naive Bayes, DecisionTree, RandomForest or Stochastic Gradient Descent.
 
 Here, model performance is checked for LogisticRegression, DecisionTree and RandomForest classifier. The code with proper descriptions
 and comments is under Python/Training 1.ipynb.
 
