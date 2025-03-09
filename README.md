# CaseStudy1DDS: Frito Lay Employee Attrition Analysis
**Setting:** We have been hired by Frito Lay to identify factors related to employee attrition.
## Question of Interest
What are the key factors contributing to employee attrition (turnover), and how effectively can we predict attrition using these factors?

## Key Factors Related to Attrition
The following factors were identified as the strongest predictors of attrition:
#### **Primary Factors**
1. Job Role
2. Age
3. Over Time
#### **Additional Influential Factors**
1. Job Level
2. Years In Current Role
3. Monthly Income

## Model Performance Summary
To predict attrition, we used **Naïve Bayes** and **k-Nearest Neighbors (kNN)** models averaging over many iterations for stronger results.
#### **Naïve Bayes Model (100 Iterations)**
- **Classification Threshold:** 0.12
- **Accuracy:** 64.60%
- **Sensitivity:** 77.86%
- **Specificity:** 62.05%
#### **k-Nearest Neighbors Model (100 Iterations, k = 3)**
- **Classification Threshold:** 0.15
- **Accuracy:** 72.76%
- **Sensitivity:** 94.29%
- **Specificity:** 68.63%

##  Additional Insights
- Job Level and Years in Current Role emerged as interesting factors, particularly seeing high-turnover in Job Levels 1 and 2. 
- Younger employees in Sales roles exhibited higher attrition rates, suggesting a potential retention challenge for some job roles.
- Employees working Over Time were more likely to leave, highlighting a possible issue with working too many hours.

## Helpful Links
- You can view a pdf link to my presenation [here](https://drive.google.com/file/d/1Tnj-58S58GQHO5TJ7wKfBoArqnQEkKkX/view?usp=share_link)
- You can view the Youtube presentation [here](https://youtu.be/fbEB-BOKmEQ?si=DlVtoCAYSkMfcsN8)
- You can view the knitted document or additional results [here](http://rpubs.com/chloedbarker/1282353)
