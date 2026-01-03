F4-Transaction Fraud Detection(Imbalanced Classification)
Problem:Detect fraudulent payments in a skewed dataset,report precision/recall
This project focuses on detecting fraudulent mobile money transactions using machine learning techniques on a highly imbalanced dataset. The model predicts whether a transaction is fraudulent and provides a fraud probability (%), helping financial systems flag high-risk transactions efficiently.
The dataset contains csv files with data step,type,amount,amount,nameOrig,OldbalanceOrg,newbalanceOrg,nameDest,newbalanceDest,oldbalanceDest.
We take these parameters of transaction as input and based on the trained model we test them give output whether it is fraud or not and it is flagged or not. 
The solution is built using the PaySim synthetic financial dataset, which closely simulates real mobile money transaction behavior.
The main objective is to detect fraudulent transactions from skewed financial data,handle extreme class imbalance effectively,Optimize fraud detection using precision, recall, and precision@k,generate a fraud score CSV for batch or real-time scoring
