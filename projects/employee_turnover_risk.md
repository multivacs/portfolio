## Employee Turnover Risk

**Project description:** The goal of this project is to create a system that using Machine Learning algorithm, calculates the risk of an employee to leave the company.

### 1. Business Analytics

First, we made a brief analysis of the data to identify the state of the company at this very moment, quantify the problem, and generate insights that help us to understand the problem.
If we see the data, there is a 16% of turnover rate, and if we make an analysis to try to identify the mean profile that leaves the company, we can see that employees with:

- With no universitarian studies
- Single
- Belongs to the sales department
- Low salary
- Makes more hours

are in more risk to leave.

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" src="images/employee_turnover_risk/ba_1.png?raw=true">  blah |  <img width="1604" src="images/employee_turnover_risk/ba_2.png?raw=true">|<img width="1604" src="images/employee_turnover_risk/ba_3.png?raw=true">|


Also, we calculated the Cost of Turnover using data from the Center for American Progress that estimates that:
- Salary below 30.000$ is 16,1% of the salary.
- Between 30.000$ and 50.000$ is 19,7%.
- Between 50.000$ and 75.000$ is 20,4%.
- More than 75.000$ is 21%.

From the actual data, in the previous year the cost of turnover from employees that have left the company are estimated in 2.7M

If we apply make a campaign to retain the talent in the Sales Department, with a reduction of the 30% of the turnover rate, we can save the company around 37.000$


### 2. Machine Learning

After we have identify the problem and visualize the possible solutions, we decide to make a machine learning algorith, using decision trees to predict, in base of the historical data of the company, which is the risk of an employee, with certain profile, leaves the company.

We use decision trees because its explainability, that makes much more easy to communicate the possible solutions to apply, and why an employee is not satisfied in the company.

<img src="images/employee_turnover_risk/ml.png?raw=true"/>
<img src="images/employee_turnover_risk/ml_2.png?raw=true"/>


### 3. Deployment with Tableau

Finally, we put all the output in the form of a dasboard using Tableau Public.
The Dashboard is interactive, and it's available in the link [Dashboard Turnover Risk](https://public.tableau.com/views/DashboardRiesgoFuga/Dashboard1?:language=es-ES&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

<img src="images/employee_turnover_risk/Dashboard.png?raw=true"/>
