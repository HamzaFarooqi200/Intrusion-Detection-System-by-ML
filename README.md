# Intrusion-Detection-System-by-ML
# Network Intrusion Detection System (NIDS) using Machine Learning

## Overview

This repository contains a Jupyter Notebook (`main.ipynb`) that demonstrates the implementation of a Network Intrusion Detection System (NIDS) using machine learning. The NIDS is trained on the KDD Cup 1999 dataset, a widely used dataset for intrusion detection research.

The notebook covers the following key aspects:

- **Data Loading and Exploration:** The dataset is loaded and explored to understand its structure and features.

- **Data Preprocessing:** Initial preprocessing steps are performed, including handling missing values and exploring categorical features.

- **Data Visualization:** Visualizations are created to understand the distribution of categorical features and the target variable.

- **Data Correlation:** Correlation analysis is conducted, and highly correlated features are identified and removed.

- **Feature Mapping:** Categorical features such as `protocol_type` and `flag` are mapped to numerical values.

- **Modeling**: The notebook employs four different machine learning models:
  - Gaussian Naive Bayes
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)

- **Model Evaluation:** The performance of each model is evaluated using training and testing accuracy. The notebook also includes visualizations of training time, testing time, training accuracy, and testing accuracy for each model.

- **Predicted Attack Types:** The notebook provides insights into the predicted attack types for a subset of test data for each model.

## Files

- `main.ipynb`: Jupyter Notebook containing the code for data analysis, preprocessing, modeling, and evaluation.
- `training_attack_types`: File containing information about attack types used for mapping.

## How to Use

To run the notebook locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/HamzaFarooqi200/your-repository.git
   cd your-repository
   ```

2. Open the `main.ipynb` notebook in a Jupyter environment (e.g., Jupyter Notebook, Google Colab).

3. Execute the cells in the notebook sequentially to analyze the data, preprocess it, train models, and evaluate their performance.

## Dependencies

The notebook uses the following Python libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Make sure to install these dependencies before running the notebook.

## Note

- The dataset used in this notebook is the KDD Cup 1999 dataset, and the code assumes the presence of the file `kddcup.data_10_percent.gz` in the same directory.

- The notebook includes visualizations and performance metrics for each model, allowing users to compare the results of different machine learning algorithms.

- Feel free to customize the code, explore additional models, or use different datasets for further experimentation.

For any questions or issues, please contact [hamzafarooqi2004@gmail.com].

---
