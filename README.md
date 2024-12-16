**Admission Data Analysis using Linear Regression**

> **Overview**

This project involves the analysis of student admission data using linear regression. The goal is to predict the likelihood of admission based on various factors such as GRE scores, TOEFL scores, CGPA, and other related features.

> **Features**

Data Preprocessing: Cleaning and preparing the dataset for analysis.

Exploratory Data Analysis (EDA): Understanding relationships between variables through visualization and statistical analysis.

Linear Regression Modeling: Building and evaluating a regression model to predict admission chances.

Evaluation Metrics: Using metrics like Mean Squared Error (MSE) and R-squared to assess model performance.

> **Dataset**

The dataset contains the following key features:

GRE Score: Graduate Record Examination score.

TOEFL Score: Test of English as a Foreign Language score.

University Rating: Ranking of the university.

Statement of Purpose (SOP): Rating of the applicant’s SOP.

Letter of Recommendation (LOR): Rating of recommendation letters.

CGPA: Undergraduate GPA on a scale of 10.

Research: Binary indicator of whether the student has research experience.

Chance of Admit: Probability of admission.

> **Project Structure**

Data Preprocessing: Handled missing values, outliers, and scaling of features.

Modeling: Built and trained a linear regression model to predict the chance of admission.

Evaluation: Assessed the model using appropriate regression metrics and visualized the predictions against actual values.

> **Requirements**

The project uses the following Python libraries:

numpy

pandas

matplotlib

seaborn

scikit-learn

You can install these dependencies using pip:

pip install numpy pandas matplotlib seaborn scikit-learn


> **Results**

The linear regression model achieved the following results:

Mean Squared Error (MSE): value

R-squared Score: value

The model provides insights into which factors significantly influence admission chances and how they correlate with one another.

> **Visualization**

The notebook includes visualizations to help understand the relationships between features and the target variable. Key plots include:

Correlation heatmap.

Scatter plots of individual features against the chance of admission.
