# WHO

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview
---
This project analyzes global health trends using World Health Organization (WHO) data, focusing on life expectancy, child mortality, and literacy rates across different regions. The visualizations, created using Tableau, highlight disparities in healthcare access and outcomes worldwide.
- Key Insights:
  - A choropleth map illustrating global life expectancy and population distribution.
  - A bar chart showing child mortality rates by region, revealing significant variations.
  - A line chart comparing trends in life expectancy, child mortality, and literacy rates across regions.
 
### Data Sources
The primary dataset used for this analysis is the "WHO.csv" file, containing comprehensive global health statistics

### Tools Used
- Google Spreadsheet : Data cleaning [Download here](https://google-sheets.en.softonic.com/)
- Tableau : Data visualization and dashboard creation [Download here](https://www.tableau.com/products/desktop/download)

### Data Cleaning and Preparation
In the data preparation phase, I performed the following task:
1. Data loading and inspection
2. Handling null rows
3. Handling duplicate values
4. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the WHO dataset to answer key questions, such as:
- How is life expectancy distributed globally?
- Which region has the highest child mortality rate?
- How do child mortality, life expectancy, and literacy rates vary by region?
- Which regions have the lowest child mortality rates?
- Is there a visible trend between life expectancy and literacy rate?

### Results and Findings

The analysis results are summarized as follows:
1. Global Life Expectancy Trends:
  - Life expectancy varies significantly across regions, with developed countries showing higher values and developing countries having lower life expectancy.

2. Child Mortality Rate by Region:
  - Africa has the highest child mortality rate (3,866), significantly surpassing all other regions.
  - South-East Asia (386), Europe (533), and the Western Pacific (667) have the lowest child mortality rates.

3. Regional Trends in Life Expectancy, Child Mortality, and Literacy Rate:
  - A clear pattern emerges where regions with higher literacy rates tend to have higher life expectancy and lower child mortality.
  - Europe exhibits the highest life expectancy, while Africa has the lowest.

### Recommendations
Based on the analysis, I recommend the following actions:
1. Improve Healthcare Access in High Mortality Regions
 - Increase investment in healthcare infrastructure, especially in Africa, to reduce child mortality rates.
 - Expand immunization programs and maternal healthcare services.
2. Promote Education and Literacy Programs
  - Strengthen literacy programs, particularly in regions with low education levels, as higher literacy rates are linked to better health outcomes.
3. Government and Policy Interventions
  - Implement policies that promote economic development and access to quality healthcare in developing regions.
  - Encourage international organizations and governments to collaborate on health initiatives.
4. Public Awareness Campaigns
  - Raise awareness about the importance of maternal and child healthcare through community engagement programs.
5. Further Research and Data Monitoring
  - Regularly update and analyze health-related data to track progress and make data-driven decisions


### Limitations
While this project provides valuable insights, there are some constraints to consider:
- Data Completeness: Some countries have missing or outdated data, which may affect accuracy.
- Generalization: Findings are based on regional trends and may not fully represent country-specific differences.
- Scope: The analysis focuses on life expectancy, child mortality, and literacy rates, without considering other critical health factors.
- Visualization: The dashboard highlights key trends but does not capture deeper statistical relationships.
- Data Source: The dataset is sourced from Kaggle, and its accuracy depends on the original provider.
  
Despite these limitations, this project offers meaningful insights and can be improved with more recent data, additional variables, and deeper statistical analysis.

### References
World Health Dataset : [WHO.csv](https://www.kaggle.com/datasets/econdata/who-dataset)
