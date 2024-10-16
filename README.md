# Diabetes-Risk-Predictor
Predicted diabetes risk by applying Scikit-learn’s logistic regression, decision tree, and random forest models, achieving up to 95% accuracy by analyzing key health features such as age, BMI, and Hemoglobin A1C levels. Engineered features by data wrangling, encoding categorical variables, and StandardScaler preprocessing. Merged and split data into training, testing, and holdout subsets, implementing 5-fold cross-validation. Computed demographics classification reports and confusion matrices, visualizing using Seaborn heat maps.

We acquired our dataset, diabetes_prediction_dataset.csv, from Kaggle. Our dataset initially contained 100,000 rows, but after cleaning and processing the data for the regression, the dataset was filtered down to 64,172 rows. The dataset is composed of individual cases with patient’s gender, age, presence of hypertension (yes or no), presence of heart disease (yes or no), patient’s smoking history (former, current, never, etc.), patient’s body mass index (bmi), Hb1Ac level (the average blood glucose levels for the last 2 or 3 months), current blood glucose level, and the actual presence of diabetes (yes or no).

For this project, we identified three research questions that we were curious to answer:

Can any of the features above (excluding the diabetes column, of course) predict the presence of diabetes?
Does being a specific gender increase the chance of being diabetic?
Which of the features above contributes most to predicting the presence of diabetes?
In conducting our regression, we aimed to examine the relationship between the aforementioned features (gender, age, hypertension, etc.) and the presence of diabetes, which became our target outcome. We further split the data based on demographic categories, such as gender and age brackets, and conducted the regression again with them as features to analyze their impact on the presence of diabetes. Finally, we conducted an analysis on the accuracy of our regression models, determining how well the model predicted whether an individual would have diabetes or not using the features given.
