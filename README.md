# Icfes_2019

The following project aims to develop a learning machine model to predict a student's overall score taking some of their socioeconomic conditions as 'features'. The stages of this work are described below:

ETL:The code explores and prepares data from the Colombian Institute for the Evaluation of Education (ICFES). It imports the necessary libraries, reads the data from a CSV file, selects relevant columns, 
handles missing values, performs data manipulation and cleaning, and identifies and removes outliers. The final cleaned dataset is saved as "df_clean.csv" for further exploratory data analysis (EDA).

EDA: The code reads data from a CSV file and performs exploratory data analysis (EDA). It generates histograms for the global scores and visualizes the mean scores by gender, age, and housing stratum using 
grouped bar charts. It also displays a correlation matrix of the selected score variables.


<img src="https://github.com/Pking31/Icfes_2019/blob/main/images/newplot.png" alt="Texto alternativo" width="300" height="200">

ML: The code prepares the data for prediction using a linear regression model. It reads the cleaned data and splits it into features (X) and the target variable (y). The features are encoded to make them suitable for the model. The encoded features are splitted into training and validation sets. The code then trains the linear regression model on the training data and predicts the target variable for the validation set. It evaluates the model's performance using metrics 
like mean absolute error, R-squared, and mean squared error. The code also performs cross-validation and grid search to find the best model parameters. 
