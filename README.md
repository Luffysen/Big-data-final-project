Bank Marketing Campaign Analysis

This project analyzes a Portuguese bank’s direct marketing campaign aimed at promoting term deposit subscriptions via phone calls. The dataset includes detailed customer demographics, contact information, and campaign outcomes, with a binary target variable indicating whether a client subscribed to a term deposit.

   Dataset Overview
	•	Source: Portuguese banking institution
	•	Target Variable: y (term deposit subscription: yes/no)
	•	Features: Client age, job, marital status, education, contact type, call duration, balance, etc.

   Project Objectives
	•	Identify key factors influencing subscription decisions
	•	Segment customer profiles based on response behavior
	•	Evaluate machine learning models for better targeting
	•	Recommend actionable strategies to optimize marketing performance

   Key Findings
	•	Severe class imbalance: Only 11.7% of clients subscribed

   Top predictive features:
	•	Call duration (strongest predictor)
	•	Account balance
	•	Client’s age
	•	High-conversion segments: Students, retired clients, and those with prior successful campaigns
	•	Preferred contact method: Cellular over landline
	•	Best campaign periods: May and other high-performing months


   Model Performance

Metric	Random Forest	Logistic Regression
Accuracy	91.1%	89.1%
Precision	65.6%	59.5%
Recall	42.1%	22.6%
F1-Score	51.3%	32.7%

	•	Random Forest outperforms Logistic Regression
	•	Recall and F1-score remain low due to class imbalance
<img width="1920" height="1011" alt="Screenshot 2025-08-03 132113" src="https://github.com/user-attachments/assets/ac32c6b0-230d-4932-8fdb-de69c7847e53" />
<img width="1453" height="584" alt="Confusion Matrix Visualization" src="https://github.com/user-attachments/assets/28803b30-2e18-40fd-b2a4-dda848c8b39b" />
<img width="875" height="784" alt="Correlation Analysis" src="https://github.com/user-attachments/assets/1af42373-f8ac-42b1-870a-d005e82b7688" />
<img width="1984" height="1483" alt="Exploratory Data Analysis - Categorical Variables" src="https://github.com/user-attachments/assets/bbb578e6-e1a6-4095-9f5a-4ebff5dfd2fe" />
<img width="1984" height="1483" alt="Exploratory Data Analysis - Categorical Variables" src="https://github.com/user-attachments/assets/1e472ff0-f805-49d8-a63d-c4fc1ef26e12" />
<img width="1184" height="784" alt="Feature Importance Analysis" src="https://github.com/user-attachments/assets/8071b800-1585-4e4a-ab48-aa352cfd10d6" />
<img width="1984" height="1483" alt="Target Variable Analysis" src="https://github.com/user-attachments/assets/25b6d5be-3a5e-459e-94d8-782e80f1d0ad" />
<img width="1450" height="584" alt="the distribution of the target variable" src="https://github.com/user-attachments/assets/7cf49096-5543-49c6-8667-7bb375ef66c8" />






