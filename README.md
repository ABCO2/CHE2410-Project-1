# The Impact of Diabetes Percentage and Human Development Index (HDI) on COVID-19 Death Cases in 2020: A Study on Global Trends


## Introduction and Background
The COVID-19 pandemic has caused widespread devastation across the globe, leading to significant loss of life and economic damage. While the virus affects people of all ages, it has been observed that people with preexisting health conditions such as diabetes are at a higher risk of developing severe symptoms and complications. Additionally, the Human Development Index (HDI) of a country plays a major role in determining its ability to prevent, diagnose, and treat COVID-19 cases. Therefore, understanding the relationship between diabetes percentage, HDI, and COVID-19 death cases is crucial in devising effective strategies to combat the pandemic.

To begin the data analysis, various sources were consulted and data was collected for each country's diabetes percentage, human development index (HDI), and death rate. The data was then compiled into an Excel sheet. To make it more manageable, the diabetes percentage and HDI data were grouped into separate columns based on their respective means; values higher or equal to the mean were assigned a value of 1 whereas lower values were assigned a value of 0. This process was repeated for both the diabetes percentage and HDI variables. 

In this study, we conduct a comprehensive analysis by applying OLS regression methodology to determine if countries with a high percentage of diabetes patients have a higher COVID-19 death count and if the same is true for countries with a low HDI rating. OLS stands for Ordinary Least Squares. OLS is a method used in regression analysis to estimate the parameters of a linear model by minimizing the sum of the squared differences between the observed dependent variable and the predicted values of that variable. It is commonly used in social science research, economics, engineering, and other fields to analyze the relationship between predictor variables and a response variable of interest. By analyzing the interaction variable (diabetes percentage*HDI), this study sheds light on the complex relationship between diabetes, HDI, and COVID-19 death cases, which can guide us in implementing targeted interventions to reduce COVID-19-related morbidity and mortality.

Human Development Index (HDI) is a composite statistic that was developed by the United Nations Development Programme (UNDP) to measure and rank countries based on their social and economic progress. The HDI takes into account three dimensions of human development: living standards, education, and health. Living standards are measured by a country's Gross National Income (GNI), which is adjusted for inflation and divided by the population. Education is measured by the average years of schooling of adults aged 25 years and over and the expected years of schooling of children. It provides insights into the quality of life of people in different countries [[1]](https://hdr.undp.org/content/human-development-report-2020).
The data utilized in this study was extracted from the [COVID-19 Open Data Repository](https://health.google.com/covid-19/open-data/raw-data) and the [WHO COVID-19 Dashboard](https://data.humdata.org/dataset/coronavirus-covid-19-cases-and-deaths).

![image](https://github.com/ABCO2/CHE2410-Project-1/assets/144171865/696a255c-f7bd-4718-b795-71c04b865852)

![image](https://github.com/ABCO2/CHE2410-Project-1/assets/144171865/843b0bad-2407-42be-9778-22504cd8aecc)

![image](https://github.com/ABCO2/CHE2410-Project-1/assets/144171865/c090f200-7b2a-4fb2-9a4d-fbcf8e49ba42)

### The table below shows the countries' key:
![image](https://github.com/ABCO2/CHE2410-Project-1/assets/144171865/9387524d-7a07-4a42-8b9d-b430a5efc50d)

Figure 1 shows the percentage of persons with diabetes in each country. Figure 2 shows the Human Development Index in each country. Figure 3 shows the death rate im each country. The table above shows the countries' key.
## Result and Discussion


## Conclusion
Based on the OLS regression analysis, it can be concluded that HDI has a significant positive impact on COVID-19 death cases, while Diabetes Percentage does not have a significant impact. The interaction between Diabetes Percentage and HDI also has a negative impact on COVID-19 death cases, but it is not significant at the conventional level (p-value=0.075). Therefore, it can be concluded that higher levels of HDI are associated with higher COVID-19 death cases, while the impact of Diabetes Percentage is not significant in explaining the variation in COVID-19 death cases.

It is important to note that the accuracy and reliability of the data used in the analysis can significantly impact the findings and conclusions drawn from the study. Also, in this study, diabetes was considered as one factor, and there are two types of diabetes. It is crucial to consider that type 1 and type 2 diabetes have distinct pathophysiological mechanisms, clinical features, and risk factors.

In conclusion, while the analysis presented in the study provides some insights into the potential association of diabetes and HDI with COVID-19 death rates, further research is needed to investigate the complex relationships between these factors and the disease. 

## Recommendation
There are also other parameters that can be considered in order to improve this study. For example, older age is a well-established risk factor for severe COVID-19 disease and death. Obesity is another well-established risk factor for severe COVID-19 disease and death. Furthermore, several genetic variants have been identified that may contribute to the risk of severe COVID-19 disease instead of analytical data. Also, studying each type of diabetes separately can provide valuable insights into the impact of diabetes on COVID-19 outcomes. There are other important factors to consider that can also improve the study. Focusing on countries that have high credibility requirements for their record-keeping systems. Also, the methodology used for grouping the data should possibly be modified to ensure relevancy.

