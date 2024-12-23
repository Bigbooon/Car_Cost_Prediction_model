# Car Cost Prediction Model

## Description
This project aims to predict car prices and classify cars as expensive or not based on their attributes using machine learning models. The dataset, sourced from **Kolesa.kz**, contains various features such as car brand, model, engine volume, mileage, and more. The primary goal is to develop a reliable predictive system for estimating car costs.

## Features of the Project

### 1. Data Cleaning and Preprocessing
- **Handling Missing Values**: Filled missing values in key columns like `Model`, `Drive Type`, and `Fuel Type`.
- **Encoding**: Used one-hot encoding for categorical variables.
- **Standardization**: Scaled numerical features such as mileage and engine volume.

### 2. Machine Learning Models
- **Regression Models** for price prediction:
  - Linear Regression
  - Decision Trees
  - Random Forest
  - Support Vector Regression (SVR)
  - K-Nearest Neighbors (KNN)

- **Classification Models** for determining expensive cars:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)

### 3. Model Evaluation
- **Regression Metrics**:
  - Mean Squared Error (MSE)
  - R² Score

- **Classification Metrics**:
  - Accuracy
  - Classification Reports (Precision, Recall, F1-Score)

### 4. Interactive Features
- Implemented **interactive widgets** to allow users to input car attributes (brand, model, year, engine volume, etc.) and predict prices dynamically.

## Key Findings
- The **Random Forest Regressor** achieved the best R² score of **0.937** and the lowest MSE.
- The **Random Forest Classifier** showed the highest classification accuracy of **69.1%**.

## How to Use
1. Clone the repository or download the files.
2. Open the Jupyter Notebook.
3. Use the interactive widgets to input car features like brand, model, year, and engine volume.
4. View the predicted price or classification result.

## Dataset
- Source: **[Kolesa.kz](https://kolesa.kz)**
- The dataset includes features such as:
  - Car brand and model
  - Year of manufacture
  - Mileage and engine volume
  - Transmission type, fuel type, and drive type
  - Color and customs clearance status

## Dependencies
To run the project, ensure you have the following libraries installed:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- ipywidgets (for interactive features)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/car-cost-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Results
- The project demonstrates the effectiveness of ensemble methods like Random Forest for both regression and classification tasks.
- Interactive widgets enhance usability, allowing users to explore predictions dynamically.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Data sourced from **Kolesa.kz**.
- Built using Python and Scikit-learn.

