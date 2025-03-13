# Indian Premier League (IPL) Prediction and Statistical Insights

## 🏏 Project Overview
This project aims to predict the outcomes of Indian Premier League (IPL) matches using various machine learning models. By analyzing historical match data from 2008 to 2022, we derive statistical insights and build predictive models to forecast match results.

## 📁 Repository Structure

### 📂 data/
Contains datasets used for analysis and modeling.
- `IPL_Matches_2008_2022.csv` - Comprehensive match data from 2008 to 2022.
- `IPL_Ball_by_Ball_2008_2022.csv` - Ball-by-ball details of each match.
- `IPLPlayerAuctionData.csv` - Information on player auctions and team compositions.

### 📂 notebooks/
Jupyter notebooks detailing data analysis and model development.
- `MATH448_Project_IPL_Prediction.ipynb` - Notebook covering data preprocessing, EDA, and model implementation.

### 📂 reports/
Documentation and reports generated from the analysis.
- `MATH 448 - IPL Prediction - Final Report.pdf` - Summarizes methodologies, findings, and conclusions.

### 📂 visualizations/
Visual representations of data insights and model results.
- `IPL_Prediction_EDA.pbix` - Power BI file showcasing interactive dashboards and visualizations.

## 🔍 Exploratory Data Analysis (EDA)
- **Team Performance**: Win/loss ratios, home vs. away performance.
- **Player Statistics**: Top performers, consistency metrics.
- **Venue Analysis**: Impact of venues on match outcomes.
- **Toss Influence**: Effect of toss decisions on match results.

## 🧠 Modeling Approach

Applied six machine learning algorithms to predict match outcomes:
1. **Logistic Regression** - Baseline classification model.
2. **Decision Tree Classifier** - Captures non-linear relationships.
3. **Random Forest Classifier** - Ensemble method to improve accuracy.
4. **Support Vector Machine (SVM)** - Effective in high-dimensional spaces.
5. **K-Nearest Neighbors (KNN)** - Simple, instance-based learning.
6. **Naïve Bayes** - Based on Bayes' theorem with independence assumptions.

### Evaluation Metrics
- **Accuracy**: Proportion of correct predictions.
- **Precision**: True positive rate among predicted positives.
- **Recall**: True positive rate among actual positives.
- **F1-Score**: Harmonic mean of precision and recall.

## 🚀 How to Use This Repository

1. **Clone the Repository**:

```bash
git clone https://github.com/thanojkrishna/IndianPremierLeaguePredictionAndStatisticalInsights.git
cd IndianPremierLeaguePredictionAndStatisticalInsights
```

2. **Set Up the Environment**:
- Ensure Python (3.7+) is installed.
- Install necessary packages:

```bash
pip install -r requirements.txt
```

3. **Explore the Data**:
- Navigate to `notebooks/` and open `MATH448_Project_IPL_Prediction.ipynb`.

4. **Interactive Visualizations**:
- Open `IPL_Prediction_EDA.pbix` in Power BI Desktop.

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements
- Data sourced from [Kaggle IPL Dataset](https://www.kaggle.com/datasets).
- Special thanks to the course instructors of MATH 448 for guidance and support.

---
Feel free to fork, star, or contribute to this repository if you find it useful!
