# Cardiovascular Disease Prediction

This repository contains a project focused on predicting **Cardiovascular Disease (CVD)** using machine learning models. The project includes data preprocessing, feature engineering, model training, and evaluation.

## 📂 Files in this Repository
- **CVD-Prediction.ipynb** - Jupyter Notebook containing the implementation of the machine learning pipeline for cardiovascular disease prediction.
- **README.md** - Documentation describing the project, methodology, and usage instructions.

## 📌 Project Overview
Cardiovascular disease is one of the leading causes of mortality worldwide. This project aims to develop a predictive model using historical patient data to classify whether an individual is likely to have CVD.

### **📊 Dataset**
The dataset used includes patient health metrics such as:
- Age, gender, cholesterol levels, blood pressure, etc.
- Lifestyle factors like smoking, alcohol intake, and physical activity.

### **🛠 Methodology**
1. **Data Preprocessing**: Handling missing values, feature scaling, encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Visualizing trends and patterns in cardiovascular risk factors.
3. **Feature Engineering**: Creating new relevant features to improve model performance.
4. **Model Training & Evaluation**:
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - Gradient Boosting (XGBoost, LightGBM)
   - Neural Networks
5. **Hyperparameter Tuning**: Optimizing model performance using Grid Search and Random Search.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CVD-Prediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the code:
   ```bash
   jupyter notebook CVD-Prediction.ipynb
   ```

## 📌 Key Findings
- Feature importance analysis showed **blood pressure, cholesterol, and smoking** as major predictors.
- **Random Forest and XGBoost** provided the best predictive accuracy.
- Model performance metrics: **Accuracy, Precision, Recall, and F1-score** were used for evaluation.

## 👨‍💻 Contributors
- Your Name

## 📜 License
This project is for educational purposes only. Not for medical or clinical use.

---
