# Data Science Experiment: Pre-processing, Feature Extraction, Data Analysis, and Machine Learning

## Description
This project aims to demonstrate the process of a data science experiment, including pre-processing, feature extraction, data analysis, and machine learning algorithm experimentation. The dataset used in this experiment is related to education data.

## Pre-processing
The dataset is loaded from Google Drive and checked for missing values. Missing values are handled by either dropping rows or filling them with the mean of the column. Categorical features are converted into numerical ones using one-hot encoding.

## Feature Extraction
No specific feature extraction techniques are mentioned in the provided code. It seems the focus is more on data cleaning and preprocessing.

## Data Analysis
Exploratory Data Analysis (EDA) is performed using seaborn and matplotlib to visualize the data distribution and relationships between variables. This includes count plots, histograms, and scatter plots to understand the data better.

## Machine Learning Algorithm Experimentation
A Logistic Regression model is trained using the pre-processed data. The model is evaluated using a confusion matrix, accuracy score, and classification report.

## Results & Analysis
- **Pre-processing:** The dataset is cleaned, missing values are handled, and categorical features are converted into numerical ones.
- **Feature Extraction:** No specific feature extraction techniques are mentioned.
- **Data Analysis:** EDA reveals insights into the data distribution and relationships between variables.
- **Machine Learning:** The Logistic Regression model achieves a certain level of accuracy in predicting the target variable.
Results & Analysis

- **KNeighbors Classifier:**
  - Accuracy: 0.8377
  - Precision, Recall, F1-score:
    - False: Precision: 0.86, Recall: 0.85, F1-score: 0.85
    - True: Precision: 0.81, Recall: 0.82, F1-score: 0.82
  - Confusion Matrix:
    ```
    [[73 13]
     [12 56]]
    ```

- **Random Forest Classifier:**
  - Accuracy: 1.0
  - Precision, Recall, F1-score:
    - False: Precision: 1.0, Recall: 1.0, F1-score: 1.0
    - True: Precision: 1.0, Recall: 1.0, F1-score: 1.0
  - Confusion Matrix:
    ```
    [[86  0]
     [ 0 68]]
    ```

- **Decision Tree Classifier:**
  - Accuracy: 1.0
  - Precision, Recall, F1-score:
    - False: Precision: 1.0, Recall: 1.0, F1-score: 1.0
    - True: Precision: 1.0, Recall: 1.0, F1-score: 1.0
  - Confusion Matrix:
    ```
    [[86  0]
     [ 0 68]]
    ```

- **Support Vector Machine (SVM):**
  - Accuracy: 0.9935
  - Precision, Recall, F1-score:
    - False: Precision: 1.0, Recall: 0.99, F1-score: 0.99
    - True: Precision: 0.99, Recall: 1.0, F1-score: 0.99
  - Confusion Matrix:
    ```
    [[85  1]
     [ 0 68]]
    ```

- **Logistic Regression:**
  - Accuracy: 1.0
  - Precision, Recall, F1-score:
    - False: Precision: 1.0, Recall: 1.0, F1-score: 1.0
    - True: Precision: 1.0, Recall: 1.0, F1-score: 1.0
  - Confusion Matrix:
    ```
    [[86  0]
     [ 0 68]]
    ```

These results indicate that all models perform very well on the dataset, with high accuracy and F1-scores. The decision tree, random forest, and logistic regression models achieve perfect accuracy, indicating a good fit to the data. Further analysis could focus on comparing these models' performance on different metrics and exploring feature importance for better model interpretability.

## Conclusion
This experiment demonstrates the steps involved in a typical data science project, from data cleaning and preprocessing to model building and evaluation. Further enhancements could include more advanced feature extraction techniques and experimenting with other machine learning algorithms for comparison.

## Future Work
In future iterations of this project, additional features could be explored, and more sophisticated models could be trained to improve prediction accuracy.
