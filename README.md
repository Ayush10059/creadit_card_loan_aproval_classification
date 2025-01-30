# **Credit Card Loan Approval Classification** 🏦💳  

## **Overview**  
This project aims to build a machine learning model to predict whether a customer will get their **credit card loan approved** based on various financial and demographic factors. The classification model helps financial institutions assess risk and streamline the approval process.  

## **Dataset**  
- **Source:** [Kaggle - Credit Card Approval Prediction](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction)  
- **Features:**  
  - Applicant income, employment status, credit score  
  - Loan amount, existing debts, past defaults  
  - Other financial and demographic attributes  
- **Target Variable:** Approval status (**Approved** / **Rejected**)  

## **Project Workflow**  
1. **Data Preprocessing**  
   - Handling missing values  
   - Feature engineering and encoding categorical variables  
   - Normalization and scaling  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of approved vs. rejected applications  
   - Correlation between features and approval status  
   - Visualization of key insights  

3. **Model Training & Evaluation**  
   - Logistic Regression, Decision Trees, Random Forest, and other classifiers  
   - Hyperparameter tuning using GridSearchCV  
   - Performance metrics: Accuracy, Precision, Recall, F1-score, AUC-ROC  

4. **Model Deployment (Future Scope)**  
   - Save the trained model using **Pickle/Joblib**  
   - Deploy as an API using **Flask/FastAPI**  

## **Dependencies**  
Ensure you have the necessary libraries installed before running the code:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## **Usage**  
Clone the repository and navigate to the project folder:  
```bash
git clone https://github.com/Ayush10059/creadit_card_loan_aproval_classification.git
cd creadit_card_loan_aproval_classification
```
Run the Jupyter Notebook or Python script:  
```bash
jupyter notebook
```

## **Results & Insights**  
- Identified key factors influencing loan approvals  
- Improved prediction accuracy with feature engineering and model tuning  
- Potential application for automating financial risk assessment  

## **Contributing**  
Feel free to fork the repo and submit a pull request if you want to improve or extend the analysis!  

## **License**  
This project is licensed under the **MIT License**.  
