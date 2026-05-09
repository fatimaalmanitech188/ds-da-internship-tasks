 👤 Intern Information
- Name: Fatima Rida Almani
- Internship: Data Science & Data Analytics
- Institution: Shaheed Zulifiqar Ali Bhutto Institude of Science and Technology(SZABIST)


 Task 1: Exploring and Visualizing the Iris Dataset

 Objective
To understand how to read, summarize, and visualize
a dataset using Python.

 Dataset
- Name: Iris Dataset
- Source: Kaggle

Approach
- Loaded dataset using pandas
- Inspected data using .shape, .columns,
  .head(), .dtypes, .describe()
- Created Scatter Plot, Histogram, and Box Plot
  using matplotlib and seaborn

 Results and Insights
- Setosa is clearly separable from other species
  based on petal dimensions
- Virginica has the largest petal size overall
- Versicolor falls between Setosa and Virginica
- Box plot revealed outliers in Sepal Width

Task 2: Credit Risk Prediction

 Objective
Predict whether a loan applicant is likely
to default on a loan.

 Dataset
- Name: Loan Prediction Dataset
- Source: Kaggle

Approach
- Handled missing values using mode and median
- Visualized Loan Amount, Income, Education,
  and Marital Status
- Trained Logistic Regression model
- Evaluated using Accuracy and Confusion Matrix

Results and Insights
- Model Accuracy: ~83.3 %
- Credit history was the strongest predictor
- Married applicants had higher approval rates
- Graduates had higher income but not always
  higher approval


Task 3: Customer Churn Prediction

 Objective
Identify customers who are likely to leave the bank.

 Dataset
- Name: Churn Modelling Dataset
- Source: Kaggle

Approach
- Dropped irrelevant columns
- Label Encoded Gender
- One-Hot Encoded Geography
- Trained Random Forest Classifier
- Analyzed Feature Importance

 Results and Insights
- Model Accuracy: 78.6%
- Age and Balance were top predictors of churn
- Customers from Germany showed higher churn rates
- Active members were less likely to churn


Task 4: Predicting Insurance Claim Amounts 

 Objective
Estimate medical insurance charges based
on personal data.

Dataset
- Name: Medical Cost Personal Dataset
- Source: Kaggle

 Approach
- Encoded sex/gender, smoker, and region columns
- Visualized Age, BMI, and Smoker vs Charges
- Trained Linear Regression model
- Evaluated using MAE and RMSE

 Results and Insights
- Smoker status had the highest impact on charges
- BMI combined with smoking dramatically
  increases charges
- Age has a steady positive correlation
  with charges
- Non-smokers clustered at much lower
  charge amounts


Task 5: Personal Loan Acceptance Prediction

Objective
Predict which customers are likely to accept
a personal loan offer.

 Dataset
- Name: Bank Marketing Dataset
- Source: Kaggle

 Approach
- Explored age, job, marital status features
- Created 6 EDA visualizations
- Trained both Logistic Regression and
  Decision Tree models
- Compared models using ROC Curve and AUC scores
- Extracted business insights from results

 Results and Insights
- Students and retired customers had highest
  acceptance rates
- Single customers accepted more than
  married customers
- Higher account balance linked to
  higher acceptance
- Duration of last contact was strongest
  predictor of acceptance

