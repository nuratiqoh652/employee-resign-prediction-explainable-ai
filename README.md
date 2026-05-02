# Employee Resign Prediction with Explainable AI

Employee resign prediction using machine learning with Explainable AI (Feature Importance &amp; Permutation Importance) to identify key drivers of employee turnover.
**Author:** Nur Atiqoh  

## Description
This project focuses on predicting employee resignation using machine learning and applying Explainable AI (XAI) techniques to understand the key factors driving employee turnover.

## Objectives
- Predict the probability of employee resignation  
- Identify key features influencing model predictions  
- Provide actionable insights for employee retention strategies  

## Methodology

### 1. Data Preprocessing
- Encoding categorical variables  
- Transforming data into numerical format  
- Resulting dataset in sparse matrix (csr_matrix) format  

### 2. Modeling
- Machine learning model for resignation prediction  

### 3. Model Interpretation (Explainable AI)

#### Challenges in Advanced Methods
- Data transformed into sparse matrix (csr_matrix)  
- High dimensionality after encoding  
- Errors encountered when applying Partial Dependence Plot (PDP)  
- SHAP requires high computational resources and dependency stability  

#### Chosen Approach
To ensure stability and reliability:
- Feature Importance  
- Permutation Importance  

These methods are more robust and suitable for the dataset condition.

## Key Insights

- Model predictions are driven by a small number of key features  
- Not all variables contribute equally to resignation decisions  

### 🔹 Dominant Feature
- **Feature 57** has the highest importance  
- Significantly more influential than other features  

### 🔹 Feature Impact Distribution
- Large gap between Feature 57 and other features (e.g., Feature 50)  
- Most features have minimal impact  

### 🔹 Potential Threshold Effect
- Model indicates certain conditions in key features significantly increase resignation probability  

## Business Insights
- Employee resignation is primarily influenced by a few key factors  
- Not all variables equally impact employee decisions  

## Business Recommendations
- Focus retention strategies on the most influential features  
- Prioritize high-impact factors to reduce employee turnover  
- Implement preventive actions based on key drivers identified by the model  

## Expected Impact
- Reduced employee turnover  
- Improved retention strategy effectiveness  
- Better HR decision-making based on data  

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  

## Conclusion
Explainable AI helps uncover the key drivers behind employee resignation, enabling organizations to make more informed and targeted retention decisions.

---
