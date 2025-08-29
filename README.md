# Laptop Price Prediction with Machine Learning

## Project Overview

This project showcases an end-to-end machine learning workflow to predict the price of a laptop based on its specifications. The goal is to build a robust regression model that can accurately estimate the price, providing valuable insights for both buyers and sellers in the computer market.

The analysis and model building are performed using Python, with a focus on core data science and machine learning libraries.

### Key Tasks & Methodology

1.  **Data Loading & Initial Exploration**: Load the dataset and perform an initial review of its structure, data types, and summary statistics.
2.  **Data Cleaning & Preprocessing**: Clean the data by handling missing values and preparing features for model consumption.
3.  **Exploratory Data Analysis (EDA)**: Visualize key relationships between features (e.g., `CPU`, `RAM`, `Storage`, `GPU`) and the target variable (`Price`) to identify patterns and potential insights.
4.  **Model Training**:
    * Split the data into training and testing sets.
    * Train two regression models:
        * **Linear Regression**: A baseline model to establish a simple benchmark.
        * **Random Forest Regressor**: A more robust ensemble model to capture non-linear relationships and improve predictive accuracy.
5.  **Model Evaluation**: Evaluate the performance of both models using metrics such as $R^2$ score to determine which model is more suitable for this problem.


### Dataset Description

The dataset used is a fictional CSV file named `Cleaned_Laptop_data.csv`, containing information on various laptop listings. It includes the following fields:

- `Brand` : Brand of the laptop (e.g., HP, Dell).
- `Model` : Model of the laptop (e.g., Spectre, XPS).
- `CPU` : Processor of the laptop.
- `RAM` : RAM size in GB.
- `Storage` : Storage size in GB.
- `GPU` : Graphics card of the laptop.
- `OS` : Operating system.
- `Price` : The target variable - the price of the laptop.

### Technologies and Libraries Used

* **Python**: The core programming language.
* **Jupyter Notebook**: For an interactive and reproducible analysis environment.
* **Pandas**: Essential for data loading, cleaning, and manipulation.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For data visualization.
* **Scikit-learn**: The primary library for machine learning, including data preprocessing and model training.

### How to Run the Project

1. Clone this repository to your local machine.
2. Ensure you have Python installed. It is highly recommended to use a virtual environment.
3. Install the required libraries using the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the `laptop_price_prediction.ipynb` notebook in Jupyter or a similar environment (e.g., VS Code).
5. Run the cells in the notebook sequentially to see the full data analysis and machine learning process.

