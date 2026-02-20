# 🌾 Crop Yield Prediction using Machine Learning

A complete end-to-end Machine Learning pipeline that analyzes
agricultural data and predicts crop yield using multiple regression
models.

This project includes: - Exploratory Data Analysis (EDA) - Feature
Engineering - Model Training - Hyperparameter Tuning - Model Evaluation
& Comparison

The goal is to understand how environmental and agricultural factors
such as rainfall, fertilizer usage, and pesticides influence crop
production.

------------------------------------------------------------------------

## 📌 Project Overview

This project applies several supervised learning algorithms to forecast
crop yield.\
Multiple regression models were trained and evaluated to determine the
best-performing approach.

🏆 **Best Model: XGBoost Regressor**\
**R² Score: 0.9575**

------------------------------------------------------------------------

## 🚀 Features

-   Detailed Exploratory Data Analysis
-   Feature Engineering (ratio-based features)
-   Outlier Handling (99th percentile capping)
-   Log Transformation of target variable
-   Data preprocessing pipeline
-   Hyperparameter tuning using GridSearchCV
-   5-Fold Cross Validation
-   Model comparison
-   Model saving using joblib

------------------------------------------------------------------------

## 🧠 Machine Learning Models Used

-   Linear Regression (Baseline)
-   Decision Tree Regressor
-   Random Forest Regressor
-   LightGBM Regressor
-   XGBoost Regressor ⭐ (Best Performing)

------------------------------------------------------------------------

## 📊 Exploratory Data Analysis

The `eda.ipynb` notebook includes:

-   Distribution analysis
-   Correlation heatmaps
-   Feature relationships
-   Statistical insights
-   Data visualization using Matplotlib and Seaborn

------------------------------------------------------------------------

## ⚙️ Machine Learning Pipeline

The `model.ipynb` notebook performs:

### Data Preparation

-   Feature scaling
-   Creation of ratio features (e.g., fertilizer per area)
-   Log transformation of target variable
-   Train/Test split (80/20)

### Model Training

-   Cross-validation (5-fold)
-   Hyperparameter tuning using GridSearchCV
-   Model performance evaluation

### Evaluation Metrics

-   R² Score
-   Mean Absolute Error (MAE)
-   Mean Squared Error (MSE)

------------------------------------------------------------------------

## 🧰 Tech Stack

### Programming Language

-   Python 3.x

### Libraries

-   Pandas
-   NumPy
-   Scikit-learn
-   XGBoost
-   LightGBM
-   Matplotlib
-   Seaborn
-   Category Encoders
-   Joblib

------------------------------------------------------------------------

## 📁 Project Structure

    Crop-Yield-Prediction/
    │
    ├── eda.ipynb          # Exploratory Data Analysis
    ├── model.ipynb        # ML pipeline & training
    ├── requirements.txt   # Dependencies (recommended)
    └── README.md

------------------------------------------------------------------------

## 🛠 Installation & Setup

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/your-username/crop-yield-prediction.git
cd crop-yield-prediction
```

### 2️⃣ Create virtual environment (Recommended)

``` bash
python -m venv venv
```

Activate environment:

**Windows**

``` bash
venv\Scripts\activate
```

**Mac/Linux**

``` bash
source venv/bin/activate
```

### 3️⃣ Install dependencies

If you have `requirements.txt`:

``` bash
pip install -r requirements.txt
```

Or install manually:

``` bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm category_encoders joblib
```

------------------------------------------------------------------------

## ▶️ How to Run

1.  Start Jupyter Notebook:

``` bash
jupyter notebook
```

2.  Open and run notebooks in order:

`eda.ipynb → model.ipynb`

------------------------------------------------------------------------

## 📈 Results

  Model               Performance
  ------------------- -----------------------
  Linear Regression   Baseline
  Decision Tree       Moderate
  Random Forest       Good
  LightGBM            Very Good
  XGBoost             ⭐ Best (R² = 0.9575)

### Conclusion

XGBoost achieved the highest accuracy and best generalization
performance for crop yield prediction.

------------------------------------------------------------------------

## 🎯 Future Improvements

-   Deploy as a web app (Streamlit / Flask)
-   Integrate real-time weather API data
-   Support multiple crop types
-   Add satellite / remote sensing data
-   Build a farmer recommendation system

------------------------------------------------------------------------

## 🤝 Contributing

Contributions are welcome!

1.  Fork the repository
2.  Create a new branch
3.  Make improvements
4.  Submit a Pull Request

------------------------------------------------------------------------

## 📜 License

This project is open source and available under the MIT License.

------------------------------------------------------------------------

## 🙌 Acknowledgements

-   Scikit-learn Documentation
-   XGBoost Community
-   LightGBM Community
-   Open Agricultural Datasets
