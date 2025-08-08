Credit Risk Modeling – PD, Expected Loss & Monitoring

Project Summary

This project demonstrates an end-to-end credit risk modeling workflow using Lending Club loan data.
It covers the complete process from data preparation to model development, risk metric computation, and monitoring.
The goal is to estimate the Probability of Default (PD), calculate Expected Loss (EL), and implement monitoring practices that align with credit risk management in financial institutions.
By combining data science techniques with domain-specific risk measures, this project provides a practical approach to understanding and managing loan portfolio risk.

Project Structure
	1.	Data Preparation.ipynb
	•	Loads, cleans, and preprocesses the Lending Club dataset.
	•	Handles missing values, encodes categorical variables, and scales numerical features.
	•	Ensures the dataset is ready for robust model training and validation.
	2.	PD Model.ipynb
	•	Develops a Probability of Default classification model using statistical and machine learning techniques.
	•	Includes feature selection, model training, evaluation metrics (AUC, KS, confusion matrix).
	•	Provides interpretability through feature importance in a business context.
	3.	Calculating Expected Loss.ipynb
	•	Computes Expected Loss = PD × LGD × EAD.
	•	Integrates model predictions with Loss Given Default (LGD) and Exposure at Default (EAD) assumptions.
	•	Includes scenario analysis to evaluate portfolio-level credit risk.
	4.	Monitoring.ipynb
	•	Implements model monitoring to track PD performance over time.
	•	Detects data drift and model degradation using stability metrics (e.g., PSI).
	•	Supports governance requirements and identifies retraining needs.

Key Highlights
	•	End-to-End Risk Pipeline: From raw Lending Club data to actionable risk insights.
	•	Business-Oriented Modeling: Aligns statistical predictions with financial risk management practices.
	•	Governance Ready: Includes monitoring for stability and compliance.
	•	Adaptable: Approach can be scaled for large datasets in real-world banking environments.

Tech Stack
	•	Languages: Python (Pandas, NumPy, Scikit-learn)
	•	Modeling: Logistic Regression, Classification Models
	•	Visualization: Matplotlib, Seaborn
	•	Risk Metrics: PD, LGD, EAD, Expected Loss
	•	Monitoring: PSI, KS, Stability Tracking

Business Impact

This framework enables:
	•	Reliable default prediction for loan portfolios.
	•	Proactive risk mitigation through Expected Loss estimation.
	•	Continuous model performance oversight to ensure accuracy and compliance over time.
