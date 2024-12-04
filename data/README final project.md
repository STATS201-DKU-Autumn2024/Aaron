# Wine Quality Prediction Dataset

## Data Source

The Wine Quality dataset contains information on red and white wine characteristics, which can be used to predict the quality of wine. The data was sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). This dataset was originally contributed by [P. Cortez et al.](https://www.researchgate.net/publication/220650461) for exploring machine learning models to predict wine quality based on physicochemical tests.

The dataset contains 11 physicochemical properties (e.g., pH, alcohol content, acidity levels, etc.) and a quality score assigned by experts. The purpose of the dataset is to enable machine learning algorithms to predict wine quality, which can be used by both consumers and producers to assess and improve wine quality.

## Data Dictionary

| **Feature**                | **Type**        | **Description**                                                                 |
|----------------------------|-----------------|---------------------------------------------------------------------------------|
| **fixed acidity**           | Numeric         | The fixed acidity level of the wine (e.g., tartaric acid).                      |
| **volatile acidity**        | Numeric         | The amount of acetic acid in the wine, affecting its taste and smell.           |
| **citric acid**             | Numeric         | The citric acid content, influencing flavor and preservation.                   |
| **residual sugar**          | Numeric         | The sugar content left in the wine after fermentation.                          |
| **chlorides**               | Numeric         | The chloride level, which can affect the taste and chemical stability.         |
| **free sulfur dioxide**     | Numeric         | The amount of free sulfur dioxide, which acts as a preservative.               |
| **total sulfur dioxide**    | Numeric         | The total sulfur dioxide in the wine, including both free and bound forms.     |
| **density**                 | Numeric         | The density of the wine, a physical property indicating alcohol content.       |
| **pH**                      | Numeric         | The pH level of the wine, affecting its acidity and stability.                 |
| **sulphates**               | Numeric         | The sulphate content, contributing to the taste and preservation of the wine.   |
| **alcohol**                 | Numeric         | The alcohol percentage of the wine, directly affecting taste and body.         |
| **quality**                 | Numeric (1-10)  | The quality rating of the wine, given by experts, on a scale of 1 to 10.        |

## Multiple Data Sources

For this study, we primarily used the Wine Quality dataset sourced from the UCI Machine Learning Repository. This dataset is comprehensive for predicting wine quality based on chemical features. It is a standalone source and does not require other datasets to address the research questions related to wine quality prediction.

However, integrating this dataset with additional datasets (such as consumer preferences or regional wine characteristics) could provide deeper insights. By combining various data sources, one could explore more complex models for wine quality prediction, incorporating not just chemical characteristics but also market preferences and environmental factors influencing wine production.

### Example of Potential Integrations:
1. **Consumer Reviews**: Integrating consumer review datasets (e.g., from platforms like Vivino or Wine Spectator) could provide insights into how quality ratings align with consumer perceptions.
2. **Regional Data**: Including data on wine origin (e.g., grape variety, climate, region) can help model regional variations in wine quality.

Such integrations could enhance the predictive power of machine learning models and provide a broader understanding of what constitutes "quality" in wine.
