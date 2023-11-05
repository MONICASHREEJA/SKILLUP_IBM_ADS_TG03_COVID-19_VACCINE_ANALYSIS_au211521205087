# SKILLUP_IBM_ADS_TG03_COVID-19_VACCINE_ANALYSIS_au211521205087

COVID-19 VACCINATION ANALYSIS[Sentimental Analysis]
This repository consists of documents related to my IBM skillup Project for Applied Data Science domain 
where a kaggle dataset provided has been handled to perform sentimental analysis carried out as 4 working phases 
and 1 Final documentation phase.

PROBLEM DEFINITION:

The goal of this project is to conduct a data-driven analysis of 
COVID-19 data to gain insights into infection rates, vaccination trends, and their impact on healthcare systems. 
This analysis aims to inform decision-making, resource allocation, and public health strategies in the 
multiple insight based decisive battle against the pandemic.

DESIGN THINKING:

1.Data Collection
2.Data Preprocessing
3.Exploratory Data Analysis
4.Statistical Analysis
5.Visualization

*DATA COLLECTION:
Collecting data on COVID-19 vaccinations involves gathering information on various aspects of the vaccination campaign.

*DATA PREPROCESSING:
Data Processing for COVID-19 Analysis involves several key steps to ensure that the data is
cleaned, prepared, and structured for meaningful analysis.

*EXPLORATORY DATA ANALYSIS:
By conducting Exploratory Data Analysis, we gain valuable insights into the COVID-19 pandemic, 
which informs public health strategies and policy decisions.

*STATISTICAL ANALYSIS:
Statistical analysis in COVID-19 involves applying various quantitative techniques to understand 
and draw insights from the data related to the pandemic.

*VISUALIZATION
Visualization aids in communicating COVID-19 trends effectively to inform decision- making and public health strategies.


DATA PREPROCESSING STEPS:

1.Data Cleaning:
Data cleaning process involves removing rows where critical vaccination information was entirely absent -
such as 'total_vaccinations', 'people_vaccinated', and 'people_fully_vaccinated'.

2.Data Integration:
Data Integration technique involves merging two datasets like we merged vaccination records and 
vaccine manufacturer information—based on the common field 'total_vaccinations'.

3.Data Transformation
Data Transformation process involves transforming data like 
we replaced any missing values in the DataFrame with zeros using df.fillna(0, inplace=True).
This ensures that missing data doesn't affect our analysis.

MODEL TRAINING:

LINEAR REGRESSION
We are training the model using the linear regression technique to predict the vaccinations rate
by the number of vaccinations obtained  in certain days.
If the coefficient is positive, it means that as the number of days increases,
the total vaccinations are expected to increase as well.

MODEL EVALUATION:

●Model evaluation is the process of assessing the performance and effectiveness of a machine learning model.

●In Model Evaluation, we calculate three important metrics. These metrics help to assess how well the model is performing 
in terms of predicting the total vaccinations based on the number of days since the start date:
     1.Root Mean Squared Error (RMSE): This measures the average error between predicted and actual values,
     with higher values indicating greater deviation.
     2.Mean Absolute Error (MAE): It computes the average absolute difference between predicted and actual values,
     providing another perspective on the model's performance.
     3.R-squared (R2) Score: This metric assesses how well the model's predictions align with the actual data.
     An R2 score of 1 indicates a perfect fit.

CONCLUSION:

The Covid-19 Vaccine dataset with various fields has been successfully  analyzed , preprocessed and 
multiple forms of evaluative insights using various techniques have been withdrawn to arrive at the 
final project completion to improve the vaccination implementation across the world.
