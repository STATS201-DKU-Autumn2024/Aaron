# README.md

## 1. Overview
This repository contains code for a data science project focused on analyzing game data using natural language processing (NLP) techniques and machine learning models. The primary tasks include:
- Loading and preprocessing datasets.
- Performing sentiment analysis using NLTK.
- Visualizing sentiment results and generating word clouds.
- Training predictive models (e.g., Logistic Regression) and evaluating their performance using metrics like ROC-AUC.

## 2. Files Included
- **Problem Set 2.ipynb**: Main notebook containing the full workflow for data analysis, including:
  - Data loading and preprocessing.
  - NLP-based sentiment analysis and visualization.
  - Model training and evaluation.
- **all_studies_game_data.csv**: Primary dataset used for the project (loaded via URL in the notebook).
- **round_data.csv**: Additional dataset used in the project.

## 3. Prerequisites
### Required Libraries
- Python 3.9+
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- sklearn
- wordcloud

### Installation Instructions
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt


---------
## 4. Usage Instructions
Follow these steps to execute the notebook:

### Load the dataset:
- The datasets are loaded from provided URLs. Ensure internet access or update the paths for local files if necessary.

### Run sentiment analysis:
- Sentiment scores are calculated using NLTK's `SentimentIntensityAnalyzer`.
- Visualize results through bar charts and word clouds.

### Train predictive models:
- Features and target variables are defined in the notebook.
- Logistic Regression is used for classification, with metrics such as classification reports and ROC-AUC.

### Evaluate models:
- Generate and visualize the confusion matrix.
- Plot ROC curves for multi-class predictions.

### Example Command to Run:
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook "Problem Set 2.ipynb"

## 5. Expected Outputs

### Visualizations:
1. **Sentiment Bar Charts**:
   - Displays the distribution of sentiment scores across samples.
2. **Word Clouds**:
   - Positive Sentiment Word Cloud: Highlights frequently used words in positive sentiment texts.
   - Negative Sentiment Word Cloud: Highlights frequently used words in negative sentiment texts.
3. **Confusion Matrix Heatmap**:
   - A visual representation of the performance of the classification model.
4. **ROC Curves**:
   - Multi-class Receiver Operating Characteristic (ROC) curves for model evaluation.

### Metrics:
1. **Classification Report**:
   - Includes metrics such as precision, recall, F1-score, and support for each class.
2. **ROC-AUC Scores**:
   - Area Under the Curve (AUC) values for multi-class predictions.

## 6. Contributors
- **Qianshuo Wang (Aaron)**: Developed the notebook, including data loading, NLP analysis, and predictive modeling.
- **Luyao Zhang**: Provided guidance and evaluation criteria.
