#  Customer Churn Prediction Using KNIME

##  Overview
This project demonstrates how to use the **KNIME Analytics Platform** to analyze and predict customer churn. It includes data preprocessing, machine learning, model evaluation, and visualization, all within a KNIME workflow.

---

##  Objectives
- Perform dataset load, data cleaning, and feature engineering
- Identify churn indicators from customer data with visualization techniques
- Build and evaluate ML models (Logistic Regression, Decision Tree, Random Forest, XGBoost)
- Deliver insights and recommendations to reduce customer churn


##  Tools & Technologies
- **KNIME Analytics Platform**
- **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest, XGBoost
- **Visualization Tools:** KNIME native chart nodes, ROC Curves
- **Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)


## 🔄 Workflow Summary
###  Step 1: Data Import & Exploration
- Import Telco data as CSV
- Explore data distribution, identify missing values

###  Step 2: Data Preprocessing
- Handle missing values and outliers
- Normalize numerical attributes (mean value)
- Encode categorical variables (One-Hot Encoding or most frequent value)

###  Step 3: Feature Engineering
- Use correlation filters
- Calculate feature importance, chart visualization (Bar, Histogram, Pie, Line, ScatterPlot) 

###  Step 4: Model Building
- Train/test split
- Build and compare Logistic Regression, Random Forest, and XGBoost models
- Apply cross-validation for tuning

###  Step 5: Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix and ROC Curve visualization

## 📈 Key Results
- **Top features:** Contract Type, Tenure, Monthly Charges
- **Best Model:** XGBoost with ~84% accuracy and 0.88 AUC

---

## 📥 How to Run
1. Download and install [KNIME Analytics Platform](https://www.knime.com/downloads)
2. Open the `.knwf` file in KNIME
3. Load csv dataset
4. Execute each node in order


## 📚 References
- Dataset: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- KNIME Docs: [https://docs.knime.com](https://docs.knime.com)


## 👩‍💻 Author
Anamika Das,
MSc in Information Technology & Management  
The University of Texas at Dallas  


