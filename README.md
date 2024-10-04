Problem Statement:
Many different industries need predictive maintenance solutions to reduce risks and gain actionable insights through processing data from their equipment.
Although system failure is a very general issue that can occur in any machine, predicting the failure and taking steps to prevent such failure is most important for any machine or software application.
Predictive maintenance evaluates the condition of equipment by performing online monitoring. The goal is to perform maintenance before the equipment degrades or breaks down.
This Capstone project is aimed at predicting the machine breakdown by identifying the anomalies in the data.
The data we have contains about 18000+ rows collected over few days. The column ‘y’ contains the binary labels, with 1 denoting there is an anomaly. The rest of the columns are predictors

I utilized Random Forest, Gradient Boosting, and Logistic Regression algorithms to train the dataset and generate predictions. Among these models, the Gradient Boosting algorithm demonstrated superior performance, achieving a tuned accuracy of 0.998 and a ROC-AUC score of 0.998.
