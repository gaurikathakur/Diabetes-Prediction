Diabetes Prediction

Predicting the likelihood of diabetes based on health‐parameters using machine learning.

Project Overview  
This application uses a machine learning model to estimate the risk of diabetes given health inputs such as age, BMI, glucose levels and other diagnostic factors. Useful for exploration/learning and should **not** be used as a medical diagnosis tool.

Features  
- Accepts input values (e.g., age, BMI, glucose, blood pressure, insulin levels)  
- Predicts probability of diabetes occurrence  
- Displays output as risk score + classification (e.g., “Low risk” / “High risk”)  
- (Optional) Visualisation of feature importances / ML model performance  
- (Optional) Web UI or CLI interface for easy input  

 Tech Stack  
- Programming Language: Python  
- Machine Learning Library: e.g., scikit-learn (or TensorFlow/Keras if used)  
- Tools: pandas, NumPy, matplotlib/seaborn (for visuals)  
- (Optional) Web or GUI: Streamlit, Flask, or similar  
- Dataset: e.g., Pima Indians Diabetes Dataset, or a custom dataset  

Installation & Setup  
```bash
git clone https://github.com/gaurikathakur/Diabetes-Prediction.git
cd Diabetes-Prediction
pip install -r requirements.txt
