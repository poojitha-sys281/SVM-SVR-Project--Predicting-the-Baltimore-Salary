# SVM-SVR-Project--Predicting-the-Baltimore-Salary
# Predicting Baltimore Employee Salary using Support Vector Regression (SVR)

##  Project Overview
This project focuses on predicting employee salaries in Baltimore based on their joining date using **Support Vector Regression (SVR)**, a supervised machine learning algorithm. The goal is to understand how salary trends vary over time and to build a predictive model that can estimate salaries for given joining dates.

---

##  Objectives
- To preprocess and transform date-based data into numerical features
- To apply Support Vector Regression for salary prediction
- To evaluate the model’s performance
- To predict salaries for new joining dates

---

## Technologies Used
- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## Dataset Description
The dataset contains employee salary information along with their joining dates in Baltimore.  
The joining dates are converted into numerical features such as **year and month** to train the SVR model.

---

## Methodology
1. Data loading and cleaning  
2. Feature extraction from joining dates  
3. Feature scaling using StandardScaler  
4. Training the Support Vector Regression (SVR) model  
5. Predicting salaries for new joining dates  
6. Inverse transforming predictions to obtain actual salary values  

---

## Results
- The model successfully predicts salaries for joining dates within the training data range.
- Predictions for very future dates may be less reliable due to extrapolation.
- Final predictions are converted back to actual salary values for better interpretation.

---

## Example Prediction
- Joining Date: 02/09/2005 → Predicted Salary: (actual salary value)
- Joining Date: 12/12/2090 → Predicted Salary: (model-based estimate, less reliable)

---

## How to Run the Project
1. Clone this repository  
2. Open the Jupyter Notebook file  
3. Install required libraries  
4. Run all cells sequentially  

---

## Conclusion
Support Vector Regression proves to be an effective approach for salary prediction when trained with appropriate features and scaling techniques. This project demonstrates how machine learning models can be applied to real-world salary prediction problems.

---

## 👩‍💻 Author
Poojitha
