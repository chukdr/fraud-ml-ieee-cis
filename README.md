# fraud-ml-ieee-cis
Transaction fraud detection using machine learning (IEEE-CIS dataset)

Baseline Fraud Detection Model (IEEE-CIS Dataset)

This project demonstrates an end-to-end fraud detection pipeline:
	•	Time-based validation split
	•	Behavioral feature engineering (transaction velocity, amount dynamics)
	•	Entity features (card, device, email)
	•	LightGBM baseline model

Results (Validation):
	•	ROC-AUC: 0.91
	•	Best F1-score: 0.55
	•	Precision: 0.65
	•	Recall: 0.47

Key insight: behavioral velocity features significantly improve fraud detection beyond raw transactional attributes.