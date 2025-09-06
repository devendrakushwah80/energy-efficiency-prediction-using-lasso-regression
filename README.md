# 🔥 Lasso Regression Project – Energy Efficiency Prediction  

This project demonstrates the use of **Lasso Regression (L1 Regularization)** for predicting **Heating Load** from building energy efficiency data.  
Unlike Ridge Regression, Lasso can shrink some feature coefficients to **zero**, effectively performing **feature selection**.  

---

## 📌 Dataset
- **Source**: UCI Machine Learning Repository – Energy Efficiency Dataset  
- **File Used**: `ENB2012_data.xlsx`  
- **Features (X)**: 8 building characteristics (Relative Compactness, Surface Area, Wall Area, Roof Area, Overall Height, Orientation, Glazing Area, Glazing Area Distribution).  
- **Target (y)**: Heating Load (y1).  

---

## 📊 Project Workflow
1. **Data Loading & Preprocessing**  
   - Load dataset with `pandas`  
   - Select features & target variable  

2. **Train-Test Split**  
   - Split data into training & testing (80-20)  

3. **Model Training**  
   - Linear Regression (baseline)  
   - Lasso Regression (`alpha=0.1`)  

4. **Evaluation Metrics**  
   - R² Score  
   - Mean Squared Error (MSE)  
   - Mean Absolute Error (MAE)  

5. **Visualization**  
   - Scatter plot comparing Linear vs Lasso predictions  

---

## ⚙️ Installation & Requirements
Install required libraries:
```bash
pip install pandas numpy matplotlib scikit-learn openpyxl
