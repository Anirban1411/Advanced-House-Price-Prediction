# Advanced House Price Prediction 🏡📈

A machine learning project to predict residential house prices using Python and Scikit-learn. This project analyzes a real estate dataset to build and evaluate a robust regression model capable of estimating property values with high accuracy.

---
## 📋 Project Workflow

This project follows a complete data science workflow, from data exploration to model evaluation, ensuring a comprehensive analysis.

### Data Loading & Initial Analysis:
* The dataset is loaded using **Pandas**.
* Initial exploratory data analysis (EDA) is performed to understand the data's structure and identify key features.

### Exploratory Data Analysis (EDA) & Visualization:
* Visualizations are created using **Matplotlib** and **Seaborn** to understand the distribution of house prices.
* The relationships between different features (e.g., `sqft_living`, `grade`) and the final sale price are explored to uncover patterns.

### Data Preprocessing & Feature Engineering:
* The `price` variable is log-transformed to handle its skewed distribution.
* New features like `house_age` and `was_renovated` are engineered to provide more predictive power to the model.

### Model Training:
* The dataset is split into training and testing sets.
* A **LightGBM Regressor** model is trained on the data. The model uses `early_stopping` to prevent overfitting and improve generalization.

### Model Evaluation:
* The model's performance is evaluated on the unseen test set.
* Key metrics for this regression problem, including **R-squared (R²)** and **Root Mean Squared Error (RMSE)**, are calculated.
* A **Feature Importance** plot is generated to identify the key drivers of house prices according to the model.

---
## 📊 Dataset

The dataset used for this analysis is `kc_house_data.csv`. It contains anonymized data for house sales in King County, USA, with features such as square footage, number of bedrooms, geographical coordinates, and a target column indicating the final sale price.

---
## 🛠️ Technologies Used

* **Python:** The core programming language for the analysis.
* **Pandas:** For data manipulation and loading.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For data visualization.
* **Scikit-learn:** For data preprocessing and model evaluation.
* **LightGBM:** For building the high-performance regression model.
* **Google Colab / Jupyter Notebook:** As the environment for writing and running the code.

---
## 🚀 How to Run

To replicate this analysis, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/advanced-house-price-prediction.git](https://github.com/YOUR_USERNAME/advanced-house-price-prediction.git)
    ```

2.  **Open the notebook:**
    Upload the `.ipynb` file and the `kc_house_data.csv` file to your Google Colab or local Jupyter Notebook environment.

3.  **Run the cells:**
    Execute the cells in the notebook sequentially to see the analysis and results.

---
## 📈 Model Performance

The final model demonstrates a strong ability to predict house prices with high accuracy.

* **R-squared (R²) Score:** The model achieved an R² of **0.88**, meaning it successfully explains 88% of the variance in house prices. This indicates a very strong fit.
* **Root Mean Squared Error (RMSE) Score:** The model shows a low RMSE of **0.1656** on the log-transformed price scale, signifying a small average prediction error.

The detailed feature importances can be found in the chart within the notebook.
