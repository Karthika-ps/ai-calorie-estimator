# 🍎 AI System for Calorie Estimation

This project uses machine learning to estimate the calorie content of various food items based on nutrient composition data.

## 📘 Overview
The model analyses nutrient information from the **FoodData Central Dataset** (U.S. Department of Agriculture) to predict the energy (calories) of foods. The project demonstrates end-to-end data handling — from preprocessing and feature engineering to model training and evaluation.

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  

## 🧩 Key Steps
1. Data extraction and cleaning from the FoodData Central dataset  
2. Merging nutrient tables and removing missing values  
3. Feature selection and preprocessing  
4. Training regression models:
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - K-Nearest Neighbors Regressor  
5. Model evaluation with R² and MSE metrics

## 📈 Results
- **Best model:** Random Forest Regressor  
- **R² score:** ~0.987  
- Demonstrates strong correlation between predicted and actual calorie values.

## 📂 Files
- `AIAssignmentNotebook.ipynb`: Main implementation and analysis notebook.

## ✨ Future Improvements
- Deploy as a simple web app using Flask or Streamlit  
- Integrate with a mobile app for real-time calorie predictions  
