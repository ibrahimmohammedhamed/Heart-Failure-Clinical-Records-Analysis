# Heart-Failure-Clinical-Records-Analysis
Exploratory Data Analysis (EDA) of heart failure clinical records dataset, including data preprocessing, visualization, and correlation analysis using Python.

Objective
The aim of this project is to conduct an exploratory data analysis (EDA) on the Heart Failure Clinical Records dataset using Python libraries such as Pandas, Seaborn, and Matplotlib. The project involves examining various factors related to heart failure and visualizing relationships between different features to gain insights into potential risk factors.

Dataset Information
The dataset used in this analysis contains clinical records of patients with heart failure, including factors such as age, presence of anaemia, creatinine phosphokinase levels, presence of diabetes, ejection fraction, high blood pressure, platelet count, serum creatinine levels, serum sodium levels, sex, smoking status, time, and death event.

Exploratory Data Analysis (EDA) Steps:
Data Preprocessing: The dataset was imported using Pandas and checked for any missing values. No missing values were found.

Descriptive Statistics: Summary statistics such as mean, median, and standard deviation were computed for numerical variables.

Data Visualization: Various visualizations were created to explore relationships between different features and the death event. These include box plots, count plots, scatter plots, kernel density estimation (KDE) plots, pair plots, and bar plots.

Correlation Matrix: A heatmap was generated to visualize the correlation matrix between different features, providing insights into the relationships between variables.

Ensemble Models: Two ensemble models, Random Forest and Gradient Boosting, were trained and evaluated on the dataset.

Random Forest Model
The Random Forest model achieved an accuracy of 75% with the following classification report:
       0       0.72      0.94      0.81        35
       1       0.86      0.48      0.62        25

accuracy                           0.75        60


Gradient Boosting Model

The Gradient Boosting model achieved an accuracy of 73.33% with the following classification report:
       0       0.72      0.89      0.79        35
       1       0.76      0.52      0.62        25

accuracy                           0.73        60



Results
The analysis revealed significant associations between certain features and the occurrence of death events, providing insights into potential risk factors for heart failure.

The correlation matrix heatmap highlighted relationships between different variables, aiding in the identification of key factors influencing heart failure.

Skills
Data preprocessing
Exploratory data analysis (EDA)
Data visualization
Correlation analysis
Statistical analysis

Dataset Sourced from: Kaggle
