# COVID-19 Big Data Project

### Deliverable 1
---

### 1. Team

#### Project Group # 6

 *a)  Member*

Kevin Talbert

 *b)  Communication plan to include project artifact repository, meeting notes, meeting platform, etc.*

Github Repo, Email communication


### 2. Selection of data from the Open Data Registry for Amazon Web Services (https://registry.opendata.aws/)
#### COVID-19 Harmonized Data

*https://registry.opendata.aws/talend-covid19/*

Description: 
```COVID-19 Harmonized Dataset```

Resource type: 
```S3 Bucket```

Amazon Resource Name (ARN): 
```arn:aws:s3:::covid19-harmonized-dataset```

AWS Region: 
```us-east-2```

AWS CLI Access (No AWS account required): 
```aws s3 ls --no-sign-request s3://covid19-harmonized-dataset/```

*https://github.com/awslabs/open-data-registry/blob/3762670e9264571d19c14f9dfa5f7b9aedd76f74/datasets/talend-covid19.yaml*


### 3. Business Problem or Opportunity, Domain Knowledge
Because of the nature of the research, the business problem is to illuminate valuable insight into the COVID-19 Pandemic and use the data in AWS' Open Data Registry to draw analyses about COVID-19 impact and effect.

COVID-19 has significantly impacted the way of life for many people across the globe. This dataset is fascinating for multiple reasons since it reveals aggregated data from a number of recognized data sources including the World Health Organization, the New York Times, and US COVID-19 Tracking Project.
The topic is not only relevant but very crucial as COVID-19 is a pandemic effecting many today. The dataset is current and updated twice daily, according to the Registry of Open Data on AWS.

### 4. Research Objectives and Question(s)
I am interested in comparing National and State-level US COVID-19 data, particularly with respect to metadata such as geographic locations, population in states, population among age group, and population by counties. While there are a number of questions which may introduce themselves during my research, the primary nature of the below questions are aimed at analysis and usage by stakeholders such as data scientists and academics but will be presented with an end-user in mind.

~ What are the states with the highest and lowest number of confirmed COVID-19 cases?

~ How do hospitalization and death counts differ throughout the data?

~ At what time were new cases the highest nationally?

~ What statistics can be observed from the dataset?


### Deliverable 2
---

### 5. Data Understanding

 *a)   Exploratory Data Analysis*
 
 Exploratory Data Analysis was done through AWS Sagemaker. View the rendered file here: [Exploratory Data Analysis](Project-Files/AWS-Sagemaker/ExploratoryDataAnalysis.ipynb)

 *b)   Dashboard*

 Dashboard instances were created using AWS Quicksight and rendered as PDF files; however, due to billing limitations, the Dashboard instances are shutdown after analysis. The PDF extracts are available below. Additionally, these dashboards are analyzed in the Results section as a tool for evaluating the research objectives and questions.
 
 [US/National Covid-19 Dashboard PDF Extract](Project-Files/AWS-Quicksight/Dashboard_Analysis_o_2022-04-19T23_34_09.pdf)
 
 [US State-Level Covid-19 Dashboard PDF Extract](Project-Files/AWS-Quicksight/CDC_State_Data_Analy_2022-04-19T23_32_15.pdf)



### 6. Data Preparation
Data preparation was done at all levels of the project, including preliminary analysis of the dataset structures documented in the Open Dataset Registry. Data preparation activities include interpreting column data properly based on the tool being utilized, considering outlier data, invalid values, performing data manipulation, and more. Data preparation activities also included determining the most efficient tool to use in order to answer questions set forth by the research objectives and questions.


### Deliverable 3
---

### 7. Analytics, Machine Learning


### 8. Evaluation and Optimization


### 9. Results


### 10. Future Work, Comments

