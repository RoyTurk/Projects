# Machine Learning - Coronary Heart Disease Predictions 🤕

- **Category:** Machine Learning
- **Course:** Machine Learning (CS-433)
- **Date:** Fall 2024
- **Language:** English

---

## 📌 Overview

The project focused on developing a **logistic regression model**
to predict the likelihood of **coronary heart disease** (CHD).
Given a dataset with **over 300 features**, the challenge was to
effectively pre-process the data and implement the model without
relying on standard machine learning libraries.

The workflow included:

- **Data Pre-processing:** Cleaning the dataset, handling missing
values, and applying feature selection to retain only the most 
relevant predictors.
- **Feature Engineering:** Identifying key medical indicators and
reducing dimensionality to improve model performance.
- **Logistic Regression Implementation:** Writing the entire 
model from scratch, including the cost function, gradient descent
optimization, and decision threshold for classification.

#

## 🛠️ Tools Used

- **Programming Language:** Python
- **IDE:** Visual Studio Code, Jupyter Notebook

#

## 📂 Project Contents

### Scripts and Files

- **`run.py`** Main script to generate predictions and save them in `y_test.csv`.
- **`implementations.py`** Contains core model functions used in `run.py`.
- **`functions.py`** Supplementary utility functions.
- **`y_test.csv`** Output file with predictions generated by the model.
- **`types.csv`** CSV file summarizing feature filtering:
	- Row 1: Feature names.
	- Row 2: Feature types (1: continuous, 2: categorical, 3: ordinal).
	- Row 3: Binary indicators (1: kept, 0: removed).
- **`Dataset.zip`** Compressed dataset used for training and evaluation.
- **`CS433_Final_Report.pdf`** Comprehensive project report detailing methods, implementation, and results.

### Feature Selection

- **Variance Thresholding:** Removed low-variance features to reduce redundancy.
- **Mean-Difference Filtering:** Eliminated features with minimal discriminatory power.
- **Correlation Analysis:** Identified and removed highly interdependent features.

#

## 📄 Results

- **Evaluation Metrics**:
	- **F1 Score**: 0.439 (balanced precision and recall for imbalanced data).
	- **Accuracy**: 0.875 (overall effectiveness of predictions).

These metrics were evaluated through the AI Crowd competition platform, where the team (Pandas) ranked **42nd out of 320 submissions**.

[View the leaderboard](https://www.aicrowd.com/challenges/epfl-machine-learning-project-1/leaderboards)

#

## 👷‍♂️ Project Members

- Ali Elkilesly
- Selim Sherif
- Roy Turk

#
