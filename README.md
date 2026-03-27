# 🚗 Used Car Price Prediction: An End-to-End Machine Learning Pipeline

## 📌 Project Objective
The primary objective of this project is to build a robust, end-to-end Machine Learning pipeline to estimate the realistic selling price of used cars. By mapping historical market records—including both categorical and numerical variables—I developed a model that accurately reflects the real-world economic dynamics of automotive valuation and asset depreciation.

## 🧠 Methodology & Technical Approach
Instead of relying on a basic out-of-the-box model, I focused heavily on data quality and feature space optimization. The workflow includes:

* **Exploratory Data Analysis (EDA) & Pre-processing:** Cleaning the dataset, handling missing values, and analyzing distributions to understand the underlying market trends.
* **Enhanced Feature Engineering:** I augmented the baseline feature space by introducing **non-linear polynomial terms** and **cross-feature interactions**. This optimization significantly increased the model's explanatory power and its ability to capture complex, multi-dimensional variance in car prices.
* **Predictive Modeling:** Implemented a **Linear Regression** model optimized for continuous metrics and nominal indicators.
* **Robust Model Validation:** To ensure strict generalizability and mitigate overfitting, I implemented **K-Fold Cross-Validation** seamlessly integrated within a Scikit-Learn transformation pipeline.

## 📊 Dataset Features
The model is trained on the following key specifications:
* `Car_Name`: Name / model of the car
* `Year`: The year the car was purchased
* `Selling_Price`: The target variable (Current selling price)
* `Present_Price`: Current ex-showroom price of the car
* `Kms_Driven`: Total kilometers driven
* `Fuel_Type`: Petrol / Diesel / CNG
* `Seller_Type`: Dealer / Individual
* `Transmission`: Manual / Automatic
* `Owner`: Number of previous owners

## 💻 Tech Stack & Tools
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn (Pipelines, Cross-validation, Linear Model), Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

