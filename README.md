# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a customer is likely to **leave (churn)** or **stay** with a telecom company using Machine Learning. The dataset is cleaned, preprocessed, analyzed, and then used to train an **XGBoost Classifier** for customer churn prediction.

The project follows a complete Data Science workflow from data preprocessing to model evaluation.

---

## 🎯 Objectives

* Analyze customer data
* Handle missing values
* Detect and analyze outliers
* Encode categorical variables
* Scale numerical features
* Train a Machine Learning model
* Predict customer churn
* Evaluate model performance

---

## 📂 Dataset

The dataset contains telecom customer information such as:

* State
* Account Length
* Area Code
* International Plan
* Voice Mail Plan
* Number of Voice Mail Messages
* Total Day Calls
* Total Day Minutes
* Total Evening Calls
* Total Night Calls
* Total International Calls
* Charges
* Customer Service Calls
* Churn (Target Variable)

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## 📈 Project Workflow

### 1. Import Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn

---

### 2. Load Dataset

* Read CSV file
* Display dataset information
* Check shape
* Preview records

---

### 3. Exploratory Data Analysis (EDA)

* Dataset information
* Data types
* Summary statistics
* Missing value analysis
* Feature inspection

---

### 4. Data Cleaning

* Handle missing values
* Fill missing values using:

  * Mean
  * Median
* Save cleaned dataset

---

### 5. Outlier Detection

Used the **Interquartile Range (IQR)** method to identify outliers in numerical columns.

---

### 6. Data Preprocessing

* Label Encoding for categorical variables
* Remove unnecessary columns (Phone Number)
* Feature Scaling using StandardScaler

---

### 7. Feature Selection

Separate the dataset into:

* **Features (X)**
* **Target (Y)**

---

### 8. Train-Test Split

Split the dataset into training and testing sets using Scikit-learn.

---

### 9. Model Building

Model Used:

* **XGBoost Classifier**

The model is trained using the training dataset.

---

### 10. Prediction

Predict customer churn on unseen test data.

---

### 11. Model Evaluation

Evaluation metrics include:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📊 Machine Learning Algorithm

**XGBoost Classifier**

XGBoost is an optimized gradient boosting algorithm known for:

* High accuracy
* Fast training
* Handling missing values
* Excellent performance on structured/tabular data

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── datascience.ipynb
├── Churn_dataset.csv
├── new_data.csv
├── phones_calls.csv
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Open

```
datascience.ipynb
```

5. Run all cells.

---

## 📌 Results

The model successfully predicts customer churn after:

* Data Cleaning
* Feature Engineering
* Data Scaling
* Model Training

Performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature importance visualization
* Compare multiple ML algorithms
* Deploy using Flask or Streamlit
* Build an interactive dashboard

---

## 📚 Learning Outcomes

This project demonstrates:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Missing value handling
* Outlier detection
* Feature encoding
* Feature scaling
* Machine Learning model training
* Customer churn prediction
* Model evaluation

---

## 👨‍💻 Author

**Manikandan**

Aspiring Data Analyst | Machine Learning Enthusiast

---

## ⭐ If you like this project

Please consider giving the repository a **Star ⭐** and sharing your feedback!
