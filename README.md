
# 💳 Credit Rating 

![credit-score-gauge-concept-vector-illustration_185038-667](https://github.com/user-attachments/assets/3631fe5d-0407-4148-bca4-4314a00f5707)


Tools Used 🛠: Python, Pandas, Scikit-learn, SMOTE, XGBoost, Seaborn, Matplotlib, StatsModels

## 🎯 Objective
The goal is to classify customers into Good or Bad credit risk categories using machine learning models trained on the German Credit dataset. This is a classic real-world problem often encountered by financial institutions during loan approvals and credit assessments.

## 💡 Why We Use It
-Credit risk classification helps banks and financial institutions:
-Evaluate loan applications more accurately
-Minimize default risk and improve credit decisions
-Optimize credit limits and interest rate offerings
-Enhance personalized financial product recommendations

## ✅ Step-by-Step Approach

### 📥 Data Preprocessing
-Loaded the German Credit dataset from UCI Repository
-Identified categorical and numerical columns
-Dropped unimportant or redundant features
-Encoded categorical variables using One-Hot Encoding

### 🔍 Exploratory Data Analysis (EDA)
-Analyzed credit status distributions
-Used box plots and histograms to assess variable importance
-Identified patterns like:
-Higher loan duration/amount → higher default risk
-Older age and lower installment rate → better credit rating
-Detected outliers and imbalance in the dataset

### 🧠 Feature Engineering & Scaling
-Selected significant features using logistic regression summary
-Applied Min-Max Scaling on continuous variables
-Used Youden's Index to determine the optimal probability threshold

### ⚖️ Dealing with Imbalanced Data
-Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the class distribution and improve model generalization

### 📊 Model Training & Evaluation
-Built multiple machine learning models:

#### ✅ Logistic Regression (baseline, AUC = 0.75)
#### ✅ Decision Tree
#### ✅ k-NN
#### ✅ SVM
#### ✅ Naive Bayes
#### ✅ Gradient Boosting
#### ✅ XGBoost
#### ✅ Random Forest (Best performer - Accuracy: 84%)

### Evaluated all models using:
-Confusion matrix
-ROC-AUC curve
-Precision, Recall, F1-score

### 🔚 Conclusion
-Feature selection and SMOTE significantly improved model performance
-Random Forest Classifier gave the best results
-Logistic Regression had limitations with imbalanced data
-XGBoost underperformed possibly due to lack of hyperparameter tuning
Overall, a successful end-to-end ML pipeline for credit classification

# Output
<img width="924" height="401" alt="Screenshot 2025-08-06 150617" src="https://github.com/user-attachments/assets/a6c640ee-a246-4fe2-9bff-644488b2dfbe" />
