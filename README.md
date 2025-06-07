# Google-Advanced-Analytics-Capstone
Predicting Employee Attrition Using Random Forest Feature Importance
# Overview - Define
The goal of this project was to *build a predictive model* using EDA techniques and Random Forest Model to *identify which employees were likely to leave Salifort Motors*. The project utilized internal HR and survey data to determine the most influential factors behind employee attrition. The final model achieved strong performance, highlighting employee satisfaction, tenure, and workload as the top predictors of turnover. These insights can help leadership at Salifort Motors proactively address retention risks and improve employee engagement strategies.

The code for this Project can be found here, or accessed in the GitHub Repository

# Method 
The dataset provided contains 14,999 rows with employees’ self-reported information. It contains 10 columns featuring data on satisfaction levels, time spent with company, promotions, department, salary and left. The full dataset can be found on [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction), however it has been repurposed by Google for this project. 
![image](https://github.com/user-attachments/assets/de342ab0-eeeb-474a-ba44-8c3704a5daa8)


# Analyze 
EDA was conducted fully within Python. This section will highlight the most important insights gathered during the data exploration phase. 

1.**Correlation Heatmap**

A Correlation Heatmap was made to identify which features should be investigated. By creating the heatmap, we understand that Last Evaluation, Number of Projects, Average Monthly Hours, and Satisfaction level all potentially correlate with employees leaving the company. 

![image](https://github.com/user-attachments/assets/fe0c6a87-6640-4924-9b95-12affa2a99a1)

2. *Monthly Hours compared to Number of Projects*
