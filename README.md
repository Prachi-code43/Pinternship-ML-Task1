# California Housing Price Predictor — Task 1

## Project Overview
This repository contains the implementation of **Task 1** for my Machine Learning Internship at **Maincrafts Technology**. The goal of this project is to build, evaluate, and analyze a baseline **Linear Regression** model to predict median house values in California using the standard scikit-learn dataset.

## Repository Contents
* `task1_ml_linear_regression.ipynb`: The complete Jupyter Notebook containing data loading, train-test splitting, model training, evaluation metrics, and performance visualizations.

## Dataset Highlights
* **Source:** California Housing Dataset (scikit-learn)
* **Total Instances:** 20,640 records
* **Input Features:** 8 economic/geographic attributes (including Median Income, House Age, and Average Rooms)
* **Target Variable:** `MedHouseVal` (Median house value expressed in $100,000s)

## Model Performance Metrics
The baseline Linear Regression model achieved the following evaluation scores:
* **Mean Absolute Error (MAE):** 0.533 (On average, predictions deviate by ~$53,300)
* **Root Mean Squared Error (RMSE):** 0.746 (Highlights the presence of high-value outliers)
* **R² Score (Coefficient of Determination):** 0.576 (The features explain 57.6% of the variance in housing prices)

## Key Takeaways & Future Scope
While the baseline linear model offers a solid foundational start, it struggles to capture non-linear geographical patterns (such as premium coastal properties). 
* **Next Steps:** Implement complex tree-based ensemble models (e.g., Random Forest, XGBoost) and perform feature engineering to capture deeper spatial interactions.

---
**Developed by:** Prachi Sarode  
**Role:** Machine Learning Intern  
**Company:** Maincrafts Technology
