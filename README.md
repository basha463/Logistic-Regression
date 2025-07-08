# Logistic-Regression
This repository contains a Jupyter Notebook (logireg.ipynb) demonstrating the steps to build, evaluate, and interpret a logistic regression model.
Steps Used in the Process:

1. Import Libraries

Imported necessary Python libraries such as pandas, numpy, matplotlib, seaborn, scikit-learn.

2. Load Dataset

Loaded the dataset into a DataFrame using pandas.

3. Explore Data

Explored data using .head(), .info(), and .describe().

Visualized distributions and relationships with plots.

4. Data Preprocessing

Checked for missing values.

Handled categorical variables using encoding.

Scaled numerical features.

5. Split Data

Split dataset into training and test sets using train_test_split().

6. Model Building

Created a logistic regression model using sklearn.linear_model.LogisticRegression.

Trained the model on training data.

7. Prediction

Made predictions on test data.

8. Model Evaluation

Evaluated model performance using accuracy, confusion matrix, precision, recall, F1-score.

Visualized the ROC curve and calculated AUC.

9. Interpret Results

Interpreted the coefficients and results for business or research insights.
