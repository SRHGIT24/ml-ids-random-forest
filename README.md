**Machine Learning Intrusion Detection System (UNSW-NB15, Random Forest)**
This project implements a Random Forest–based Intrusion Detection System (IDS) trained on the UNSW-NB15 dataset. The notebook explores preprocessing, training, evaluation, and feature importance analysis for detecting malicious vs. normal network traffic.

📊 Dataset
Source: UNSW-NB15 - Kaggle.com
Records: ~257k
Features: 45 network traffic features (protocol, duration, bytes, etc.)
Labels: Binary classification → Normal (0) or Attack (1)

⚙️ Tech Stack
Language: Python 3
Libraries:
pandas, numpy → Data preprocessing
scikit-learn → Random Forest classifier, evaluation metrics
matplotlib, seaborn → Visualization (confusion matrix, ROC curve, feature importance)
joblib → Model persistence

🚀 Features
Data loading & preprocessing (train/test split)
Random Forest model training
Model evaluation using:
Accuracy, Precision, Recall, F1-score
Confusion Matrix
ROC-AUC Curve
Top-15 Feature Importance ranking
Model + predictions saved for reuse

📈 Results
Accuracy: ~90%
ROC-AUC: ~0.98
Strong generalization on test set


👉 This project demonstrates the use of machine learning for intrusion detection and can be extended with deep learning or ensemble models for further research.
