# 🩺 Diabetes Prediction using Machine Learning

This project uses the **Pima Indians Diabetes Dataset** to predict whether a person is diabetic using health data and a Machine Learning model.

## 🚀 Features
- Used **Random Forest Classifier**
- Scaled inputs using **StandardScaler**
- Achieved **~81% accuracy**
- Accepts real-time user input for prediction

## 🧠 Tech Stack
- Python
- Jupyter Notebook
- pandas, numpy
- scikit-learn (ML magic)

## 📁 Dataset Info
- Source: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Total Rows: 768
- Columns:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (0 = Not Diabetic, 1 = Diabetic)

## 📊 Example Prediction
```python
# Example input
[5, 160, 70, 32, 100, 35.0, 0.8, 42]

Model Output
"⚠️ Diabetic Detected"
```
## How to Run
Clone the repo:
git clone https://github.com/siddhikasavant/Diabetes-Prediction.git
Open main.ipynb in Jupyter
Run all cells & try testing your own values
