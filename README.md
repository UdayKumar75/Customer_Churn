# 📊 Customer Churn Prediction using Machine Learning

This project predicts customer churn in a telecom company using machine learning techniques. The goal is to identify customers likely to leave the service so the business can take proactive action to retain them.

---

## 🔍 Problem Statement

Customer churn is a key concern for subscription-based businesses. By analyzing customer behavior and contract details, we can predict which customers are at risk of leaving and help reduce churn.

---

## 📁 Dataset

- **Source**: IBM Sample Dataset  
- **File**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Target Variable**: `Churn` (Yes/No)

### Key Features:
- Customer demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- Service details: `PhoneService`, `InternetService`, `StreamingTV`, etc.
- Account info: `tenure`, `MonthlyCharges`, `TotalCharges`
- Contract info: `Contract`, `PaperlessBilling`, `PaymentMethod`

---

## ⚙️ Technologies Used

- **Python 3**
- **Pandas** & **NumPy** – Data preprocessing
- **Matplotlib** & **Seaborn** – Visualizations
- **Scikit-learn** – Machine learning
- **Jupyter Notebook** – Development environment

---

## 🧪 Workflow

1. Load and clean the dataset
2. Handle missing values and convert data types
3. Encode categorical features
4. Split the dataset into training and testing sets
5. Train a Random Forest Classifier
6. Evaluate the model (accuracy, confusion matrix, classification report)
7. Visualize key insights (feature importance, churn distribution, etc.)

---

## 📈 Results

- Random Forest achieved strong performance in predicting churn
- Important features include: `MonthlyCharges`, `Contract`, `tenure`, `TotalCharges`
- Visualizations used:
  - Churn distribution pie chart
  - Feature importance bar chart
  - Monthly Charges vs Churn boxplot
  - Confusion matrix heatmap

---

## ▶️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
