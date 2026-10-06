# Data Mining and Machine Learning: Income & Voting Demographics Analysis

## Project Overview
This repository contains a comprehensive data-mining pipeline and exploratory analysis examining socioeconomic factors, income distributions, and their potential relationship with political voting demographics across the United States. 

## Key Objectives & Research Questions
The project explores the following primary research questions and core evaluation areas:

* **Fairness & Demographic Impact on Income:** 
  * *Question:* How do personal demographics (such as sex, race, and place of birth) affect income distribution and financial outcomes?
* **Personal and Professional Drivers:** 
  * *Question:* What are the primary personal and professional drivers (such as age, education level, and hours worked) influencing individual earning potential?
* **Income Bracket Prediction:** 
  * *Question:* Can we accurately classify and predict whether an individual falls into a high or low-income bracket using machine learning models based on professional and personal attributes?
* **Geospatial Voting Demographics:** 
  * *Question:* How do state-level election results correlate with regional income averages, educational attainment, and demographic breakdowns?
* **Custom Hypothesis (Data Mining):** 
  * *Overview:* Investigates whether wealth in Democratic-leaning states is more strongly knowledge-oriented and correlated with education (white-collar work), whereas wealth in Republican-leaning states is more strongly correlated with hours worked or blue-collar sectors.

## Key Scope & Methodology
* **Data Preprocessing & Cleansing:** Managing missing values, identifying outliers, grouping high-cardinality categorical variables (such as education checkpoints, industry sectors, and racial demographics), and applying logarithmic transformations to handle skewed financial data.
* **Predictive Modelling:** Training and evaluating multiple machine learning classifiers (including Logistic Regression, Random Forest, Naive Bayes, and Neural Networks) for both income brackets and voting trend analysis.
* **Model Explainability:** Leveraging feature ranking and SHAP (SHapley Additive exPlanations) values to interpret global feature importance and local prediction influences.

## Repository Structure
* `chapters/`: Contains modular scripts and workflow components.
* `F331073 Data-Mining Report.pdf`: The complete written project report.
* `README.md`: Project documentation and scope overview.

## Tools & Frameworks
* Built using data-mining workflows and Python scripts for data transformation, statistical testing, and predictive modelling.
