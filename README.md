# Heart Disease Data Analysis

## Project Overview
This project focuses on analyzing heart disease data to identify the factors that influence the presence of heart disease in individuals. The goal is to leverage data-driven insights to predict heart disease based on key health indicators, which can assist in early detection and intervention.

## Business Problem
Heart disease is a leading cause of death worldwide, making its early detection critical for healthcare providers. Key challenges include:

- Identifying high-risk individuals based on health data.
- Understanding key factors such as cholesterol levels, maximum heart rate, and fasting blood sugar.
- Using insights to improve medical interventions and preventive care strategies.

The objective is to perform a comprehensive analysis of patient data to predict heart disease presence and uncover actionable health insights.

## Dataset
The dataset contains health records of individuals, with key attributes like age, gender, cholesterol levels, and heart disease indicators.

**The dataset includes the following key features:**
- **Age**: The age of the individual.
- **Sex**: The gender of the individual.
- **Cholesterol levels (chol)**: Measured cholesterol levels.
- **Maximum heart rate achieved (thalach)**: The maximum heart rate achieved during testing.
- **Fasting blood sugar (fbs)**: Whether the individual’s fasting blood sugar is greater than 120 mg/dl.
- **Target**: Indicates the presence (1) or absence (0) of heart disease.

## Tools Used
- **Python**: For data cleaning and exploratory data analysis (EDA).
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For data visualization.
- **Power BI**: For creating interactive dashboards and advanced visualizations.

## Data Preparation
- **Data Type Conversions**: Converted numerical and categorical columns into appropriate formats for analysis.
- **Handling Missing and Zero Values**: Ensured no missing or erroneous values existed in critical columns.
- **Outlier Detection and Removal**: Detected and removed outliers in health indicators such as cholesterol and maximum heart rate to ensure more accurate results.

## Key Metrics
- **Target Variable**: The presence or absence of heart disease (1 indicates heart disease, 0 indicates no heart disease).
- **Key Indicators**: Age, cholesterol levels, maximum heart rate achieved (thalach), and fasting blood sugar.
- **Sex Distribution**: Data contains patients of both sexes, and sex is analyzed as a potential factor for heart disease.

## Analysis Insights
### Age and Heart Disease
- Heart disease is more prevalent in individuals aged **40-60**, with a significant peak between ages **50 and 60**.
- The highest concentration of heart disease cases was seen between ages **50-60**, suggesting this as a critical age range for screening.

### Cholesterol Levels
- Higher cholesterol levels tend to correlate with the presence of heart disease. Individuals with cholesterol levels above **250 mg/dl** are at a higher risk.
- Cholesterol levels between **200-300 mg/dl** are associated with most heart disease cases, indicating a key risk factor.

### Maximum Heart Rate (thalach)
- The maximum heart rate achieved tends to decrease as age increases. The dashboard's line graph shows a clear downward trend after the age of **40**, with the most significant decreases between **50-60**.
- Individuals with lower maximum heart rates are more likely to have heart disease, making cardiovascular health a crucial area for monitoring.

### Gender
- Male patients have a slightly higher prevalence of heart disease than female patients in this dataset.
- The dashboard shows that males are more prone to heart disease, particularly between the ages of **40-60**. Gender-specific health interventions may be necessary.

### Fasting Blood Sugar (fbs)
- Higher fasting blood sugar levels (**fbs > 120 mg/dl**) are associated with an increased risk of heart disease. However, **27.01%** of cases are linked to elevated blood sugar levels, indicating that it is a secondary but important risk factor compared to cholesterol and heart rate.

## Recommendations
### Targeted Health Screening
- Focus on early heart disease detection in individuals aged **40-60**, especially those with elevated cholesterol levels.

### Cholesterol Management
- Promote programs for lowering cholesterol, particularly for individuals with levels exceeding **250 mg/dl**.

### Exercise and Heart Health
- Encourage physical activities that improve cardiovascular health, especially for individuals with low maximum heart rates.
- Patients aged 50+ should focus on maintaining a healthy heart rate through exercise.

### Blood Sugar Control
- Implement stricter monitoring of fasting blood sugar levels in at-risk individuals to prevent heart complications.

### Gender-Specific Health Campaigns
- Design awareness campaigns tailored to both men and women, with a focus on prevention strategies for those showing early risk factors.
- **Men aged 40-60** should be the focus of targeted campaigns since they have a slightly higher risk based on the data.

## Limitations
- **Data Size**: The dataset is limited in size, which may affect the generalizability of the insights. A larger dataset would allow for more robust conclusions.
- **Time Frame**: The analysis is based on static data and does not account for changes over time in patient health or medical interventions.
- **External Factors**: Factors such as lifestyle, family history, and medication use were not accounted for, which could influence heart disease risk.

## Conclusion
The **Heart Disease Data Analysis** provides valuable insights into how various health metrics such as age, cholesterol levels, and maximum heart rate are linked to heart disease. The analysis reveals that individuals aged **40-60**, especially those with high cholesterol and low maximum heart rates, are at higher risk. By focusing on these factors, healthcare providers can better identify at-risk individuals and design personalized prevention and treatment plans to reduce the incidence of heart disease.
