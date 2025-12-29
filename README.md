# Academic Risk Analysis using Python

## Overview
This project presents an interpretable analysis of academic risk factors among
secondary school students. Instead of focusing solely on prediction accuracy,
the study emphasizes understanding *why* students face academic risk using
clear and explainable indicators.

The analysis is conducted entirely using Python for data exploration,
statistical analysis, and visualization.

---

## Dataset
The project uses the **Student Performance Dataset** from Kaggle, originally
sourced from the UCI Machine Learning Repository.

The dataset contains academic and behavioral attributes of students, including
grades, absences, and failure history.

---

## Research Objective
The objective of this project is to identify interpretable patterns associated
with academic risk and to understand how attendance, failures, and early academic
performance influence final outcomes.

---

## Methodology

### 1. Data Exploration
- Loaded and inspected the dataset for structure and consistency
- Examined statistical summaries to understand distributions

### 2. Academic Risk Definition
Academic risk is defined using a transparent rule-based approach:
- Final grade (G3) < 10  
- OR number of failures ≥ 2  
- OR absences > 15  

This definition prioritizes interpretability over black-box prediction.

### 3. Statistical Analysis
- Correlation analysis between grades, failures, and absences
- Group-wise comparisons between at-risk and non–at-risk students

### 4. Visualization
Reproducible visualizations were generated to support findings:
- Correlation heatmap of academic factors
- Boxplot comparing final grades across risk groups
- Scatter plot showing the impact of absences on final grades

---

## Key Findings
- Absences and academic failures show a strong negative relationship with final grades
- Early academic performance strongly influences final outcomes
- Students classified as at academic risk exhibit significantly lower grade distributions

---

## Visualizations

### Correlation Between Academic Factors
<img src="https://github.com/Ashwini07-cmd/Academic-Risk-Analysis/blob/52e3e477eccfc16a7a4f8ecb88d6dcde731fed7d/Correlation_heatmap.png" width="700"/>

### Final Grade Distribution by Academic Risk
<img src="https://github.com/Ashwini07-cmd/Academic-Risk-Analysis/blob/52e3e477eccfc16a7a4f8ecb88d6dcde731fed7d/grade_vs_risk_boxplot.png" width="700"/>

### Impact of Absences on Final Grade
<img src="https://github.com/Ashwini07-cmd/Academic-Risk-Analysis/blob/52e3e477eccfc16a7a4f8ecb88d6dcde731fed7d/absences_vs_grade.png" width="700"/>

---
## Ethical Considerations
This analysis is intended to support early academic intervention and informed
decision-making. The results should not be used to label or penalize students.

---

## Conclusion
This project demonstrates how explainable, Python-based data analysis can be
used to derive meaningful insights into academic performance. The emphasis on
interpretability, clarity, and ethical awareness aligns with research-oriented
data analysis practices.
