# ❤️ Heart Disease Prediction using Data-Driven Insights  

This project predicts the likelihood of heart disease in patients based on clinical parameters using machine learning. By combining data analysis and predictive modeling, it helps identify individuals at risk — empowering early detection and preventive care.

---

## 📋 Overview  

Heart disease remains one of the leading causes of death globally. Detecting it early can save lives.  
This project uses **Python** and **machine learning** to analyze medical data and predict whether a patient is likely to have heart disease.

---

## 🎯 Objective  

> “Given a patient’s clinical data, can we accurately predict whether they are at risk of heart disease?”

---

## 📚 Dataset  

The dataset used is the **Heart Disease UCI Dataset**, containing real-world medical attributes such as:  
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Serum Cholesterol  
- Maximum Heart Rate Achieved  
- Exercise-Induced Angina  
- ST Depression  
- Slope, CA, Thal, etc.  

📂 File: `heart-disease.csv`

---

## 🧩 Project Workflow  

1. **Problem Definition** – Identify the objective and evaluation metrics.  
2. **Data Collection & Cleaning** – Load the dataset and prepare it for analysis.  
3. **Exploratory Data Analysis (EDA)** – Visualize distributions, correlations, and class balance.  
4. **Model Building** – Train multiple ML algorithms:  
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Random Forest Classifier  
5. **Model Evaluation** – Use metrics like Accuracy, F1-score, Precision, Recall, and ROC-AUC.  
6. **Comparison & Interpretation** – Analyze which model performs best and why.

---

## ⚙️ Tech Stack  

- **Python 3.x**  
- **pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn** – Visualization  
- **scikit-learn** – Model building and evaluation  
- **Jupyter Notebook** – Development environment  

---

## 🧠 Results  

After experimentation, the **Random Forest Classifier** outperformed other models, offering high accuracy and recall — crucial for reducing false negatives in medical prediction.  

| Model | Accuracy | F1 Score | Recall |
|--------|-----------|----------|---------|
| Logistic Regression | ~84% | ~0.83 | ~0.82 |
| KNN | ~78% | ~0.77 | ~0.76 |
| Random Forest | **~88%** | **~0.87** | **~0.89** |

*(Results may vary slightly depending on random seed and tuning.)*

---

## 📊 Visualizations  

- Correlation Heatmap of Features  
- Distribution of Heart Disease Cases  
- ROC Curve Comparison  

---

## 🚀 How to Run  

```bash
# Clone this repository
git clone https://github.com/amritauji/heart-disease-classification.git

# Navigate into the folder
cd heart-disease-classification

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook heart_disease_classification.ipynb
