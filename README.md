# Machine-Learning-Capstone-Project

10Alytics Capstone Project- Online Payment Fraud Detection Machine Learning Problem 

Definition 

Fraud is a major challenge which results in Financial losses, disputes, customer dissatisfaction and reputational damage to the affected Financial institution whenever it occurs.As result of the large volume of transactional data invoved, Machine Level models is the best option for dealing with this challenge.The aim of this project, therefore, is to build a Machine Learning Model that can automatically and proactively predict and identify fraudulent online payment transactions more accurately thereby improving customer patrongate and higher return on investments.
Steps Taken

•	The data set was imported from the link provided.

•	I performed some exploratory data analysis (EDA) on the dataset for a better insight. 

•	Data cleaning/ wrangling was done which includes encoding of categorical variables

•	The relevant libraries were imported after which the target and relevant features were selected.

•	The dataset was splitting into two namely training and test datasets using the ratio 70:30

•	Two supervised machine learning models, Decision Tree Classifier and Random Forest were imported and used to train and retrain the model was trained using the training dataset.

•	The measurement metrics namely accuracy_score, classification_report and confusion_matrix were imported from sklearn.metrics and used to measure the performance of the models.

From the findings,The DecisionTreeClassifier Model has an accuracy score of 0.999570, precision of 0.82 and recall of 0.81 while the RandomForestClassifier has an accuracy score of 0.999758, precision of 0.80 and recall of 0.98
The two models produced good results but RandomForestClassifier should be deployed as it outperformed the other model with an accuracy score of 0.999758 and a recall value of 0.98
