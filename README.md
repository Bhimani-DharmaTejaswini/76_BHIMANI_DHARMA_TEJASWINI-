F4-Transaction Fraud Detection(Imbalanced Classification)
Problem:Detect fraudulent payments in a skewed dataset,report precision/recall
This project focuses on detecting fraudulent mobile money transactions using machine learning techniques on a highly imbalanced dataset. The model predicts whether a transaction is fraudulent and provides a fraud probability (%), helping financial systems flag high-risk transactions efficiently.
The dataset contains csv files with data step,type,amount,amount,nameOrig,OldbalanceOrg,newbalanceOrg,nameDest,newbalanceDest,oldbalanceDest.
We take these parameters of transaction as input and based on the trained model we test them give output whether it is fraud or not and it is flagged or not. 
The solution is built using the PaySim synthetic financial dataset, which closely simulates real mobile money transaction behavior.
The main objective is to detect fraudulent transactions from skewed financial data,handle extreme class imbalance effectively,Optimize fraud detection using precision, recall, and precision@k,generate a fraud score CSV for batch or real-time scoring.
The workflow includes data preprocessing, domain-driven feature engineering, stratified train-test splitting, and imbalance handling using class weighting.
Model evaluation emphasizes precision, recall, F1-score, ROC-AUC, and precision@k / recall@k, rather than accuracy, to align with business requirements. Threshold tuning is applied to maximize fraud detection while controlling false alerts, and the final model generates a fraud_score.csv for batch or real-time scoring.
The model we used to evaluate is LightGBM. It trains very fast even on large datasets, handles imbalanced data effectively using class weights, captures complex non-linear patterns better than simple models, gives higher precision and F1-score for rare classes like fraud, uses less memory compared to traditional tree models, and is widely used in real-world industry applications such as banking and fintech systems.
Using LightGBM method the value of precision and recall values are high compared to Logistic Regression and Random Forest.
