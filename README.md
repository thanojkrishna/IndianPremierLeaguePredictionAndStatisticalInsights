# IPL Match Outcome Prediction

This project aims to predict the outcomes of Indian Premier League (IPL) matches using various machine learning models. The dataset spans from 2008 to 2022, providing detailed information on matches, player performances, and other relevant metrics. Six different machine learning models were implemented and evaluated for their predictive power.

## Project Structure

- **MATH448_Project_IPL_Prediction.ipynb**: The Jupyter Notebook containing the code and analysis.
- **IPL_Ball_by_Ball_2008_2022.csv**: The ball-by-ball data of IPL matches.
- **IPL_Matches_2008_2022.csv**: The match data of IPL matches.
- **Players_SuperCleaned.csv**: The cleaned data of players' performances.
- **IPL Prediction EDA.pbix**: The Power BI file for exploratory data analysis.
- **MATH 448 - IPL Prediction - Final Report.pdf**: The final report detailing the project findings and analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, scikit-learn

Project Overview:
-----------------
Data Description:
The project utilizes three comprehensive datasets detailing IPL matches, ball-by-ball deliveries, and player performances. Key features from these datasets were used to train the machine learning models.

Exploratory Data Analysis (EDA):
Detailed EDA was conducted to provide insights into match outcomes, player performances, and other relevant metrics. The EDA results are visualized using various plots and charts.

Model Implementation:
Six different machine learning models were implemented:

Logistic Regression
Random Forest
Support Vector Machine (SVM)
Gradient Boosting Classifier
Linear Discriminant Analysis (LDA)
Quadratic Discriminant Analysis (QDA)
Hyperparameter Tuning
Hyperparameter tuning was performed for each model using GridSearchCV to optimize their performance. The tuned models showed significant improvements in accuracy, precision, recall, and F1 score.

Results & Conclusion:
The results showed that the Gradient Boosting and Random Forest models performed the best after hyperparameter tuning. Detailed results and comparisons are provided in the final report.

Future Work:
Future improvements include incorporating additional data sources, advanced feature engineering, model ensemble techniques, and expanding the analysis to other cricket formats.

Appendix:
The appendix contains the Python code used for data preprocessing, model implementation, and evaluation.

