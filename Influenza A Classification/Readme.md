# Introduction
The study utilizes two substantial datasets: one from the World Health Organization (WHO) containing global Influenza A epidemiological data from 2003 to 2023 and the other encompassing Influenza A infections in New York counties from 2009 to 2019. Both datasets underwent pre-processing, with essential features selected to develop an XGBoost Classification model for forecasting Influenza A cases in humans.

# Dataset

1. Country.csv was sourced from World Health Organization (WHO)
* Cumulative number of confirmed human cases for avian influenza A(H5N1) reported to WHO, 2003-2023, 5 January 2023
* WHO publishes information on human cases with influenza A(H5N1) avian influenza infection on a monthly basis on  
  the Influenza webpage

2. NYFull.csv (https://www.kaggle.com/datasets/titustitus/h1n1-new-york-2009)
* The dataset contains weekly information of infections (positive test) in New York Counties during the period Oct 2009-Mar 2019. The months studied are Jan, Feb, Mar, Apr, May, Oct, Nov, Dec.
* There are included other variables by County like the amount of hospital beds, unemployment rate, population, average income, Median age,Total expenditure per Year in hospital interventions.

# Methodology

In our methodology, we employ the XGBoost classifier to predict Influenza-A infections, utilizing its renowned capabilities in handling imbalanced datasets. We gather data from the Avian Influenza A(H5N1) dataset and additional New York county data. Following rigorous data pre-processing, including cleaning, feature engineering, normalization, and partitioning, we leverage XGBoost's algorithmic strengths in gradient boosting, regularization, and imbalanced data handling. Through our data processing and analysis, we train and evaluate the XGBoost models, achieving impressive accuracy in classifying the severity of epidemiological events based on provided features.

# Conclusion

Through the seamless integration of XGBoost, the healthcare sector embarks on a transformative journey towards more effective treatment assessments and strategic advancements in combating Influenza-A outbreaks.

#Find the Conference Paper on IEEE Xplore
https://ieeexplore.ieee.org/document/10503406
