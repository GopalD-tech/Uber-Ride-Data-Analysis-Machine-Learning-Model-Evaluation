# Uber-Ride-Data-Analysis-Machine-Learning-Model-Evaluation
Conducted end-to-end analysis of Uber ride data using Python (EDA, visualization, feature engineering). Evaluated multiple machine learning models for trip pattern prediction. XGBoost achieved the highest accuracy at 82%, outperforming linear models.
📂 Project Overview

The dataset contains:

Start & End Date and Time

Ride Category (Business/Personal)

Start & Stop Locations

Miles Traveled

Purpose of Trip

The goal is to perform EDA + visualization and build machine learning models to predict ride-related metrics and understand factors influencing trip behavior.

🔧 Tech Stack

Languages & Libraries:

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost, LightGBM, CatBoost

Jupyter Notebook

🧹 Data Cleaning & Preprocessing

Steps performed:

Removed missing/duplicate values

Processed and formatted date–time columns

Extracted features (Hour, Day, Month, Weekday)

Encoded categorical features

Normalized and scaled numerical values

Cleaned inconsistent text fields

📊 Exploratory Data Analysis (EDA)

Key insights:

Peak ride hours & busiest weekdays

Most used ride categories

Frequently visited start & stop locations

Business vs Personal ride patterns

Trip distance distribution

Purpose-based trends

Visualizations used:
✔ Line charts
✔ Bar charts
✔ Heatmaps
✔ Boxplots
✔ Distribution plots

🤖 Machine Learning Model Evaluation

A total of 11 regression models were trained and benchmarked.

🔥 Model Accuracy Scores
Model	Accuracy
XGBoost	0.821
LightGBM	0.756
Decision Tree	0.742
ADA Boost	0.738
CatBoost	0.735
Random Forest	0.736
Gradient Boosting	0.730
KNN Regressor	0.665
Linear SVR	0.520
SVR	0.161
Linear Regression	-1.14e19
🧠 Key Findings

XGBoost performed the best, achieving 82% accuracy, showing strong predictive capability for mobility datasets.

Linear Regression performed very poorly due to non-linear relationships and feature complexity.

Time-based features (hour, month, weekday) strongly influence ride behavior.

Tree-based models are more suitable for transport and ride-hailing data.

📈 Conclusion

This project demonstrates:

End-to-end data analysis workflow

Handling real-world transportation data

Clear understanding of EDA and visualization

Model building, tuning, and comparison

Insight generation and data storytelling

This analysis can help companies like Uber, Ola, Rapido, or Yatri Sathi understand customer trends, optimize driver allocation, and forecast demand.

📁 Project Files

Uber_Analysis.ipynb – Complete notebook

data.csv – Dataset

README.md – Project documentation

models/ – Saved ML models (optional)

visuals/ – Graphs and plots (optional)
