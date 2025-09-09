# Advanced House Price Prediction 🏡

## 1. Project Overview

This project presents a complete data science workflow to accurately predict residential house prices in King County, USA. The primary objective is to develop a high-performance regression model by leveraging advanced feature engineering and the LightGBM algorithm. The final model successfully explains approximately 88% of the variance in house prices, providing valuable insights into the key drivers of the real estate market.

---

## 2. Key Features

* **End-to-End Workflow:** Covers every step from data loading and cleaning to model training and evaluation.
* **Exploratory Data Analysis (EDA):** Analyzes data distributions and feature correlations to inform modeling strategies.
* **Advanced Feature Engineering:** Creates new, insightful features like `house_age` and `was_renovated` to improve model accuracy.
* **High-Performance Modeling:** Implements a **LightGBM Regressor**, a powerful and efficient gradient boosting model.
* **Insightful Results:** Generates a feature importance plot to identify the key factors influencing house prices.

---

## 3. Dataset

The project uses the **King County House Sales dataset** (`kc_house_data.csv`).

* **Size:** 21,613 property listings.
* **Key Features:** `price`, `bedrooms`, `sqft_living`, `grade`, `lat`, `long`, `yr_built`.
* **Target Variable:** `price`.

---

## 4. How to Run This Project

### Prerequisites

To run the project notebook, you will need Python 3 and the libraries listed in the `requirements.txt` file.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

### Usage

Open and run the Jupyter Notebook `Advanced-House-Price-Prediction.ipynb` to see the complete analysis, from data loading to the final model evaluation.
