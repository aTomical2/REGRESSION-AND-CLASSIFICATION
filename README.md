# Regression and Classification Analysis

## Overview and Goals

This project investigates regression and classification techniques applied to a structured dataset. The primary focus is to evaluate model complexity, interpretability, and predictive performance for decision trees with varying depths. The analysis is designed to provide actionable insights into the trade-offs between simplicity and predictive power in machine learning models.

## Prerequisites

To run this analysis, the following requirements must be met:
  - Python 3.8+
  - Installed Python libraries: pandas, numpy, matplotlib, seaborn, sklearn

## Steps Taken

  - **Data Preprocessing**: Cleaned and prepared the dataset for analysis.
  - **Exploratory Data Analysis (EDA)**: Performed a visual and statistical examination to understand data distributions and relationships.
  - **Model Implementation**:
    - Trained two decision tree classifiers with max_depth values of 5 and 8, respectively.
    - Evaluated model accuracy and visualised tree structures.

- **Performance Evaluation**: Compared the models in terms of complexity, interpretability, and risk of overfitting.

## Findings

  - Both decision trees achieved an identical accuracy of 89.26% on the testing dataset.
  - The tree with max_depth=5 offers a simpler structure, better interpretability, and reduced computational requirements while maintaining the same predictive accuracy as the more complex tree.
  - The tree with max_depth=8, although more complex, did not exhibit improved performance, highlighting the adequacy of the simpler model for this dataset.

## Conclusion
The tree with max_depth=5 is the preferred model in this analysis due to its balance of simplicity, interpretability, and robust performance. This case study underscores the importance of tailoring model complexity to the dataset's underlying patterns, avoiding unnecessary computational overhead and risk of overfitting.

### **Author**
**Tom Gibson**
