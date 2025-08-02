# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Implemented using Python in Jupyter Notebook (Anaconda environment), the goal is to build models that accurately distinguish between legitimate and fraudulent transactions using a dataset of real-world anonymized transactions.

## 🔍 Problem Statement

Credit card fraud is a major issue in financial sectors. The objective of this project is to develop a reliable and efficient fraud detection system using classification models that can predict whether a transaction is fraudulent based on various features.

## 🧰 Tools & Technologies Used

- **Platform**: Jupyter Notebook (via Anaconda)
- **Language**: Python
- **Libraries**:
  - `pandas` – for data manipulation
  - `NumPy` – for numerical operations
  - `matplotlib`, `seaborn` – for data visualization
  - `scikit-learn` – for model building and evaluation
  - `imbalanced-learn` – for handling imbalanced data

## 📁 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Details**: The dataset contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, out of which 492 are fraudulent. All features except 'Time' and 'Amount' have been anonymized (V1, V2, ..., V28).

## 📊 Project Workflow

1. **Data Loading & Exploration**
   - Checked dataset shape, types, and missing values
   - Explored class imbalance and performed basic EDA

2. **Data Preprocessing**
   - Standardized the 'Amount' and 'Time' features
   - Handled class imbalance using SMOTE

3. **Model Building**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - XGBoost Classifier

4. **Model Evaluation**
   - Used metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC
   - Plotted confusion matrices and ROC curves

## 📈 Results

- Evaluated all models and compared their performance on imbalanced data
- XGBoost and Random Forest showed the best performance in terms of precision and recall

## 📌 Key Learnings

- Importance of handling imbalanced datasets in fraud detection
- Trade-offs between precision and recall in sensitive applications
- Feature scaling and SMOTE significantly improve model performance

## 🚀 Future Work

- Hyperparameter tuning for model optimization
- Integrate with real-time transaction data streams
- Deploy model via a web dashboard or API for real-world use

## 📎 How to Run

1. Clone the repository:
git clone https://github.com/aniverma-40/Credit-Card-fraud-detection.git

2. Navigate to the folder:
cd Credit-Card-fraud-detection

3. Open the Jupyter Notebook using Anaconda or Jupyter:
jupyter notebook


4. Run each cell sequentially in the notebook to execute the project.

---

Feel free to fork, improve, and give this repo a ⭐ if you find it helpful!
