# Daily Rainfall Forecasting Using Advanced Regression Models

This repository contains a comprehensive machine learning project for predicting **next-day rainfall** using historical meteorological data from **Mashhad, Iran**. The goal is to explore and compare a wide range of regression models — from classical linear regression to flexible nonparametric methods — and identify the most effective predictors of rainfall.

---

## Objective

To model the relationship between meteorological features (temperature, humidity, wind, solar radiation, etc.) and the next day's rainfall using:

*  **Linear and Polynomial Regression**
*  **Regularized Models** (Ridge, Lasso, ElasticNet)
*  **Support Vector Regression (SVR)** — Linear, Polynomial, RBF kernels
*  **Decision Tree & Random Forest Regressors**
*  **Spline-Based Regression (Cubic, Natural, GAM-style)**
*  **Generalized Additive Models (GAM)**
*  **ElasticNet**
*  **KNN Regression**

---

## Dataset

* **Source**: Daily meteorological records from the Mashhad weather station.
* **Features**:

  * Temperature (max, min, avg)
  * Humidity (max, min, avg)
  * Solar radiation
  * Wind speed
  * Rainfall (target)

---

## Key Takeaways

* **Natural Spline Regression** achieved the best predictive accuracy (lowest RMSE and highest R²).
* Regularized models helped mitigate overfitting but did not outperform spline models.
* Polynomial regression (degree 2+) showed poor generalization despite low train error.
* Ensemble models like **Random Forest** performed well but not significantly better than linear models.

---

## Contributors

* **Alireza Shadman**: [LinkedIn Profile](https://www.linkedin.com/in/alireza-shadman-7186497/)
* **Amirhossein Babaeian**: [LinkedIn Profile](https://www.linkedin.com/in/amirhossein-babaeian/)
* **Mahdi Rostamzadeh**: [LinkedIn Profile](https://www.linkedin.com/in/mahdi-rostamzadeh/)
