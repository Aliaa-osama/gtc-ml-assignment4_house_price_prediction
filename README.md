# 🏡 House Price Prediction

## 📌 Project Overview

This project predicts **California housing prices** using machine
learning models.\
The workflow includes: - Data loading & cleaning\
- Feature selection\
- Splitting the dataset into train/test sets\
- Applying multiple machine learning models (Linear Regression, Random
Forest)\
- Evaluating results and reducing overfitting with cross-validation

------------------------------------------------------------------------

## 📂 Project Structure

    house_price_predection.ipynb   # Main Jupyter Notebook
    housing.csv                    # Dataset (California Housing Prices)
    README.md                      # Project documentation (this file)

------------------------------------------------------------------------

## ⚙️ Requirements

Install the required libraries before running the notebook:

``` bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

------------------------------------------------------------------------

## 🚀 Usage

1.  Place `housing.csv` in the same folder as the notebook.\

2.  Open the notebook:

    ``` bash
    jupyter notebook house_price_predection.ipynb
    ```

3.  Run the cells step by step to:

    -   Explore and clean the dataset\
    -   Build and train ML models\
    -   Evaluate performance

------------------------------------------------------------------------

## 📊 Models & Techniques

-   **Linear Regression** -- baseline model for prediction\
-   **Random Forest Regressor** -- more powerful model, but prone to
    overfitting\
-   **Cross-validation** -- applied to reduce overfitting and improve
    generalization

------------------------------------------------------------------------

## 📈 Key Findings

-   Some features with low correlation to the target
    (`median_house_value`) were dropped:\
    *households, population, total_bedrooms, longitude*\
-   **Random Forest performed better** than Linear Regression, but
    showed signs of **overfitting**.\
-   **Cross-validation** helped reduce variance and improve model
    robustness.

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Hyperparameter tuning with GridSearchCV / RandomizedSearchCV\
-   Try advanced models (XGBoost, Gradient Boosting, Neural Networks)\
-   Deploy the model using **Streamlit** or **Flask** for interactive
    predictions

------------------------------------------------------------------------

## 👩‍💻 Author

**Aliaa Osama Alkady**\
📧 <aliaa.osama20@gmail.com>\
🔗 [LinkedIn](https://www.linkedin.com/in/aliaaosamaalkady/)
