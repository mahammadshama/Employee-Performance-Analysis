# Employee-Performance-Analysis
This project, conducted as a part of IABAC Certified Data Scientist Certification


---

# Employee Performance Analysis

## Project Overview

This project, conducted for INX Future Inc., aims to analyze employee performance data, identify key factors affecting performance, and provide data-driven recommendations for improvement.   

## Dataset    

Source: HR department of INX Future Inc.     

Size: 1200 records, 28 features    

## Key Features:

Numerical: Age, DistanceFromHome, TrainingTimesLastYear, TotalWorkExperienceInYears, etc.    

Categorical: Gender, JobRole, BusinessTravelFrequency, Attrition, etc.    

Discrete: JobSatisfaction, WorkLifeBalance, PerformanceRating, etc.     



## Data Processing   

Outlier Handling: Capping & log transformation    

Encoding: Label encoding & manual mapping    

Scaling: StandardScaler for continuous variables    

Balancing: SMOTE applied for class imbalance    

Correlation Analysis: Ensured no multicollinearity    


## Exploratory Data Analysis (EDA)    

Univariate Analysis: Histograms, count plots   

Bivariate Analysis: Performance trends across key features    

Multivariate Analysis: Pair plots for feature interactions    


## Model Development

**Algorithms Tested**

Baseline Models: Logistic Regression, LDA, QDA   

Tree-Based Models: Decision Tree, Random Forest, Gradient Boosting, Extra Trees, AdaBoost, CatBoost   

Others: SVM, KNN, MLP Classifier   


## Best-Performing Models

**1. Random Forest Classifier (Final Model)**

Untuned Accuracy: 93.3%   

Tuned Accuracy: 91.6%   



**2. Gradient Boosting Classifier**

Untuned Accuracy: 92.5%   

Tuned Accuracy: 92.5% (Consistent Performance)   




## Key Insights

Department Performance:   

Data Science & Development: Highest ratings   

Finance & Sales: Lowest ratings   


## Top 3 Factors Influencing Performance:

Last Salary Hike Percentage    

Work Environment Satisfaction    

Years Since Last Promotion   



## Recommendations

1. Improve Employee Satisfaction: Recognition programs, better work-life balance    


2. Optimize Performance Management: Regular reviews, clear goals, performance-based incentives   


3. Enhance Workplace Culture: Strong leadership, team-building activities   



By implementing these strategies, INX Future Inc. can improve employee performance while maintaining a positive work environment.    
