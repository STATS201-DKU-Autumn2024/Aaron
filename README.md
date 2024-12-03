# Final Project: Optimizing Wine Quality Prediction and Consumer Preferences through Adaptive Network Structures and Machine Learning Models

## Author
- **[Qianshuo Wang(Aaron)]**: [Lead Developer, Data Analyst, and Report Author]


## Disclaimer
This project was submitted for **STATS201 Machine Learning for Social Science**, instructed by **Prof. Luyao Zhang** at **Duke Kunshan University** in **Autumn 2024**.

## Acknowledgments
We would like to acknowledge **Prof. Luyao Zhang** for the invaluable guidance throughout the project. Special thanks to our classmates for their insightful feedback, as well as AIGC tools and open-source software that aided the development of our models.
                        **Classmates** for offering collaborative support and exchanging ideas during project development
## Statement of Intellectual and Professional Growth
This project allowed me to expand my understanding of integrating machine learning with real-world applications like wine quality prediction. The process of learning about adaptive networks and consumer behavior has deepened my knowledge of social science and reinforced my technical skills in machine learning. This project is a milestone in my journey to blend data science with practical, industry-relevant challenges.

## Embedded Media
- 
- [Poster Link] (Embed the poster here)

## Table of Contents
1. [Background and Motivation](#background-and-motivation)
2. [Research Questions](#research-questions)
3. [Application Scenario](#application-scenario)
4. [Methodologies](#methodologies)
5. [Results](#results)
6. [Intellectual Merits](#intellectual-merits)
7. [Practical Impacts](#practical-impacts)
8. [AI Governance and Ethical Considerations](#ai-governance-and-ethical-considerations)

## Background and Motivation
- **Gap or Problem**: Wine quality prediction has traditionally relied on chemical properties and expert opinions. However, consumer preferences, which are subjective and influenced by social interactions, have not been sufficiently incorporated into predictive models. Additionally, preferences evolve over time, which presents a challenge for static models.
- **Significance**: This research aims to bridge this gap by incorporating adaptive network structures and machine learning, improving wine quality prediction. By considering how social feedback (e.g., reviews, ratings, expert opinions) influences preferences, this approach offers more personalized wine recommendations. It also highlights the role of social influence in decision-making, which is significant for both the wine industry and machine learning.

## Research Questions
- **How do adaptive network structures, reflecting evolving consumer interactions, enhance the prediction of wine quality and consumer preferences?**
- **Can machine learning algorithms improve the accuracy of wine quality prediction by incorporating dynamic feedback from consumer networks?**

These questions are crucial for understanding consumer behavior, particularly in industries like wine, where opinions evolve and influence purchasing decisions. The integration of adaptive networks and machine learning is a novel approach combining social science with technology.

## Application Scenario
- **Industries/Fields**: Wine industry, consumer preference analysis, machine learning, social network analysis.
- **Dataset Use**: The data includes various wine characteristics (e.g., alcohol content, acidity, pH, etc.) and ratings that can be used to predict wine quality. Integrating social network analysis will also allow the model to account for consumer review patterns and social feedback, offering a more holistic approach to wine quality prediction.

## Methodologies

### Machine Learning Methods:
1. **Prediction**: Supervised learning techniques (e.g., Random Forest, Support Vector Machines, or Neural Networks) will be applied to predict wine quality based on chemical properties and historical ratings.
2. **Adaptive Network**: An adaptive network will be created to represent dynamic social interactions (e.g., how consumer feedback influences each other). This network will evolve as connections between individuals change based on their ratings or interactions, dynamically adjusting predictions to improve accuracy.

### Evaluation:
1. **Confusion Matrix**: To assess classification performance for categorical outcomes like wine quality (e.g., excellent, good, poor).
2. **ROC Curve**: To evaluate the model’s ability to classify wine quality categories based on its predictive power.

### Data Preprocessing:
- Handling missing values, scaling numerical features (e.g., alcohol content, acidity), and encoding categorical variables (e.g., wine category).
- Constructing the adaptive network by linking individuals based on shared reviews or ratings.

### Interpretability and Explainability:
- Using SHAP values to explain the contributions of different features (e.g., alcohol, acidity) to wine quality predictions.
- Visualizing the adaptive network dynamics to understand how feedback influences predictions.

## Results
- **Findings**: The performance of the machine learning model with and without the adaptive network will be summarized, including improvements in prediction accuracy when social network feedback is incorporated.
- **Visualizations**: Confusion matrices and ROC curves will be presented to evaluate the model's performance. Examples will be provided showing how social feedback influenced wine preference predictions across different consumer groups.

## Intellectual Merits
- **Advancement of Existing Literature**: This research extends machine learning models by integrating adaptive network analysis to account for social feedback, a feature not fully explored in previous wine quality prediction studies.
- **Inspiring Future Research Directions**:
   - Exploring adaptive networks in other domains (e.g., movie recommendations, product reviews).
   - Investigating how different network structures (e.g., small-world networks) may affect predictions.

## Practical Impacts
- **Societal or Real-World Benefits**: This research helps wineries and wine retailers understand consumer preferences more accurately, offering personalized wine recommendations and improving customer satisfaction and loyalty.
- **Potential Applications**: The results could inform personalized wine recommendation systems both online and in-store and could contribute to targeted advertising based on evolving consumer preferences.

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

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
