# Predicting house model
# Overview
The report will focus on building a predictive model for USA sales Prices. There is a total of 32 variables, including target variables and Sale price, ranging from different housing features. After understanding different input variables and carrying out data preparation processes, two different models, regression and decision tree models, will be developed and compared together for the most appropriate model.

# Key skills demonstrated
**1. R programming language:** Using R studio with R language to perform data analysis
**2. Data Cleaning and Mining:** Handling missing data, dealing with outliers, and normalizing data. 
**3. Exploratory Data Analysis (EDA):** Identifying trends, patterns, and relationships in data
**4. Predictive analytics:** Building different predictive models, including Regression models and Decision trees, and deciding the best models to predict the house prices

# Table of contents
1. [Project setup](#project-setup)
2. [Project Structure](#project-structure)
3. [How to Run the Project](#how-to-run-the-project)
4. [Key Analysis and Visualisations](#key-analysis-and-visualisation)
5. [Insights and Findings](#insights-and-findings)

# Project setup
To run this project, you will need R Studio to run the code to obtain the desired data and save your data in the correct directory 

# Project structure
1. Dataset: The data to be used during the analytics process
2. Predicting house code: The file includes all the code lines to be used for extracting information from the Cleaning and Mining process to Building and Choosing the appropriate model

# How to run the project 
The project performs in order of 3 following stages
1. Cleaning and Mining:
   * Transform the data to the appropriate format
   * Checking the duplicates and missing values
   * Dealing with skewed data
   * Performing dimension reduction techniques
   * Learning the pattern of the predictor variables and its correlation with the target variable
2. Building models
   * Building 4 regression models to choose the optimal one
   * Building 3 decision tree models to choose the optimal one
3. Choosing the most optimal model
   Compare regression model with decision tree models to decide on the most suitable model for predicting house prices

The code file has been organized according to the above stages. Please access my website via the link to understand a detailed explanation of EDA results and Model clarifications: [Building a predicting model for estimating House value in Boston, USA](https://nrena1997.wixsite.com/analyst-porfolio/post/building-a-predicting-model-for-estimating-house-value-in-boston-usa)

# Key analysis and visualisation
* Evaluation metrics: These are key metrics used in evaluating the model and deciding on the optimal one
</p>

    * Regression models:
<p align="center">
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/Regression_model_comparison.png" width=30% height=40%>
</p>

    * Decision tree:
<p align="center">
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/Decisiontree_comparison.png" width=30% height=40%>
</p>

* Decision tree model demonstration: Different from the regression model, which uses numbers to demonstrate the relationship between predictor and target variables, the decision tree conveys the relationship via pictures.
<p align="center">
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/PartC_Decisiontree_initial.png" width=30% height=40%>
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/PartC_Decisiontree_increaseCP.png" width=30% height=40%>
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/PartC_Decisiontree_decreseCP.png" width=30% height=40%>
</p>

* Regression model demonstration: By sketching the distribution of the predicted variable against the actual variable, we can evaluate the performance of the model
<p align="center">
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/PartC_Regressionmodel_1.png" width=30% height=40%>
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/PartC_Regressionmodel_2.png" width=30% height=40%>
  <img src= "https://github.com/RenaNguyen1997/image/blob/main/Predicting_house/PartC_Regressionmodel_3.png" width=30% height=40%>
</p>
 
For a detailed explanation of these models, kindly visit my website under the sections "Regression models" and " Decision tree models"

# Insights and findings
As observed, the distance between the predicted and actual values generated from the decision tree model is larger than the regression model. The metrics reveal that the regression tree model will perform better at predicting a value that is close to the actual value.

However, considering the previous research and the limitations of the chosen input variables, it is highly recommended that more trials be performed on regression models before concluding and deciding on the model for real-world applications.
