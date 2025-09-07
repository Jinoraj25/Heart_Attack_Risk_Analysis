📊 Heart Disease Risk Prediction (Framingham Study)
📌 Project Overview

This project analyzes real-world health data from the Framingham Heart Study to explore the risk factors associated with Coronary Heart Disease (CHD).
Using Python (Pandas, Matplotlib, Seaborn), the notebook performs data cleaning, exploratory data analysis (EDA), and visualizations to highlight how age, gender, smoking, blood pressure, cholesterol, glucose, and other factors influence CHD risk.

🗂 Dataset Information

Source: Framingham Heart Study (public dataset)

Records: 4,000+ participants with multiple health parameters

Features include:

Demographics: Age, Gender

Lifestyle: Smoking, Diabetes

Clinical: Blood Pressure, Cholesterol, Glucose, BMI, Heart Rate

Target: Ten_Year_CHD (1 = Risk, 0 = No Risk)

⚕️ Medical Context (Key Ranges)

Total Cholesterol: Normal < 200 mg/dL | High Risk > 240 mg/dL

Blood Pressure: Normal < 120/80 mmHg | Hypertension ≥ 140/90 mmHg

Glucose: Normal < 140 mg/dL | Diabetes ≥ 200 mg/dL

BMI: Normal 18.5–24.9 | Obesity ≥ 30

Heart Rate: Normal 60–100 bpm | Tachycardia > 100 bpm

This helps interpret visualizations in terms of medical health risks.

🛠 Steps in the Project

Data Cleaning

Removed duplicates, standardized column names.

Decided not to remove medical outliers (e.g., very high cholesterol, extreme smoking) since they can represent real high-risk cases.

Exploratory Data Analysis (EDA)

Gender vs CHD risk

Smoking vs CHD risk

Age trends in CHD risk

Hypertension impact on CHD

Glucose levels by diabetes status

Cholesterol distribution

Correlation heatmap

Visualization

Saved charts in the 📂 images/ folder

Used bar plots, line plots, KDE plots, scatter plots, pie chart, heatmap

Insights

CHD risk increases significantly with age.

Smokers show higher CHD risk than non-smokers.

Hypertension and high cholesterol strongly correlate with CHD.

Diabetics have higher glucose and increased CHD risk.

Male participants show slightly higher risk compared to females.


🚀 How to Run

Clone this repository:

git clone <repo-link>


Open the notebook in Jupyter:

jupyter notebook "Heart Disease Risk Prediction Using Real-World Health Data (Framingham Study).ipynb"


Run all cells to reproduce the analysis.

📌 Conclusion

This analysis highlights the critical role of age, smoking, hypertension, cholesterol, and diabetes in predicting heart disease risk.
The project demonstrates how data analysis can provide actionable health insights and serves as a strong foundation for predictive modeling in healthcare.

## Author

**Jino G J**  
GitHub: [https://github.com/Jinoraj25](https://github.com/Jinoraj25)

