# Wine Quality Prediction Using Machine Learning Models

## Overview

This project uses machine learning techniques to predict wine quality based on several physicochemical features. It explores the use of various models such as **Random Forest**,**SHAP**, **Confusion Matrix** and **XGBoost** to identify the most influential features affecting wine quality and to build an accurate predictive model.

## Code Execution: Steps to Run the Code

To run this project, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/wine-quality-prediction.git
    cd wine-quality-prediction
    ```

2. Install the required dependencies (listed below under **Dependencies**).

3. Execute the Jupyter notebook or Python script:

    - For Jupyter notebook, simply open the `Wine_Quality_Prediction.ipynb` file in Jupyter Lab or Jupyter Notebook.
    
    - For Python script, you can run the script using:
      ```bash
      python wine_quality_prediction.py
      ```

4. Check the outputs in the terminal or view the results in the generated figures and confusion matrix.

## Dependencies

The following libraries are required to run the code:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **scikit-learn**: For implementing machine learning models and evaluation metrics.
- **matplotlib**: For plotting graphs and visualizations.
- **xgboost**: For using the XGBoost model.
- **seaborn**: For statistical data visualization (optional, for advanced plotting).

### Install Required Libraries

To install the required dependencies, you can use a `requirements.txt` file. Here's the content of the `requirements.txt`:

```txt
pandas==1.3.3
numpy==1.21.2
scikit-learn==0.24.2
matplotlib==3.4.3
xgboost==1.4.2
seaborn==0.11.2

