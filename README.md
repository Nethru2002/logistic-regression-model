# Logistic Regression Model

## Overview
This project implements a **Logistic Regression** model using Python and Scikit-Learn. It is designed to predict outcomes based on the dataset `customer_details.csv`.

## Dataset
The dataset used in this project is `customer_details.csv`. It contains customer information, which is preprocessed and used for model training.

## Installation & Requirements
To run this project, install the required dependencies:

```bash
pip install pandas numpy seaborn scikit-learn matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Nethru2002/logistic-regression-model.git
   cd logistic-regression-model
   ```
2. Place your dataset (`customer_details.csv`) in the project folder.
3. Open the Jupyter Notebook and execute the cells to preprocess data, train the model, and evaluate its performance.

## Model Training & Evaluation
- The dataset is split into **training and test sets**.
- **StandardScaler** is used for feature scaling.
- **Logistic Regression** is applied to classify the target variable.
- Model performance is evaluated using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **ROC Curve**
  - **Classification Report**

## Results
The model's effectiveness is determined by accuracy and other performance metrics. Check the notebook for detailed results and visualizations.

## License
This project is open-source and available under the MIT License.
