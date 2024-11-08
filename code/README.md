# Human Behavioral Patterns Dataset Exploration and Analysis

Welcome to the Human Behavioral Patterns Dataset Exploration and Analysis project! This repository contains a comprehensive examination of human and AI performance across various experiments and conditions, aiming to uncover insights into human-AI interaction, performance differences, and potential synergies in decision-making tasks.

## Dataset Overview

The dataset comprises behavioral data from multiple experiments, capturing key features such as:

- Experiment identifiers (Paper_ID, Exp_ID, Treatment_ID)
- Performance metrics for humans, AI, and human-AI collaboration
- Number of participants and experiments
- Temporal information (Year of study)
- Statistical measures (means, standard deviations)

## Key Findings

### 1. Performance Comparison
- On average, humans outperformed AI systems in the measured tasks.
- There is significant variability in performance across experiments for both humans and AI.

### 2. Experiment Distribution
- The number of experiments per study varies widely, ranging from 5 to 1675.
- Most studies involve a moderate number of participants, with median values around 40.

### 3. Temporal Trends
- The dataset covers studies from 2020 to 2023, with a concentration in 2021-2022.

## Visualizations

### Example: Heatmap of Correlation Between Variables

Below is an example heatmap that shows the correlation between different variables in the dataset such as human performance, AI performance, and human-AI collaboration.

![Correlation Heatmap of Performance Metrics](https://pplx-res.cloudinary.com/image/upload/v1730955000/user_uploads/rmjzmwtmw/Jie-Ping-2024-11-07-Xia-Wu-12.47.04.jpg)

This heatmap helps us understand how different variables are correlated:
- Darker colors indicate stronger correlations.
- Lighter colors suggest weaker or no correlations between variables.

## Dataset Description

The human behavioral patterns dataset provides performance measurements for humans, AI systems, and their collaboration across various tasks and experiments. Each experiment's data is represented as a separate column with rows representing different metrics. This dataset enables analysis of performance patterns both temporal (across years) and task-specific.

| **Variable**        | **Description**                                  |
|---------------------|--------------------------------------------------|
| Date/Time           | Hourly timestamp for each measurement            |
| Human_Performance   | Performance score for human participants         |
| AI_Performance      | Performance score for AI systems                 |
| HumanAI_Performance | Performance score for human-AI collaboration     |

For more detailed information, please refer to the dataset documentation.
