# Regression_Data_Scientist_Salaries
Metis Regression Module 2 Project 

## ABSTRACT

I used Selenium automated web browsing software to scrape job posting data off Glassdoor.com to determine the features that most impact data scientist salaries in the United States. I cleaned and then modeled the data using a Random Forest Regressor to get an R^2 of .94 and RMSE of 16.7k. After I performed permutation feature importance on the Random Forest model, the feature with the highest impact on Data Science salary came from if an employer provided the salary to Glassdoor.com. Other key features were if a job posting had 'Senior' or 'Data Analyst' in the title, as well as the age of the company.

### Install
 The following libraries are required for this project:
 
  - NumPy
  - Pandas
  - Matplotlib
  - Regex
  - Selenium
  - Scikit-learn

### Data
  - [Glassdoor.com](https://www.glassdoor.com/Job/data-scientist-jobs-SRCH_KO0,14.htm)
