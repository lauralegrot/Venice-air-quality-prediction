# Venice's air quality prediction 🌞🌧️🌫️  

## Project description
* **Next-day PM10 exceedance prediction for Venice** using multi-year meteorological data (2018–2019–2021–2022) to classify whether air quality will surpass the European regulatory limit of 50 µg/m³.
* Cost-effective air quality forecasting framework leveraging **weather variables** (temperature, humidity, wind speed, atmospheric pressure) from the Venice Tessera station, integrated with PM10 measurements from ARPA Veneto.
* **Trained and compared multiple statistical learning models** (Logistic Regression, Logistic Regression with interactions, LDA, QDA, Naive Bayes, Ridge, Lasso, KNN) on an imbalanced binary classification task, applying undersampling, backward stepwise feature selection (BIC/AIC), and decision-threshold optimization to improve sensitivity to high-pollution days.
* **Best overall performance achieved by Logistic Regression** on the undersampled dataset with optimized threshold (0.6), reaching **Accuracy ≈ 0.86, Recall up to 0.90, and F1-score ≈ 0.71**
