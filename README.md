# AI-model-for-two-level-diagnosis-of-heart-diseases
🫀 Heart Disease Detection Model
This project presents a Machine Learning-based Heart Disease Detection System that predicts the likelihood of a person having heart disease based on key clinical features. The model is trained and evaluated on a well-known heart disease dataset, and aims to support early diagnosis, improve decision-making, and ultimately contribute to better patient outcomes.

📌 Objective
The main objective of this project is to develop a predictive model that can accurately detect the presence of heart disease using machine learning algorithms. This tool can be useful for medical professionals and researchers to assist in preliminary diagnoses and risk assessment.

🧠 Machine Learning Models Used
Multiple classification models were explored and evaluated to determine the best-performing algorithm:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Decision Tree

XGBoost (optional if included)

After comparing performance metrics such as accuracy, precision, recall, and F1-score, the best model was selected for deployment.

📊 Dataset
The dataset used is the Cleveland Heart Disease dataset, which is publicly available via the UCI Machine Learning Repository. It includes 14 key medical attributes:

age: Age of the patient

sex: Gender (1 = male, 0 = female)

cp: Chest pain type (0 to 3)

trestbps: Resting blood pressure

chol: Serum cholesterol in mg/dl

fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)

restecg: Resting electrocardiographic results (0 to 2)

thalach: Maximum heart rate achieved

exang: Exercise induced angina (1 = yes; 0 = no)

oldpeak: ST depression induced by exercise

slope: Slope of the peak exercise ST segment

ca: Number of major vessels (0–3) colored by fluoroscopy

thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)

target: Diagnosis of heart disease (1 = disease present; 0 = no disease)

⚙️ Workflow
Data Preprocessing

Handling missing values

Feature encoding and scaling

Correlation analysis and feature selection

Model Training

Data split into training and testing sets

Hyperparameter tuning using GridSearchCV (optional)

Training multiple models and evaluating their performance

Model Evaluation

Accuracy, precision, recall, F1-score

Confusion matrix

ROC-AUC curve

Deployment (optional)

If deployed, a simple Streamlit or Flask-based web app is used for user interaction

🚀 Features
High accuracy in prediction with minimal input

User-friendly model ready for integration

Modular code for easy experimentation and extension

Optional web interface for demo purposes

🛠️ Technologies Used
Python

Scikit-learn

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook / Google Colab

Streamlit or Flask (if deployed as a web app)

📈 Results
The final selected model achieved:

Accuracy: ~XX%

Precision: ~XX%

Recall: ~XX%

F1-Score: ~XX%

(📌 Replace XX% with your actual results)
