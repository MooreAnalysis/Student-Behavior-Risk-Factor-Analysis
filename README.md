# Behavior-Risk-Factor-Analysis

![R](https://img.shields.io/badge/R-Data%20Analysis-blue)
![Healthcare Analytics](https://img.shields.io/badge/Domain-Healthcare-red)

Poor mental health days were selected as the primary variable of interest due to the growing public health focus on mental health and its relationship to overall quality of life, productivity, and long-term health outcomes. By analyzing behavioral and demographic factors associated with poor mental health days, this project aims to identify trends that may contribute to improved prevention and intervention efforts. My personal commitment to mental health awareness also influenced the decision to explore this topic using the CDC BRFSS 2021 dataset. 

# Dataset
- CDC 2021 BRFSS public health survey dataset containing large-scale demographic, behavioral, and health-related data from U.S. adults for statistical and exploratory analysis. 
- The ages of the participants in the study are 18 years old and older. 
# Key Insights
- Employment status has more of an impact on the number of reported poor mental health days than education level
-  Unemployed individuals who are unable to work report about 6 more poor mental health days than wage employees.
- State unemployment offices should provide access to digial mental health resources or offer free counseling to unemployed individuals
-  Students report about 3 more poor mental health days than wage employees.
-  Schools should deploy and promote mental health resources such as peer-led clinics. 
-  Retired individuals report approximately 2 less poor mental health days than wage employees. 
  
# New Challenges
- Determining whether missing data should be removed or imputed based on its impact on data quality and analytical accuracy. 
- Interpreting the CDC codebooks

# If I had more time
- Add residual plots and influence diagnostics to better evaluate practical effect sizes and identify model limitations. 
- Analyze geographic differences between mental health days and chronic health conditions

# Data Preparation
- Create a new dataframe, from the original dataset, to include only the response variable and predictor variables
- Rename variables to improve interpretability for analysis and visualizations
- RReplace NAs with imputed values using the mean
- Convert categorical variables to factors with labels to prepare for regression analysis

# Analytical Techniques
- Exploratory visualization using ggplot() histograms, multivariable boxplots
- Descriptive statistics
- Grouped mean/standard deviation comparisons
- Bivariate analysis
- Regression analysis

# Diagnostic Analysis
- Distribution comparison before and after imputation 
- Outlier detection
- Model fit assessment

# Data Visualization
- Histograms, boxplots, ordered bar chart
  
# Skills
- R Programming
- dplyr library
- tidyverse library
- car library
- psych library
- Model Evaluation
- Prediction Models
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Regression Analysis
- Data Visualization
- Residual & Influence Diagnostics
- Survey Data Analysis
- Descriptive Statistics

