# Fraudulant_Firm_Detection_Python

The goal of the research is to help the auditors by building a classification model that can predict the fraudulent firm on the basis of present and historical risk factors. The information about the sectors and the counts of firms are listed respectively as Irrigation (114), Public Health (77), Buildings and Roads (82), Forest (70), Corporate (47), Animal Husbandry (95), Communication (1), Electrical (4), Land (5), Science and Technology (3), Tourism (1), Fisheries (41), Industries (37), Agriculture (200)

Many risk factors are examined from various areas like past records of audit office, audit-paras, environmental conditions reports, firm reputation summary, on-going issues report, profit-value records, loss-value records, follow-up reports etc. After in-depth interview with the auditors, important risk factors are evaluated and their probability of existence is calculated from the present and past records

Regression Task
- Applied the following regression models: KNN repressor, linear regression, Ridge, Lasso, polynomial regression, SVM both simple and with kernels
- Used Grid Search to find the best scaling parameter. Plotted graphs to get a better glimpse of the results
- Used Cross Validation to find average training and testing score
- Found the best regressor and trained the model on the entire dataset using the best parameters and predicted buzz for the test_set

Classification task
- Applied the following classification models: KNN classifcation, Logistic Regression, Linear Supprt Vector Machine, Kerenilzed Support Vector Machine, Decision Tree
- Genereated the Confusion Matrix for all the classifiers
- Found the best classifier and trained the model on the entire dataset using the best parameters and classified the test_set

Ensemble Learning Technique
- Improved the model accuracies by 15% by implementing different ensemble learning techniques such as AdaBoost, Bagging, Pasting and Gradient Boosting

 
