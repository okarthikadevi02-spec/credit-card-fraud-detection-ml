# Credit Card Fraud Detection using Machine Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
Credit card fraud is a serious problem where fraudulent transactions are very rare compared to normal transactions.  
The goal of this project is to build a model that can accurately identify fraud cases.

---

## Dataset Information
The dataset contains 284,807 transactions with 31 features.

- Features V1 to V28 are anonymized (PCA transformed)
- Time: Time elapsed between transactions
- Amount: Transaction amount
- Class: Target variable (0 = Normal, 1 = Fraud)

The dataset is highly imbalanced, with very few fraud cases.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Data Loading  
2. Data Understanding  
3. Data Preprocessing  
4. Feature Scaling  
5. Train-Test Split  
6. Model Building  
7. Model Evaluation  

---

## Data Preprocessing

- Scaled `Amount` and `Time` features using StandardScaler  
- Checked class imbalance  
- Split dataset using stratified sampling  

---

## Machine Learning Models

- Logistic Regression  
- Random Forest Classifier  

---

## Model Evaluation

Evaluation metrics used:
- Accuracy Score  
- Classification Report  
- Confusion Matrix  
- Precision-Recall Curve  

---

## Key Insights

- Dataset is highly imbalanced  
- Fraud transactions are very rare  
- Random Forest performs better than Logistic Regression  
- Precision and Recall are more important than Accuracy  

---

## Conclusion

The model successfully identifies fraudulent transactions using machine learning techniques.  
This project highlights the importance of handling imbalanced datasets in real-world problems.

---

## Future Improvements

- Use advanced models such as XGBoost  
- Apply SMOTE for better balancing  
- Perform hyperparameter tuning  
- Deploy the model  

---

## Project Structure

credit-card-fraud-detection-ml/
│
├── fraud_detection.ipynb  
├── creditcard.csv  
├── README.md  

---

## Author

Karthikadevi O  
Aspiring Data Scientist  

---

## Note

This project is for educational purposes and demonstrates machine learning concepts on real-world data.
