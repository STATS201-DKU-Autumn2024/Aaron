# Final Project: Optimizing Wine Quality Prediction Using Machine Learning Models

## Author
- **[Qianshuo Wang(Aaron)]**: [Lead Developer, Data Analyst, and Report Author]


## Disclaimer
This project was submitted for **STATS201 Machine Learning for Social Science**, instructed by **Prof. Luyao Zhang** at **Duke Kunshan University** in **Autumn 2024**.

## Acknowledgments
We would like to acknowledge **Prof. Luyao Zhang** for the invaluable guidance throughout the project. Special thanks to our classmates for their insightful feedback, as well as AIGC tools and open-source software that aided the development of our models.
                       
## Statement of Intellectual and Professional Growth
This project allowed me to expand my understanding of integrating machine learning with real-world applications like wine quality prediction. The process of learning about adaptive networks and consumer behavior has deepened my knowledge of social science and reinforced my technical skills in machine learning. This project is a milestone in my journey to blend data science with practical, industry-relevant challenges.

---
## Embedded Media
- [https://github.com/STATS201-DKU-Autumn2024/Aaron/blob/main/data/Poster.png] 
---
## Table of Contents
## Wine Quality Prediction Using Machine Learning

### Table of Contents
1. [Background and Motivation](#background-and-motivation)
2. [Research Questions](#research-questions)
3. [Application Scenario](#application-scenario)
   1. [Industry and Field](#industry-and-field)
   2. [Dataset](#dataset)
      - [Dataset Description](#dataset-description)
      - [Dataset Characteristics](#dataset-characteristics)
      - [Data Preprocessing](#data-preprocessing)
4. [Methodology](#methodology)
   1. [XGBoost](#xgboost)
   2. [SHAP](#shap)
   3. [Confusion Matrix](#confusion-matrix)
5. [Results](#results)
   1. [XGBoost Results](#xgboost-results)
   2. [SHAP Results](#shap-results)
   3. [Confusion Matrix Results](#confusion-matrix-results)
6. [Intellectual Merits](#intellectual-merits)
7. [Practical Impacts](#practical-impacts)

---

### Background and Motivation
Traditionally, wine quality prediction relies heavily on geographical factors, and consumers often believe that wines from certain regions are of higher quality. However, the chemical composition of wine, such as acidity, alcohol content, sugar levels, etc., may have a more direct impact on wine quality. Existing models often overlook this factor, focusing instead on regional advantages as the primary quality indicator. This study aims to challenge the idea that geographical origin is the only determinant of wine quality by using machine learning models to analyze the relationship between the chemical composition of wine and its quality.

### Research Questions
1. Which wine components (such as acidity, alcohol content, sugar levels, etc.) are the most important factors in predicting wine quality?
2. How can we improve the accuracy of wine quality prediction by focusing on chemical composition instead of geographical origin?

### Application Scenario

#### Industry and Field
The dataset used in this study comes from the wine industry, focusing on the chemical compositions of red and white wines and their quality ratings. This application is within food science and beverage industry research, emphasizing predictive analytics for wine quality control.

#### Dataset

##### Dataset Description
This study utilizes a Wine Quality Dataset, which contains multivariate data about various chemical properties of red and white wines. The dataset is designed to support machine learning models focused on wine quality prediction.

##### Dataset Characteristics
- **Data Type**: Multivariate dataset containing chemical compositions of wines along with corresponding quality ratings.

##### Data Preprocessing
- **Missing Values**: The dataset is relatively clean, with minimal missing values. Any missing values, if present, are handled by imputing mean/median values based on the feature distribution.
- **Normalization**: Data features are normalized to ensure consistent scales across all variables, which improves the performance of machine learning algorithms.

### Methodology

#### XGBoost
XGBoost is used in this study to predict wine quality in a multi-class classification task. It is particularly suitable for this problem as it can capture complex, non-linear relationships between features, such as the chemical composition of wine and its quality. XGBoost also offers advantages such as ranking feature importance and efficiently handling missing data.

#### SHAP
This article applies SHAP to determine which ingredients play the most significant role in predicting wine quality by assigning an independent contribution value to each characteristic.

#### Confusion Matrix
A confusion matrix is used in this study to evaluate the classification performance of the machine learning models. Given that we are predicting wine quality (e.g., excellent, good, poor), the confusion matrix will display the number of true positives, true negatives, false positives, and false negatives for each class.

### Results

#### XGBoost Results
From the analysis, the results show that volatile acidity has the greatest impact on wine quality, followed by residual sugar, chlorides, and total sulfur dioxide.

#### SHAP Results
SHAP analysis reveals that volatile acidity has a high impact on red wine quality, while free sulfur dioxide has minimal influence.

#### Confusion Matrix Results
The prediction accuracy is relatively high for quality scores of 7 (Very Good) and 8 (Excellent), but lower for quality scores of 4 (Low Quality) and 5 (Fair).

### Intellectual Merits
This study makes significant contributions to the application of machine learning in the wine industry by identifying key features like volatile acidity, offering a more precise understanding of the chemical factors that influence wine quality.

### Practical Impacts
- **Informed Wine Selection**: Consumers can make more informed choices based on chemical composition, such as choosing wines with optimized volatile acidity.
- **Consumer Preferences and Market Insights**: Winemakers can align their products with consumer preferences, particularly in markets that prioritize specific flavor profiles.
- **Personalized Wine Preferences**: The analysis offers consumers the ability to tailor wine selections based on their taste preferences.

---

## Navigation Instructions

To navigate the repository and locate the following components:

1. **Code for simulations and visualizations**:
   - The main code for running simulations and generating visualizations (e.g., confusion matrices, ROC curves, adaptive network dynamics) is located in the `code/` directory. Inside this folder, you will find the following files:
     - `wine_quality_prediction.ipynb`: Contains the implementation of machine learning models and training pipeline.
     - `visualizations.py`: Generates visualizations like confusion matrices, ROC curves, and adaptive network diagrams.

2. **Datasets and preprocessing steps**:
   - The datasets and related preprocessing scripts can be found in the `data/` directory:
     - `wine_quality.csv`: The primary dataset used for wine quality prediction, which includes features like alcohol content, acidity, pH, etc.
     - `preprocessing.py`: Contains preprocessing steps like handling missing values, feature scaling, and encoding categorical variables.

3. **Documentation and dependencies**:
   - The `docs/` directory contains all the project documentation, including this README file. It provides detailed information about the methodology, results, and conclusions.
   - The `requirements.txt` file lists the dependencies required to run the project, including libraries such as `scikit-learn`, `matplotlib`, `pandas`, and `networkx`.

You can also explore the directory structure to familiarize yourself with the project and its components.

---
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
