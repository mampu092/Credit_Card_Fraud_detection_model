Credit Card Fraud Detection System

Overview

This project implements a Credit Card Fraud Detection System using Machine Learning with a two-layer data filtering architecture. The goal of the system is to efficiently detect fraudulent transactions by first filtering suspicious data and then performing deeper analysis using machine learning models.

The system improves fraud detection accuracy while reducing computational cost by eliminating obviously legitimate transactions in the first stage.

⸻

Key Features
	•	Two-layer fraud detection architecture
	•	Machine learning-based fraud classification
	•	Efficient preprocessing and feature engineering
	•	Reduced false positives
	•	Scalable fraud detection pipeline

⸻

System Architecture

Layer 1: Data Filtering Layer

The first layer performs basic rule-based filtering to quickly eliminate transactions that are highly likely to be legitimate.

This layer includes:
	•	Transaction threshold filtering
	•	Basic statistical checks
	•	Rule-based anomaly detection

The goal is to reduce the volume of data that needs deep analysis.

Layer 2: Machine Learning Detection Layer

Transactions flagged by the first layer are passed to the machine learning model for deeper analysis.

This layer includes:
	•	Feature extraction
	•	Model prediction
	•	Fraud probability scoring

Possible models used:
	•	Logistic Regression
	•	Random Forest
	•	Neural Networks

The model predicts whether a transaction is fraudulent or legitimate.

⸻

Workflow
	1.	Load transaction dataset
	2.	Perform data preprocessing
	3.	Apply Layer 1 filtering
	4.	Pass suspicious transactions to Layer 2 ML model
	5.	Predict fraud probability
	6.	Output classification results

⸻

Technologies Used
	•	Python
	•	Machine Learning
	•	Scikit-learn
	•	Pandas
	•	NumPy
	•	Matplotlib / Seaborn (for visualization)

⸻

Dataset

The model can be trained using publicly available datasets such as the European Cardholders Credit Card Fraud Dataset.

Typical dataset features include:
	•	Transaction time
	•	Transaction amount
	•	PCA transformed features
	•	Fraud label
