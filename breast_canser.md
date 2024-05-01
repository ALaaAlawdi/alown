# Breast Cancer Classifier

This notebook contains the code for a breast cancer classifier using the Wisconsin dataset. The code includes pre-processing, feature extraction, data analysis, and experimentation with machine learning algorithms. 

## Pre-processing

The dataset is imported and pre-processed to handle non-numeric values in the 'Bare Nuclei' column. Non-numeric values are removed, and the column is converted to the 'int64' data type.

## Splitting Data

The data is split into training, validation, and test sets using a 2:1:1 ratio.

## Comparison Between Algorithms

Several machine learning algorithms are compared, including Logistic Regression, Random Forest, Decision Tree, Gradient Boosting, K-Nearest Neighbors, and Support Vector Classifier. Training and testing accuracy, as well as confusion matrices, are printed for each algorithm.

Results:
- Logistic Regression: Training Accuracy - 0.9901, Testing Accuracy - 0.9430
- Random Forest: Training Accuracy - 0.9967, Testing Accuracy - 0.9649
- Decision Tree: Training Accuracy - 1.0, Testing Accuracy - 0.9342
- Gradient Boosting: Training Accuracy - 1.0, Testing Accuracy - 0.9342
- K-Nearest Neighbors: Training Accuracy - 0.9868, Testing Accuracy - 0.9430
- Support Vector Classifier: Training Accuracy - 0.9868, Testing Accuracy - 0.9518

## Training Model by Decision Tree

A Decision Tree classifier is trained with a max depth of 3 and evaluated on the training and validation sets.

## Choosing Best Max_depth

The effect of the max_depth parameter on accuracy is analyzed, and a plot is created to visualize the relationship.

## Model Evaluation

The final model (Decision Tree with max_depth=3) is evaluated on the test set using accuracy, precision, recall, F1 score, and a classification report. A confusion matrix is also plotted to visualize the model's performance.

Results:
- Accuracy: 0.9474
- Precision: 0.8812
- Recall: 1.0
- F1 Score: 0.9368

Classification Report:
              precision    recall  f1-score   support

           2       1.00      0.91      0.95       139
           4       0.88      1.00      0.94        89

    accuracy                           0.95       228
   macro avg       0.94      0.96      0.95       228
weighted avg       0.95      0.95      0.95       228

---

To run the code, follow these steps:

1. Import the dataset.
2. Pre-process the data.
3. Split the data into training, validation, and test sets.
4. Compare different machine learning algorithms.
5. Train the final model.
6. Evaluate the model.

For detailed implementation, refer to the [Jupyter notebook](https://colab.research.google.com/drive/1b19SncjHGlsAr8U0rlYqDpatl2RrH9Gj).

