# Investigate-Noshowappointment-Dataset
The noshow appointment dataset contains information of many appointments. The dataset was originally sourced from Kaggle. 
https://www.kaggle.com/joniarroba/noshowappointments/home

This dataset is focused on the question of whether or not patients show up for their appointment and what factors were useful in predicting if patients would miss thier appointments. It contains basic demographic information on the patients as well as whether or not the patient received SMS notifications.

The dataset is managed for unifying names, removing wrong data, adding new features based on existing data. A few observations is also managed regarding age and no_show fields.There are many patients with appointments scheduled and no duplicated rows were found in this dataset.

Most of the patient are at young age and on average are 37 years. 25% of patients are below 18 and most of them are below 55 and the number of patients goes down for patients older than 60 years.There was a small but significant difference in average age between patients who missed their appointments and those who show up.

The distribution of appointments among days of week Monday to Friday is almost equal and none on Sunday.A little bit less visits on Thursday and Friday. Higher percetage of missed appointments are on Saturdays and Fridays which are above 20%.

The analysis identifies that several features were correlated with No Shows. The distributions of show/missed for different categories look similar and most of the patients are not alcoholics, diabetes nor handicapted. 75% of patients recieved appointment SMS but the relationship between SMS received and no shows was contrary to what was expected.

The data should be investigated for future researches with more statistical analysis to reveal new insights and correlations. For example, analyzing how much time passed between a visit scheduling time and the actual visit time could help on investigating the longest wait time and how it is related to no show rate. In addition, the appointment_day has no hour specified, thus it is difficult to analyze if the appointment hour has anything to do with no shows. 
Another example, the demographics such as neighbourhood could have a huge impact of patients missing their appointment.


Statistical Analysis is done by:
Data Wrangling, 
Exploratory Data Analysis, 
Data visualization

Tools
Python Jupyter Notebook

Libraries: numpy, pandas, matplotlib, seaborn
