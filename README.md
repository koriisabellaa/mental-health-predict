# Mental Health in Tech Company Prediction

## Project Overview
---

This is a final project of the Summer Club-Data Science Class presented by Generation Girl, using data from Kaggle - OSMI (https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) and for this project, We pick the survey from 2014.

- Open Sourcing Mental Illness (OSMI) is a non-profit, corporation dedicated to raising awareness, educating, and providing resources to support mental wellness in the tech and open source communities that came out with a new survey to see how employees want to get mental health treatment in tech companies around the world every year.
- Survey is filled by respondents who suffer from mental health disorders (diagnose or un-diagnosed by medical, even it's just a feeling) in tech companies and see if any factors can affect the employee to get treatment or not. 
- Mental health affects your emotional, psychological and social well-being. It affects how we think, feel, and act. It also helps determine how we handle stress, relate to others, and make choices. In the workplace, communication and inclusion are keys skills for successful high performing teams or employees.

---
## Business Understanding 
---
### Problem Statement:
Based on the project review that has been described, here are the details of the problems that can be solved in this project:

1. How is the mental health prediction of employees in technology companies based on data?
2. What are the strongest predictors of mental health illness or certain attitudes towards mental health in the workplace?

### Goal:

1. Assisting HR in determining which factors the company should support in order for the employee to seek mental health treatment.
2. Assisting employees in becoming more concerned about their mental health without self-diagnosis.
___

## Solution Statements
---
We used 3 models to collect data, namely Logistic Regression, Gradient Boosting Classifier, and Gaussian NB, to predict the probability of a categorical dependent variable about mental health in a tech company.

1. Logistic Regression, a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.). In other words, the logistic regression model predicts P(Y=1) as a function of X.
2. Gradient boosting classifiers, a group of machine learning algorithms that combine many weak learning models together to create a strong predictive model. 
3. Gaussian NB, a special type of NB algorithm. It’s specifically used when the features have continuous values. It’s also assumed that all the features are following a gaussian distribution i.e, normal distribution.
---
## Data Understanding
---
Here is the following information from the dataset used in this project:

| Jenis | Keterangan | 
| :----------- | :---------: 
| Sumber | [Kaggle Dataset - Mental Health in Tech Company](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) |
| Lisensi | CC BY-SA 4.0 |

The data used comes from the database of mental health survey results at technology companies, which contains information about the preference data of 1259 users obtained from the survey.csv file:

This dataset contains the following data:

- Timestamp
- Age
- Gender
- Country
- state: If you live in the United States, which state or territory do you live in?
- self_employed: Are you self-employed?
- family_history: Do you have a family history of mental illness?
- treatment: Have you sought treatment for a mental health condition?
- work_interfere: If you have a mental health condition, do you feel that it interferes with your work?
- no_employees: How many employees does your company or organization have?
- remote_work: Do you work remotely (outside of an office) at least 50% of the time?
- tech_company: Is your employer primarily a tech company/organization?
- benefits: Does your employer provide mental health benefits?
- care_options: Do you know the options for mental health care your employer provides?
- wellness_program: Has your employer ever discussed mental health as part of an employee wellness program?
- seek_help: Does your employer provide resources to learn more about mental health issues and how to seek help?
- anonymity: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?
- leave: How easy is it for you to take medical leave for a mental health condition?
- mentalhealthconsequence: Do you think that discussing a mental health issue with your employer would have negative consequences?
- physhealthconsequence: Do you think that discussing a physical health issue with your employer would have negative consequences?
- coworkers: Would you be willing to discuss a mental health issue with your coworkers?
- supervisor: Would you be willing to discuss a mental health issue with your direct supervisor(s)?
- mentalhealthinterview: Would you bring up a mental health issue with a potential employer in an interview?
- physhealthinterview: Would you bring up a physical health issue with a potential employer in an interview?
- mentalvsphysical: Do you feel that your employer takes mental health as seriously as physical health?
- obs_consequence: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?






---
## Modelling and Result
---




---
## Visualization
---







---
## Conclusion Based on EDA 
---

- ### Based on profiling the respondents
  Companies must know that gender and family history greatly influence the decision to get treatment for employees. So if the company wants to provide more support, the company must make an assessment of the employee's personality because different characters can determine different needs.
- ### Based on the work environment of respondents
  Work interference is the most common reason employees want to get treatment. This means the company should consider providing facilities to anticipate job stress on employees. 
- ### Based on the mental health facilities of respondents
  The company needs to provide a good benefit for employees. One of the things that can be done is use third parties who can be hired to maintain a wellness program if the company doesn't have the resources for it. Building trust by keeping information private about which employee gets treatment can also be a trigger for the employee wanting to get treatment.


---
## Conclusion :




