# Experiment Code

## Pre-processing

The [Personal Key Indicators of Heart Disease](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease) dataset contains 320K rows and 18 columns. It is a cleaned, smaller version of the 2020 annual CDC survey data of 400k adults. For each patient (row), it contains the health status of that individual. The data was collected in the form of surveys conducted over the phone.

**Read and Analysis the Data**

- Read the dataset using `pd.read_csv` and save it in `df`.
- Display basic information about the dataset using `df.info()` and `df.describe()`.
- Check for duplicates, null values, and unique values in each column using `df.duplicated().sum()`, `df.isnull().sum()`, and `df.nunique()`.

**Cleaning Data**

- Remove duplicated rows using `df.drop_duplicates()`.
- Solve the imbalance problem in the 'HeartDisease' column using the Random Over Sampler technique.

**Visualization**

- Visualize the data to understand the distribution of features and their relationship with the target variable ('HeartDisease') using seaborn and matplotlib.

**Encoding Categorical Columns**

- Convert categorical columns into numerical representations using label encoding and binning for certain columns.

**Feature Extraction**

- Extract features from existing columns, such as transforming BMI values into categories and mapping age categories.

**Feature Selection**

- Use correlation analysis and SelectFromModel to select relevant features for modeling.

**Machine Learning Algorithm Experimentation**

- Train multiple machine learning models (e.g., Logistic Regression, Random Forest, Decision Tree, K-Nearest Neighbors, Support Vector Machine).
- Evaluate the models' performance using accuracy metrics and confusion matrix.

---

## Results & Analysis

- **Random Forest Classifier** achieved an accuracy of 0.85 in predicting heart disease.
- The confusion matrix shows that the model performed well in predicting both classes (heart disease and no heart disease).

---

**Note**: Add detailed explanations, visualizations, and insights gained from the analysis in this section.

