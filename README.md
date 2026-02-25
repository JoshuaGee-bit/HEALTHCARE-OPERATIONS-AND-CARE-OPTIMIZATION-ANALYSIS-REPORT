# HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT

## Project Overview
This report aims to evaluates provider workload and patient demand to optimize care delivery, understand operational strain points and recommend operational improvements. 

## Table of Content
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Tasks](#tasks)
- [Deliverables](#deliverables)
- [Datasets](#datasets)
- [Methodology](#Methodology)
- [Answer to Questions](#answer-to-questions)
- [Recommendations](summary-and-recommendations)

## Tools Used
- Microsoft Power BI
  
- Microsoft Excel

## Tasks
1.	Analyze patient load per provider
2.	Identify overburdened specialties
3.	Link health risk to care demand
4.	Visualize provider utilization
5.	Recommend optimization strategies

## Deliverables 
●	Provider utilization dashboard
●	Operational insights report
●	Optimization recommendations

## 1.	Clean datasets
I copied the patients, consultations, vitals, provider and providers assignment dataset from the link provided https://docs.google.com/document/d/1WRah5zfdE4vy5bz3XOFIBx_0YjWxtL_BYkmxKOBxSmo/edit?usp=sharing and pasted it on Microsoft Excel worksheet, after which I saved the documents. Then I opened my Microsoft Power BI to get the above datasets I saved from Ms. Excel, it loaded to the power query where I was able to clean, transform the datasets.

## Datasets
![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Patient's%20Table.jpg)
![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Consultation%20Table.jpg)
![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Vitals%20Table.jpg)
![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Provider%20table.jpg)
![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Provider%20Assignment%20Table.jpg)


## Operational Insight Report
![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Healthcare%20Operations%26Care%20Optimization%20Analysis.jpg)

**2.	To Analyze patient load per provider.**
I created a measure and used the Dax formular below to get the patient load then I created a visual bar chart. Patient Load by Provider ID across Specialty. This is shown in the above Dashboard. It can be deduced that each provider has the same number of patient load which is 2 patients each.

![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Patient%20Load%20Measure.jpg)

**3. Overburdened Specialty**
The overburdened specialty is Endocrinology (D02) with more than two (2) consultations and has the highest number of patients. I created a measure for total consultation then a visual with Total consultation by specialty. The chart can be seen on the above dashboard.

![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/Total%20Consultation.jpg)

**4.	For the health risk to care demand**
I created a measure to count the number of patients with high risk and created a risk level vs consultation chart and it was deduced that we had six (6) high risk patients and 1 low risk patient. High-risk patients account for most consultations, which drives operational strain. This chart can be seen in the dashboard above. High risk patients increase demand 

![image alt](https://github.com/JoshuaGee-bit/HEALTHCARE-OPERATIONS-AND-CARE-OPTIMIZATION-ANALYSIS-REPORT/blob/main/High%20Risk%20care%20Demand.jpg)

**5.	Provider Utilization**
It is embedded in the above dashboard, I created tables containing Provider Id, Specialty, Patient load, total consultations and high-risk patients. I also created a column chart with Provider utilization and Provider ID

![image alt]()

![image alt]
