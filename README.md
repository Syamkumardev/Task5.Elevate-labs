# Task5.Elevate-labs

#  Logistic Regression – Binary Classification

##  Task Overview
This project is part of the AI & ML Internship (Task 4).  
The objective is to implement logistic regression on a binary classification problem using the Breast Cancer Wisconsin dataset.


  Steps Taken
1. Loaded Breast Cancer dataset using sklearn
2. Standardized features using StandardScaler
3. Split data into training and test sets (80-20)
4. Trained Logistic Regression model using sklearn
5. Evaluated with:
   - Confusion Matrix
   - Precision and Recall
   - ROC-AUC Score
6. Plotted ROC curve and interpreted results


#  Model Evaluation

- ROC-AUC Score: check output
- Confusion Matrix:
  - True Positives, False Positives, etc.
- Precision and Recall calculated




##  Interview Question Answers

1. How does logistic regression differ from linear regression?  
   Logistic regression predicts probabilities and uses sigmoid activation for binary classification, while linear regression predicts continuous values.

2. What is the sigmoid function?  
   A function that maps any real-valued number to a value between 0 and 1, used to interpret outputs as probabilities.

3. What is precision vs recall?  
   Precision = TP / (TP + FP) — how many predicted positives are true.  
   Recall = TP / (TP + FN) — how many actual positives are correctly predicted.

4. What is the ROC-AUC curve?  
   ROC curve plots TPR vs FPR; AUC measures model's ability to distinguish classes.

5. What is the confusion matrix?  
   A 2x2 matrix showing true vs predicted values: TP, TN, FP, FN.

6. What happens if classes are imbalanced?  
   The model might become biased toward the majority class. Use techniques like SMOTE or adjust class weights.

7. How do you choose the threshold?  
   Based on trade-off between precision and recall, often using ROC or Precision-Recall curve.

8. Can logistic regression be used for multi-class problems?  
   Yes, using one-vs-rest or softmax (multinomial) approaches.


#  Tools & Libraries

- Python
- scikit-learn
- pandas, matplotlib, seaborn



##  Files Included

- logistic_regression.ipynb — Full code
- README.md — Summary and interview answers


