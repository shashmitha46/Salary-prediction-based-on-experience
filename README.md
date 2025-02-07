# Salary Prediction Based on Experience
This repository contains a Salary Prediction Model that estimates a person's salary based on their years of experience. The model is trained on a synthetic dataset and uses regression techniques to establish the relationship between experience and salary.

## 📌 Project Overview
In this project, we generate a synthetic dataset to simulate real-world salary trends and apply machine learning techniques to predict salaries. The key steps involved are:

- Data Generation: Creating a synthetic dataset with experience and corresponding salary.
- Data Preprocessing: Handling missing values, scaling features, and exploratory data analysis (EDA).
- Model Selection: Using regression algorithms to train the model.
- Evaluation: Assessing model performance using metrics such as Mean Squared Error (MSE) and R² Score.
## 📂 Repository Structure
```
├── Synthetic_salary.ipynb   # Jupyter notebook for data generation and model training
├── dataset/                 # Folder containing generated datasets (if applicable)
├── README.md                # Project documentation (this file)
└── requirements.txt         # List of dependencies (if required)
```
## 🚀 Getting Started
#### Prerequisites
Ensure you have Python 3.x installed along with the following libraries:
```
pip install numpy pandas matplotlib seaborn scikit-learn
```
#### Running the Project
1. Clone the repository:
```
git clone https://github.com/shashmitha46/Salary-prediction-based-on-experience.git
cd Salary-prediction-based-on-experience
```
2. Open Synthetic_salary.ipynb in Jupyter Notebook and execute the cells.
## 📊 Model & Results
- The model uses Linear Regression as the primary algorithm.
- Performance metrics such as Mean Squared Error (MSE) and R² Score are used to evaluate the accuracy of predictions.
- The salary trend is visualized through scatter plots and regression lines.
## 🔥 Future Enhancements
- Integrate more features such as education level, job sector, and location.
- Experiment with other regression models (Polynomial Regression, Decision Tree, Random Forest).
- Deploy the model as a web application using Flask or FastAPI.
