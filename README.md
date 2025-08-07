# India Suicide Data Visualization

## Overview
This repository contains a data visualization project analyzing suicide trends in India from 2001 to 2012. The project explores demographic patterns, regional differences, and risk factors influencing suicide rates across various dimensions such as age, gender, state, education, profession, and social status. Through descriptive analytics and visualizations, the project aims to provide actionable insights for stakeholders, researchers, and policymakers to support culturally-sensitive and data-informed suicide prevention strategies.

## Project Objectives
- Analyze and visualize suicide trends in India using a dataset spanning 2001–2012.
- Identify key demographic patterns and risk factors, including age, gender, state, education, profession, and social status.
- Investigate major causes and methods of suicide and their variations across demographics.
- Develop intuitive visualizations to communicate findings effectively to diverse audiences.
- Support the creation of targeted mental health interventions and prevention strategies.

## Dataset
The dataset, sourced from the National Crime Records Bureau (India), includes 12 years of observations (2001–2012) on suicides, natural and unnatural accidents, and traffic accidents. Key variables include:
- **Time Period**: 2001–2012
- **Demographics**: Age, gender, education, profession, social status
- **Geographical Data**: State-wise suicide records
- **Causes of Suicide**: Family problems, illness, bankruptcy, etc.
- **Methods of Suicide**: Hanging, insecticide consumption, firearms, etc.

The dataset was cleaned and preprocessed to handle missing or inconsistent data, with normalization applied where necessary (e.g., adjusting for population differences).

## Project Structure
The project is organized as follows:
- **Data Cleaning and Preprocessing**: Handling missing data, standardizing column names, and normalizing figures for fair comparisons.
- **Data Segmentation**: Dividing the dataset by categories such as education, profession, social status, and causes.
- **Clustering**: Grouping similar data points (e.g., job roles, education levels) for analysis.
- **Visualizations**: Creating static and interactive visualizations, including:
  - Year-wise suicide trends
  - Age and gender breakdowns
  - State-wise comparisons
  - Education, profession, and social status impacts
  - Cause and method analyses
- **Tools Used**: [Specify tools, e.g., Python (Pandas, Matplotlib, Seaborn), R, or Tableau, if applicable]
- **Outputs**: Visualizations include bar charts, line graphs, and stacked visuals for intuitive storytelling.

## Key Findings
1. **Overall Trends**: Suicide rates in India were stable from 2001–2004, dipped in 2005, peaked in 2010, and declined in 2011–2012, suggesting improvements in awareness or policy interventions.
2. **Age and Gender**: Contrary to the hypothesis that males are always more prone to suicide, females in the 0–14 age group showed higher rates. The 30–45 age group is the most vulnerable overall.
3. **State Variations**: Southern states like Tamil Nadu, Kerala, and Karnataka have high suicide rates despite high education levels, indicating other socio-economic factors at play.
4. **Education and Gender**: Lower education levels correlate with higher suicide rates, with women more affected among the uneducated.
5. **Profession**: Farming/agriculture, housewives, self-employed, private service, and unemployed groups face elevated suicide risks due to financial, societal, and emotional pressures.
6. **Social Status**: Married individuals, especially men, show higher suicide rates, challenging the notion that marriage is a protective factor.
7. **Causes and Methods**: Family problems and illness are major causes. Hanging is the most common method, but insecticide consumption and firearms dominate in specific states like Andhra Pradesh and Uttar Pradesh, respectively.
8. **Attempters vs. Completers**: Middle-aged, unemployed, married men and housewives are at high risk for both attempts and completions.
9. **Location**: Most suicides occur at home, particularly among women, while men are more likely to choose outdoor locations.

## Research Questions and Hypotheses
The project addressed key questions, including:
- What are the overarching suicide trends in India from 2001–2012?
- Which states have the highest/lowest suicide rates?
- How do age, gender, education, profession, and social status influence suicide rates?
- What are the most common causes and methods of suicide?

Tested hypotheses include:
- Males are more likely to commit suicide than females (partially rejected due to higher female rates in the 0–14 age group).
- Lower education levels increase suicide risk, especially for women (accepted).
- Married women are at higher risk than unmarried women (partially accepted).
- Men are more affected by financial issues, women by family issues (accepted).
- Men use more lethal suicide methods than women (accepted).

## Visualizations
The project includes a mix of static and interactive visualizations:
- **Year-wise Trends**: Line graphs showing suicide rates and totals over time.
- **Age and Gender Analysis**: Bar charts and stacked visuals for demographic breakdowns.
- **State-wise Comparisons**: Choropleth maps or bar charts highlighting regional differences.
- **Cause and Method Analysis**: Pie charts or bar graphs showing distributions.
- **Education and Profession**: Stacked bar charts linking education/profession to suicide rates.

## Prevention Recommendations
Based on the findings, the project suggests:
1. **Address Root Causes**: Tackle unemployment, gender inequality, and mental health issues.
2. **Medical and Psychological Care**: Promote early detection, therapy (e.g., DBT), and follow-up care for attempters.
3. **Targeted Support**: Provide debt relief for farmers, counseling for students, and domestic violence prevention for women.
4. **Community Awareness**: Foster empathy and open conversations to reduce mental health stigma.
