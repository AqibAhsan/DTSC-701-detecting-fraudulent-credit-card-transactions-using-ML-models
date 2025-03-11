This project focuses on detecting fraudulent credit card transactions using machine learning models. The dataset used contains 13,788 rows and 394 columns, with a small percentage (2.75%) of fraudulent transactions. The goal is to identify fraudulent transactions among many and test different models to determine the most accurate and efficient one for fraud detection.

The project aims to develop a model to identify fraudulent transactions in real-time to help society mitigate fraud.

Pyspark, the Python API for Apache Spark, is used due to its ability to handle large-scale datasets efficiently.
The dataset is unbalanced (with more genuine transactions than fraudulent ones).
Data preprocessing involves cleaning, handling missing values, and transforming the dataset for machine learning algorithms.

Four machine learning models were trained and tested: Naive Bayes, Artificial Neural Network (ANN), Random Forest, and Gradient Boosting.
The models use PySpark tools like StringIndexer, VectorAssembler, and StandardScaler for data preprocessing and classification.

Model Evaluation:
Performance metrics such as accuracy, error rate, ROC AUC (Area Under the Curve), and training and prediction times were used to evaluate each model.

The goal was to determine which model is both the most accurate and efficient in detecting fraudulent transactions.

Model Comparison:
A comparison table was created to showcase the accuracy, error rate, ROC AUC, and processing times of each model to identify the best performing model.

This project has significant real-world applications as it could help detect fraudulent transactions in the massive amounts of data processed daily by financial institutions, ensuring quicker responses and minimizing losses.
