🛡️ Credit Card Fraud Detection with Random Forest
This project demonstrates how to build a Credit Card Fraud Detection model using machine learning, specifically a Random Forest Classifier. The dataset used is a 2023 version of anonymized transaction data, containing 31 features (V1–V28, amount, ID, class) where the target variable indicates whether a transaction is fraudulent.

🔧 Key Steps:
Data Cleaning & Preprocessing: Checked for missing values, handled feature scaling, and dropped irrelevant columns (e.g., transaction ID).

Data Splitting: Divided the dataset into training and test sets (80/20 split) for model training and evaluation.

Model Building: Trained a RandomForestClassifier with hyperparameters (n_estimators=100, max_depth=10, etc.).

Cross Validation: Used 5-fold cross-validation with F1 scoring to ensure robust model evaluation.

Evaluation Metrics: Assessed model performance using:

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC Curve & AUC Score (achieving AUC = 1 due to balanced dataset)

Visualization:

Feature importance ranking via bar plots

Correlation heatmaps

ROC curve visualization

⚠️ Note: The dataset used here is highly balanced (roughly 50/50 fraud vs. non-fraud), which is rare in real-world scenarios and contributes to the model’s near-perfect performance.

📁 Dataset Source:
Kaggle - Credit Card Fraud Detection Dataset 2023: https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023/data

🧠 Skills Practiced:
Data preprocessing and feature engineering

Model training and cross-validation

Evaluation with classification metrics

Visualization with Seaborn and Matplotlib
![Image](https://github.com/user-attachments/assets/925924b7-43c1-4388-b5fe-6dfc4b8521f6)
![Image](https://github.com/user-attachments/assets/4734c9eb-1a0f-4d44-8d26-51f1a93aaa41)
![Image](https://github.com/user-attachments/assets/425c2d90-f634-4d2b-9cc9-078723cb881d)
![Image](https://github.com/user-attachments/assets/eb5a60f7-f12c-4f14-8729-62f571632e29)
![Image](https://github.com/user-attachments/assets/655276a8-37c5-42d8-966f-75aeace9c47f)
![Image](https://github.com/user-attachments/assets/f37dd9ba-f91d-4357-89f6-a0010f5de278)
