# Health-and-Demographic-Patterns-in-South-Africa-HDPSA-Data-Mining

## Overview
This project applies the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology to analyze public health and demographic datasets in South Africa. 

The goal was to identify patterns between healthcare access, sanitation, literacy, nutrition, and mortality rates using data mining and business intelligence techniques.

## Objectives

- Identify high-risk health regions
- Determine predictors of child and maternal mortality
- Analyze relationships between sanitation and disease
- Evaluate impact of immunization and COVID-19 prevention behaviors
- Develop interactive dashboards for decision support

## Datasets Used

- Access to Health Care
- Child Mortality
- HIV Behavior
- Immunization
- Toilet Facilities
- Water
- COVID-19 Prevention
- Maternal Mortality
- Literacy
- ARI Symptoms
- Anthropometry
- IYCF (Infant & Young Child Feeding)

## Methodology – CRISP-DM

### 1. Business Understanding
Defined key health indicators and stakeholder objectives.

### 2. Data Understanding
- Exploratory Data Analysis (EDA)
- Missing value detection
- Outlier analysis
- Correlation analysis
- Initial visualizations in R

### 3. Data Preparation
- Data cleaning
- Feature engineering
- Categorical encoding
- Data merging
- Scaling and normalization

### 4. Modelling

**Clustering**
- K-Means
- Hierarchical Clustering
- Elbow Method

**Classification**
- Logistic Regression
- Decision Trees
- Random Forest

**Association Rules**
- Apriori Algorithm
- Support, Confidence, Lift evaluation

## Model Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Silhouette Score

## Dashboard

Developed interactive dashboards using:
- Power BI
- Region-level filters
- Mortality risk segmentation
- Sanitation coverage visuals

## Tools & Technologies

- R
- R Markdown
- Power BI
- Excel

## Key Insights

- Strong relationship between sanitation access and reduced ARI cases
- Literacy level influences healthcare access behavior
- High-risk clusters identified using clustering techniques
