# F1-Dataset-PitNextLap-Predicton-Random-Forest-Classifier

Project Objective:
To predict whether a Formula 1 driver will make a pit stop on the next lap based on race conditions and contextual race features such as lap number, tire information, and race state.

Approach:
Data preprocessing and cleaning
Feature engineering for race context
One-hot encoding of categorical variables
Train-test split for model evaluation
Initial Logistic Regression baseline experimentation
Random Forest classification model
Cross-validation for model consistency
Performance evaluation using classification metrics

Key Findings:
Logistic Regression showed signs of underfitting and struggled with pit-stop event recall due to dataset complexity and class imbalance.
Random Forest significantly improved prediction performance by capturing nonlinear relationships within the data.
Evaluation metrics such as precision, recall, F1-score, and confusion matrix analysis were critical in comparing model effectiveness.

Techniques & Tools Used:
Python
Pandas & NumPy
Scikit-learn
Random Forest Classifier
Logistic Regression (baseline experimentation)
One-Hot Encoding
Cross Validation
Accuracy, Precision, Recall, F1-score
Confusion Matrix Visualization
