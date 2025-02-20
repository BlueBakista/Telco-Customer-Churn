# Machine Learning Assignment

## Overview
This project focuses on analyzing customer churn data using various machine learning techniques, including classification, regression, and clustering. The dataset used for this analysis is the **Telco Customer Churn** dataset from Kaggle.

## Dataset
Each row in the dataset represents a customer, with columns containing attributes such as:
- **Demographic information** (e.g., gender, senior citizen status, partner, dependents)
- **Subscription details** (e.g., internet service type, contract type, payment method)
- **Usage and service features** (e.g., online security, streaming TV, multiple lines)
- **Churn status** (whether the customer has left the service)

### Data Preprocessing
- Handling missing values (e.g., converting `TotalCharges` to numeric and dropping NaNs)
- Encoding categorical variables using label encoding
- Splitting the dataset into training and test sets

## Exploratory Data Analysis (EDA)
EDA was performed to identify key patterns and trends, including:
- Churn rates based on demographics
- Impact of contract type and payment method on customer churn
- Correlation analysis among features using a heatmap

## Machine Learning Models
The following models were implemented:

### **Classification** (Predicting Churn)
- **Logistic Regression**
- **Naive Bayes**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM) - Linear & Kernel**
- **Decision Trees**
- **Neural Networks**

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1 Score

### **Regression** (Predicting Total Charges)
- **Linear Regression**
- **Random Forest Regressor**
- **Extra Trees Regressor**
- **AdaBoost Regressor**
- **XGBoost Regressor**
- **NGBoost Regressor**

**Evaluation Metrics:**
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

### **Clustering** (Customer Segmentation)
- **K-Means Clustering**
- **Gaussian Mixture Model (GMM)**
- **K-Medoids Clustering**

**Evaluation Metrics:**
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index

## Results & Insights
- Customers with **month-to-month contracts** have the highest churn rate.
- Customers using **electronic check payments** are more likely to churn.
- **Senior citizens and customers without tech support** have a higher likelihood of leaving.
- Customers with **fiber optic internet** experience the highest churn.

## Dependencies
The following Python libraries were used:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost ngboost scikit-learn-extra kagglehub
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python analysis.py
   ```

## Contributors
- Prasoon Narayan Singh
- 

## License
This project is licensed under the MIT License.

