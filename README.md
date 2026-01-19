# house_sales
House Sales Machine Learning Project

**Overview**

This project analyzes historical residential house sales data to identify key factors influencing property prices and to build a predictive model that estimates house prices based on property characteristics. The goal is to support data-driven pricing decisions for real estate stakeholders.

**Business Problem**

Accurate house pricing is challenging due to multiple interacting factors such as property size, location, condition, and age. Mispricing can result in revenue loss or prolonged listing times.

**Objective**

Identify the strongest drivers of house prices

Build a predictive model to estimate house prices

Translate analytical findings into actionable business insights

**Dataset**

The dataset contains historical residential property sales records with features including:

1. Living area (square feet)
2. Number of bedrooms and bathrooms
3. Property condition
4. Location-related attributes
5. Year built

**Tools & Technologies**

1. Python (Pandas, NumPy)
2. Data Visualization (Matplotlib, Seaborn)
3. Scikit-learn
4. SQL (data validation and exploration)

**Methodology**
1. Data Cleaning & Preparation
2. Removed duplicates and handled missing values
3. Treated outliers to reduce skewness
4. Encoded categorical variables
5. Scaled numerical features where required

**Exploratory Data Analysis (EDA)**
1. Analyzed price distribution and variability
2. Identified correlations between house prices and key features
3. Visualized trends using histograms, boxplots, and correlation heatmaps

**Feature Engineering**
1. Created derived features to capture property characteristics
2. Reduced multicollinearity to improve model interpretability

**Modeling**
1. Built a Linear Regression model as a baseline predictor
2. Evaluated performance using RMSE and R² score

**Key Insights**

1. Property size and location are the strongest predictors of house prices
2. Well-maintained and newer houses command higher market values
3. Some features show diminishing returns beyond specific thresholds

**Business Impact**

1. Provides a data-driven framework for residential property pricing
2. Supports real estate agents and investors in pricing strategy decisions
3. Approach can be scaled for rental pricing and market trend analysis

**Future Improvements**
1. Integrate external economic and neighborhood data
2. Evaluate advanced models (Random Forest, Gradient Boosting)
3. Deploy the model as an interactive pricing tool

Evaluate advanced models (Random Forest, Gradient Boosting)

Deploy the model as an interactive pricing tool
