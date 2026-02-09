# Breast Cancer Classification with KNN and Decision Trees

### Objective
Predict whether a breast tumor is malignant or benign using supervised machine learning. I built a machine learning project to predict whether a breast tumor is benign or malignant using real medical data. First, I loaded and explored the dataset, checked features and handled inputs and labels. Then I trained two supervised ML models: a Decision Tree and K-Nearest Neighbors (KNN). I split the data into training and testing sets and evaluated both models using accuracy, precision, recall, F1-score, and confusion matrices. KNN performed better after scaling the data, while the Decision Tree was easier to understand. This project shows how different models trade off performance vs explainability in real ML workflows.

### Dataset
Breast Cancer Wisconsin (Diagnostic) Dataset from Kaggle.

### Models Used
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Key Findings
- KNN achieved higher accuracy after feature scaling.
- Decision Tree provided interpretability with slightly lower performance.
- Demonstrates the tradeoff between explainability and predictive power.

### Tools
Python, pandas, scikit-learn, matplotlib, seaborn
