# Health disease risk analysis
### Table of Content
 - [Project overview](project-overview)
 - [Data source](data-source)
 - [Tools](tools)
 - [Data cleaning and preparation](data-cleaning-and-preparation)
 - [Exploratory data analysis](exploratory-data-analysis)
 - [Data analysis](data-analysis)
 - [Results](results)
 - [Recommendations](recommendations)
 - [References](references)

### Project overview
To have a better understanding on how demographic and clinical factors influence heart diseases to improve  preventive strategies.
### Data source
The primary dataset used for this analysis is the 'heart disease dataset.csv' file from kaggle
  - [download here](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
 ### Tools
  - Microsoft Excel- Data cleaning
  - Power BI- Data Visualization and Creating Reports
### Data cleaning and Preparation
In the initial phase of data preparation, i did the following:
1. Data loading and inspection
2. Handle Missing values
3. Check for duplicates
### Exploratory Data Analysis
1. Identify patterns associated with heart disease
2. Monitor high-risk patient characteristics
3. Evaluate clinical indicators linked to disease presence
### Data Analysis
    some basic features used
          --- Power Bi
              totalpatients= countrows('heart')
              heartdiseaserate = divide([totalheartdisease],[totalpatients],0)
           ---
### Results
1. patients between 45years to 59 years have the highest record of heart disease risk by 85 cases
2. patients with chest pain type 2(high) have the highest record of heart disease risk by 68 cases
3. 75% of female population have heart disease cases while 45% of the male population have heart disease cases
4. patients with zero number of vessels have the highest record of heart disease risk by 130 cases
5. The average maximum heart rate is higher in patients with heart disease status 2(reversable defects) by 151 cases
### Recommendations
 1. The hospital management can focus more heart preventive routines in women
 2. The management can also organize special programs for individuals between 45years to 59 years
 3. More awareness could be organized for chest pain
### References
Kaggle heart disease dataset

  
