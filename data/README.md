# A brief description of the data source:  
## Data Source Overview
This dataset, comprehensively detailed in [1], provides an extensive collection of data on human behavioral patterns. It includes a variety of sociocultural and economic variables, covering diverse geographic regions over multiple years. Structured for analyses across fields such as behavioral science, economics, and policy-making, this dataset consolidates data from varied sources to enable robust, data-driven insights into trends, anomalies, and causal factors in human behavior.

The data has undergone standardized cleaning and validation procedures to ensure consistency and reliability, making it well-suited for statistical and machine-learning applications. This dataset is especially valuable for comparative studies, supporting models of cross-regional and longitudinal behavior, and providing a foundation for both foundational research and practical applications.

## References
[1] L. K. Son, A. Whillans, J. M. Burrowes, "Human behavior data for research: Description and applications," Nat. Hum. Behav., vol. 8, pp. 1543-1554, Oct. 2024. Available: https://www.nature.com/articles/s41562-024-02024-1.

## Data Dictionary
### Table S1: Dataset Data Dictionary

| Variable Name   | Type   | Definition                                                       | Unit         | Range (Date & Value)                   | Frequency  | Timezone | Sample Observation |
|-----------------|--------|-------------------------------------------------------------------|--------------|----------------------------------------|------------|----------|--------------------|
| Paper_Name      | String | Name of the paper associated with the dataset                     | Text         | N/A                                    | N/A        | N/A      | "Study on XYZ"      |
| Paper_ID        | Integer| Unique identifier for the paper                                   | ID           | 0–1000+                                | N/A        | N/A      | 123                |
| Exp_ID          | Integer| Experiment identifier within the paper                            | ID           | 0–500+                                 | N/A        | N/A      | 45                 |
| Treatment_ID    | Integer| Identifier for specific treatment applied in the experiment       | ID           | 0–500+                                 | N/A        | N/A      | 12                 |
| Measure_ID      | Integer| Identifier for specific measure used in the experiment            | ID           | 0–500+                                 | N/A        | N/A      | 34                 |
| Exp_ID_Cleaned  | String | Cleaned version of experiment identifier for easier interpretation| ID           | 0–500+                                 | N/A        | N/A      | "45_cleaned"        |
| ES_ID           | String | Unique identifier for effect size calculation                     | ID           | 0–500+                                 | N/A        | N/A      | "ES_001"            |
| Title           | String | Title of the specific dataset or experiment                       | Text         | N/A                                    | N/A        | N/A      | "Effect of ABC"    |

This data dictionary provides an overview of the dataset's variables, including detailed descriptions, types, units ranges for each variable.

---
# Problem Set 2
# Project Overview

## Datasets Included

This repository includes the following datasets:

1. **`all_studies_game_data.csv`**  
2. **`all_studies_round_data.csv`**

---

## Dataset Details

### 1. `all_studies_game_data.csv`

**Source and Purpose:**  
This dataset contains detailed information about games played in various studies. It serves as a foundational dataset to analyze patterns in gameplay, user behavior, and study outcomes. The dataset aims to support research in behavioral analysis and experimental gaming setups.

**Preprocessing and Harmonization Steps:**  
- **Data Cleaning:** Missing or incomplete rows were inspected and filled where possible or removed if deemed unnecessary for analysis.  
- **Normalization:** Ensured uniform data formats (e.g., timestamps in ISO format, consistent case for categorical variables).  
- **Deduplication:** Checked for and removed duplicate entries to maintain dataset integrity.  

---

### 2. `all_studies_round_data.csv`

**Source and Purpose:**  
This dataset provides round-by-round data, offering granular insights into each game's progress within the studies. It is complementary to the game-level data, enabling more detailed analysis of intra-game dynamics.

**Preprocessing and Harmonization Steps:**  
- **Data Cleaning:** Addressed outliers and validated field-level consistency.  
- **Index Alignment:** Ensured that round identifiers align correctly with the game identifiers from `all_studies_game_data.csv`.  
- **Feature Engineering:** Added derived fields (e.g., round duration, player actions) to enhance analytical value.  

---

**Poster.pdf**

## Usage Instructions

1. Clone the repository to access the datasets.  
2. Load the datasets using tools such as Python's `pandas` or R's `data.table`.  
3. Apply your analysis pipeline or use the provided preprocessing scripts to prepare the data further.

---

## Notes

- Both datasets are anonymized and do not contain personally identifiable information (PII).  
- For detailed preprocessing scripts and exploratory analysis, refer to the `/code` folder.  


