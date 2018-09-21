# Employee Retention/Churn Analysis - Donald Lee-Brown

Originally a mock data challenge completed as part of the [2018B NYC Insight Data Science Fellows Program](https://www.insightdatascience.com/).

Employee churn is a major cost driver at many companies, as the cost of re-hiring and training a new employee can in many cases be higher than the employee's annual salary. Thus, if employee churn can be predicted, companies can either a) better budget for re-hiring expenses and/or b) reduce the impact of the factors that make an employee leave their job.

In this project we are presented with some limited data on employees from several companies. The data include information about the employee's tenure at the company (hire date and leave date), position, salary, and years of experience prior to being hired at the company. The data span the years 2011-2015.

Key questions to answer are:

* What are some key individual factors that influence employee churn? For example, salary, discipline, and experience may all play a role in whether or not a company retains an employee.

* Do company-wide factors play a role in employee churn? For example, perhaps employees at large companies are more likely to leave and pursue other opportunies (or vice versa).

* When does churn occur? Do most dissatisfied employees leave early or do they try and stick around for a few years?

# Conclusion
The goal of this project was to predict employee churn, which is a costly and (ideally) avoidable event at many companies. To this end, a dataset consisting of employee salaries, departments, and seniority levels for several companies was analyzed to search for indicators of churn.

During the course of the data exploration phase, several interesting insights were gathered:

* While the companies had wildly different hiring rates, churn rate was approximately constant across the companies.
Churn rate was also largely constant with respect to department.
* Considering how long employees stay at a company before leaving, many employees leave after just one year of employment, another group tends to leave around the 2 year mark, and comparatively few employees leave after that.
* The deviations of salary level from department averages strongly depended on employee experience level. Counterintuitively, the salary deviations did not predict employee churn.
* There are several patterns in the data that suggest problems with the data collection process - these problems could be masking correlations between the features analyzed and the likelyhood of employee churn.
* Ultimately, the features examined as part of this analysis do not predict employee churn likelyhood. Provided there were not major problems with the data collection process, this would seemingly indicate that employee churn is driven by other factors.

Intuitively, it does seem that there should be a connection between compensation and likelyhood of leaving. However, maybe base salary isn't necessarily a good predictor. In the future, it may be useful to have more information about an employee's compensation history - raises, bonuses, promotions, etc. as these may cause employees who would otherwise leave to stay with a company.
