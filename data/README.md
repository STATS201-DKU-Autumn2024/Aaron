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
