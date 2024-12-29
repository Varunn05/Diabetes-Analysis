# Diabetes Prediction Project 🚀

## Overview  
This project aims to predict the likelihood of diabetes in patients based on diagnostic measurements. By leveraging machine learning algorithms, we analyze key health indicators to provide accurate predictions. The project involves comprehensive data preprocessing, exploratory data analysis (EDA), and model evaluation using classification metrics.

---  

## Dataset 📊  
**Source**: PIMA Indian Diabetes Dataset (768 samples, 9 features)  
**Features**:  
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  
- Outcome (Target Variable: 0 - No Diabetes, 1 - Diabetes)  

---  

## Workflow 🔄  
1. **Data Preprocessing**  
- Replaced zero values with median imputation for Glucose, BMI, and Insulin.  
- Applied IQR to handle outliers across multiple features.  
- Scaled data using StandardScaler to normalize feature ranges.  

2. **Exploratory Data Analysis (EDA)**  
- Visualized distributions using count plots, histograms, and pie charts.  
- Generated pair plots and correlation heatmaps to reveal feature interactions.  
- Scatter and line plots created with Plotly for interactive visualization.  

3. **Model Building and Evaluation**  
- **Logistic Regression**: Achieved 79% accuracy on the test set with ROC AUC score of 0.83.  
- **Support Vector Machine (SVM)**: Tuned poly, rbf, and sigmoid kernels to enhance accuracy.
- Visualized model performance using ROC curves and confusion matrices.  

---  

## Key Results 📈  
- **Logistic Regression**: 79% Test Accuracy  
- **SVM (Poly Kernel)**: 90% Training Accuracy  
- **ROC AUC Score**: 0.83  
- **Confusion Matrix Analysis**: Highlighted precision and recall for improved predictions.  

---  

## Visualizations 🖼️  
- Correlation Heatmap  
- Distribution Plots (Glucose, BMI, Age, etc.)  
- ROC Curve (Logistic Regression)  
- Pair Plots and Scatterplots (3D Plotly Visualization)  

---  

## How to Run 🛠️  
1. Clone the repository  
```bash  
git clone https://github.com/username/diabetes-prediction.git  
```
2. Install dependencies  
```bash  
pip install -r requirements.txt  
```
3. Run the notebook  
```bash  
jupyter notebook diabetesassignment.ipynb  
```

---  

## Dependencies 📦  
- Python 3.8+  
- NumPy, Pandas, Matplotlib, Seaborn  
- Scikit-Learn  
- Plotly  

---  

## Future Improvements 🚧  
- Implement deep learning models for higher accuracy.  
- Optimize SVM parameters using GridSearchCV.  
- Deploy the model as a web application for real-time predictions.

