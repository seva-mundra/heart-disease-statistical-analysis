# heart-disease-statistical-analysis
# Heart Disease Data Analysis Using Python

## Overview
This project explores the UCI Heart Disease dataset using Python. It combines web scraping, data preprocessing, exploratory data analysis (EDA), statistical methods, and regression models to understand patient data and analyze relationships between health-related features.

## Objectives
- Collect dataset information using web scraping.
- Perform data cleaning and preprocessing.
- Explore data distributions, correlations, and visual patterns.
- Apply sampling techniques, bootstrap resampling, and the Central Limit Theorem.
- Perform confidence interval estimation and hypothesis testing.
- Compare regression models using evaluation metrics.

## Technologies Used
- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Web Scraping:** Requests, BeautifulSoup
- **Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** SciPy
- **Machine Learning:** Scikit-learn
- **Model Saving:** Joblib
- **Optional Interface:** Gradio

## Dataset
- **Source:** UCI Machine Learning Repository
- **Dataset:** Heart Disease
- **Domain:** Healthcare
- **Task:** Statistical analysis and regression modelling

Dataset source: https://archive.ics.uci.edu/dataset/45/heart+disease

## Project Workflow
1. Retrieve and explore dataset information using web scraping.
2. Load the heart disease data and preprocess the features.
3. Perform exploratory data analysis and correlation analysis.
4. Study sampling distributions, the Central Limit Theorem, and bootstrap resampling.
5. Conduct confidence interval estimation and hypothesis testing.
6. Apply independent and paired t-tests.
7. Build and compare simple and multiple linear regression models.
8. Evaluate models using MAE, MSE, RMSE, and R².
9. Save selected regression models and scalers using Joblib.
10. Explore an optional Gradio interface for predictions.

## Regression Models
The notebook compares:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor

The regression tasks predict maximum recorded heart rate (`thalach`) using age, and multiple features including age, resting blood pressure, and cholesterol.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `SI_BP_analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run the notebook cells in order.

Install the main dependencies:

```bash
pip install requests beautifulsoup4 lxml html5lib pandas numpy matplotlib seaborn scipy scikit-learn joblib gradio
```

## Learning Outcomes
- Practical experience with web scraping and data acquisition.
- Understanding of statistical inference and hypothesis testing.
- Application of sampling and resampling techniques.
- Experience building and evaluating regression models.
- Data visualization and interpretation using Python.

## Disclaimer
This is an educational data science project. Its statistical analyses and regression predictions are not intended for medical diagnosis or clinical decision-making.
