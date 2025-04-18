SULTANUL ARIFIN EMON
ID: 222-112-007
________________________________________
❤️ Heart Disease Prediction Using Logistic Regression
📌 Overview
Heart disease is one of the leading causes of death globally. Early prediction can help in timely diagnosis and treatment. This project uses Logistic Regression, a statistical method for binary classification, to predict the presence of heart disease based on clinical parameters.
________________________________________
🧠 Objective
To develop a machine learning model using logistic regression to predict whether a person has heart disease based on a set of features.
________________________________________
📁 Dataset
Source: UCI Machine Learning Repository – Heart Disease Dataset
Features Used:
•	age: Age of the patient
•	sex: Gender (1 = male; 0 = female)
•	cp: Chest pain type (0–3)
•	trestbps: Resting blood pressure
•	chol: Serum cholesterol (mg/dl)
•	fbs: Fasting blood sugar (>120 mg/dl, 1 = true; 0 = false)
•	restecg: Resting ECG results (0–2)
•	thalach: Maximum heart rate achieved
•	exang: Exercise-induced angina (1 = yes; 0 = no)
•	oldpeak: ST depression induced by exercise
•	slope: Slope of the peak exercise ST segment
•	ca: Number of major vessels (0–3)
•	thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
•	target: Presence of heart disease (1 = yes; 0 = no)
________________________________________
🔧 Tools & Libraries
•	Python
•	Pandas
•	NumPy
•	Matplotlib / Seaborn (for visualization)
•	Scikit-learn (for model building and evaluation)
________________________________________
🔍 Data Preprocessing
•	Handling missing values
•	Encoding categorical variables
•	Feature scaling
•	Train-test split (e.g., 80/20)
________________________________________
🧪 Model: Logistic Regression
•	Logistic Regression is used because this is a binary classification problem.
•	It's simple, interpretable, and effective for linearly separable data.
________________________________________
✅ Evaluation Metrics
•	Accuracy
•	Confusion Matrix
•	Precision, Recall, F1 Score
•	ROC Curve & AUC Score
________________________________________
📈 Results
Metric	Score
Accuracy	~85%
Precision	~0.87
Recall	~0.83
F1-Score	~0.85
AUC-ROC	~0.88
Note: These are illustrative and will vary based on preprocessing and train-test split.
________________________________________
📊 Visualization
•	Correlation heatmap to understand feature relationships
•	ROC Curve to visualize performance
•	Confusion Matrix to see prediction breakdown
________________________________________
🧩 Conclusion
•	Logistic Regression provides a solid baseline model.
•	Key influencing factors include age, cp, thalach, and oldpeak.
•	Further performance improvements can be achieved using ensemble methods or deep learning.
________________________________________
🚀 Future Work
•	Try more advanced models (Random Forest, XGBoost)
•	Hyperparameter tuning
•	Model deployment using Flask/Django
•	Use of real-time patient data via IoT devices or EHR systems
________________________________________
📎 References
•	UCI ML Repository
•	Scikit-learn documentation
•	WHO – Heart Disease Facts
