# Google-Advanced-Data-Analytics-Professional-Certificate-Capstone
# Activity Overview
In this activity, we use Python for model building and data analysis. We deploy different models to analyze a dataset and generate business insights for the stakeholders. In particular, we build and evaluate a logistic regression model and the 2 machine learning models (decision tree and random forest). 

We are a data professional working for Salifort Motors. Currently, there is a high rate of turnover among Salifort employees. (Note: In this context, turnover data includes both employees who choose to quit their job and employees who are let go). Salifort’s senior leadership team is concerned about how many employees are leaving the company. Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees. 

If Salifort could predict whether an employee will leave the company, and discover the reasons behind their departure, they could better understand the problem and develop a solution. 

As a first step, the leadership team asks Human Resources to survey a sample of employees to learn more about what might be driving turnover.  
Next, the leadership team asks to analyze the survey data and come up with ideas for how to increase employee retention. To help with this, they suggest we design a model that predicts whether an employee will leave the company based on their job title, department, number of projects, average monthly hours, and any other relevant data points. A good model will help the company increase retention and job satisfaction for current employees, and save money and time training new employees. 

As a specialist in data analysis, the leadership team leaves it up to us to choose an approach for building the most effective model to predict employee departure. We can will build and evaluate a statistical model such as logistic regression. Also, we will build and evaluate machine learning models such as decision tree, and random forest. 

For any approach, we will need to analyze the key factors driving employee turnover, build an effective model, and share recommendations for next steps with the leadership team. 

The Python notebook for this project includes a guided framework that assists us with the required coding. We input the code in the Python notebook to build and evaluate a logistic regression model and the following machine learning models. 

We will perfom tasks like: 
* Exploratory data analysis (EDA)
* Model building and evaluation 

This project uses a dataset called HR_capstone_dataset.csv. It represents 10 columns of self-reported information from employees of a multinational vehicle manufacturing corporation. 

The dataset contains: 14,999 rows – each row is a different employee’s self-reported information, and 10 columns

| Column name | Type | Description |
| :----- | :----- | :----- |
| satisfaction\_level | int64 | The employee’s self-reported satisfaction level \[0-1\] |
| last\_evaluation | int64 | Score of employee's last performance review \[0–1\] |
| number\_project | int64 | Number of projects employee contributes to |
| average\_monthly\_hours | int64 | Average number of hours employee worked per month |
| time\_spend\_company | int64 | How long the employee has been with the company (years) |
| work\_accident | int64 | Whether or not the employee experienced an accident while at work |
| left | int64 | Whether or not the employee left the company |
| promotion\_last\_5years | int64 | Whether or not the employee was promoted in the last 5 years |
| department | str | The employee's department |
| salary | str | The employee's salary (low, medium, or high) |
