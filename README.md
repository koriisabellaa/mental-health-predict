# Mental Health in Tech Company Prediction

## Project Overview


This is a final project of the Summer Club-Data Science Class presented by Generation Girl, using data from Kaggle - OSMI (https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) and for this project, We choose the survey from 2014.

- Open Sourcing Mental Illness (OSMI) is a non-profit, corporation dedicated to raising awareness, educating, and providing resources to support mental wellness in the tech and open source communities that came out with a new survey to see how employees want to get mental health treatment in tech companies around the world every year.
- Survey is filled by respondents who suffer from mental health disorders (diagnose or un-diagnosed by medical, even it's just a feeling) in tech companies and see if any factors can affect the employee to get treatment or not. 
- Mental health affects your emotional, psychological and social well-being. It affects how we think, feel, and act. It also helps determine how we handle stress, relate to others, and make choices. In the workplace, communication and inclusion are keys skills for successful high performing teams or employees.


## Business Understanding 

### Problem Statement:
- Mental health affects emotional, psychological and social well-being. It affects how we think, feel, and act. It also helps determine how we handle stress, relate to others, and make choices. In the workplace, communication and inclusion are keys skills for successful high performing teams or employees.

- Tech workers tend to suffer from mental health disorders more often (diagnosed or undiagnosed by medical, even if it's just a feeling) so it is necessary to see whether there are factors that can influence employees to get treatment or not.


### Goal:

1. Assisting HR in determining which factors the company should support in order for the employee to seek mental health treatment.
2. Assisting employees in becoming more concerned about their mental health without self-diagnosis.


## Solution Statements

We use 3 data classification models, namely Logistic Regression, Gradient Boosting Classifier, and Gaussian NB, to predict the probability of the categorical dependent variable related to mental health in technology companies.

1. Logistic Regression, a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.). In other words, the logistic regression model predicts P(Y=1) as a function of X.
2. Gradient boosting classifiers, a group of machine learning algorithms that combine many weak learning models together to create a strong predictive model. 
3. Gaussian NB, a special type of NB algorithm. It’s specifically used when the features have continuous values. It’s also assumed that all the features are following a gaussian distribution i.e, normal distribution.

## Data Understanding

Here is the following information from the dataset used in this project:

| Jenis | Keterangan | 
| :----------- | :---------: 
| Sumber | [Kaggle Dataset - Mental Health in Tech Company](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) |
| Lisensi | CC BY-SA 4.0 |

The data used comes from the database of mental health survey results at technology companies, which contains information about the preference data of 1259 users obtained from the survey.csv file.

for more information can be checked on (https://docs.google.com/presentation/d/1nhxzp0X_JTG1H8xrkVzalbPCddQm2m4EuJUvcc0kifA/edit?usp=sharing)






