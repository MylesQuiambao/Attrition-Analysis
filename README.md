# Attrition-Analysis

# Project Background
The HR department of Salifort Motors wants to know which factors make an employee leave the company. Seeing as it is costly and time-consuming to interview, hire, and train an employee.

In this project, my objectives are to: <br/>

  • Analyze the collected data to uncover patterns associated with employee attrition. <br/>
  • Develop a predictive model that forecasts whether an employee is likely to leave the company.

Once this has been accomplished, the company will be able to pinpoint factors that lead to employee turnover, provide solutions to increase employee retention, and ultimately benefit the company.

For the full exploratory data analysis and model building, you can find the Jupyter Notebook here.

# Executive Summary
It has been observed that employee turnover largely ties in with various management issues within the company.

Critical findings are as follows:

  • There is a noticeable constant increase in the number of employees that leave related to the average monthly hours. Alarmingly, all employees that have worked on 7 projects have left. This may infer that overworking plays a factor in employee turnover rates. <br/>
  
  • The majority of the employees who have stayed only worked on 3-5 projects and worked around the total mean of average monthly hours (200). This may signify a comfortable working setup for retaining employees.
  
![image](https://github.com/user-attachments/assets/74904732-825a-49c5-92a9-bd25259124bf)

  • Employees who have worked ~240-320 average monthly hours are the ones who have the lowest satisfaction levels. These are most likely the employees who have worked on the most projects. <br/>
  
  • Another group of employees that have left can be noticed along the average monthly hours range of ~130-160 which can be possibly identified as employees unmotivated to work enough to reach the mean levels of average monthly hours.

![image](https://github.com/user-attachments/assets/d2a8a908-3607-4b0f-b212-bdc8294b6c74)

  • There is a drop in satisfaction levels from employees with a tenure of 4 years. A deeper investigation into policies or benefits in a 4-year tenure may be suggested as this may be a critical factor for turnover.

![image](https://github.com/user-attachments/assets/2aecd7b9-c1f2-47b7-8536-d187639b7617)

  • The fluctuations of salary levels among levels of tenure don't seem to scale positively. This shows that salary levels don't necessarily increase over time. 

![image](https://github.com/user-attachments/assets/e4cbcf96-39a6-4071-a4f5-d9f9159060f0)

  • Two groups are apparent in the visualization: First are the ones who have overworked and received high evaluation scores and the other are employees who worked lower than average hours and received low evaluation scores. This might give us a sign of a correlation between hours worked and evaluation score.

![image](https://github.com/user-attachments/assets/6012005c-0a5d-4ebb-874e-fdb56d060bd4)

  • A majority of the employees that have left worked at ~280-320 average monthly hours and haven't been promoted within the last 5 years. This is natural as it would be demotivating to stay despite working more hours than average.
  
  • Very few employees who were promoted in the last 5 years have left.

![image](https://github.com/user-attachments/assets/4cdfba74-1e60-4513-b6de-69ac63e2e0f0)

  • The proportions of the number of employees that have left and have stayed seem to be constant across departments. This shows that there are no specific departments affected by the possible factors of turnover.

![image](https://github.com/user-attachments/assets/d6de3c81-a8a3-48b7-af21-1c2ec2931328)

  • This correlation heatmap confirms that the number of projects, monthly hours, and evaluation scores are positively correlated with each other, and satisfaction level is negatively correlated with employee turnover.

![image](https://github.com/user-attachments/assets/13638043-65b8-4d6e-8128-6e242ff51a63)

# Conclusions and recommendations

To retain employees, the following recommendations could be presented to the stakeholders:

* Cap the number of projects that employees can work on.
* Consider promoting employees who have been with the company for at least four years, or conduct further investigation about why four-year tenured employees are so dissatisfied. 
* Either reward employees for working longer hours, or don't require them to do so. 
* If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear. 
* Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts. 
* High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort. 

# Results and Evaluation of the Logistic Regression Model

![image](https://github.com/user-attachments/assets/1d940380-eddc-4506-ab18-076111f9fbda)

The logistic regression model achieved a precision of 80%, recall of 83%, f1-score of 80% (weighted averages), and accuracy of 83%, on the test set.

For the full EDA and Model building, you can view the Jupyter Notebook [here](https://nbviewer.org/github/MylesQuiambao/Attrition-Analysis/blob/main/Attrition-Analysis.ipynb).
