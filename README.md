# Examining the Relationship of GDP on Life Expectancy: A Global Perspective

This project, completed as part of the MSc Data Analytics programme at the University of Glasgow (2023-24), investigates the relationship between life expectancy at birth and Gross Domestic Product (GDP) across countries in 2021. Data was sourced from Our World in Data (https://ourworldindata.org/) under the Poverty and Economic Development theme. The analysis explores the linear association between life expectancy and GDP, incorporating the potential influence of continents. It includes:
- **Data Wrangling and Exploratory Data Analysis (EDA)** in R, with graphical and numerical summaries of life expectancy, GDP, and geographical regions.
- **Formal Data Analysis** in Python, featuring regression modeling. A multiple regression model with parallel slopes was determined to be the best fit.


## Files and Structure
- **R Folder**:
  - `eda_and_wrangling.qmd`: Quarto markdown file for Data Wrangling and Exploratory data analysis.
  - `eda_and_wrangling.pdf`: PDF version of the EDA.
- **Python Folder**:
  - `formal_analysis_and_validation.ipynb`: Notebook for Formal Analysis, model comparison and validation and conclusion.
- **Google Colab**: Formal analysis notebook can also be accessed [here](https://colab.research.google.com/drive/1qH4r2_tzG0y7dqGfwTvmfoqtNIYwKloI#scrollTo=zBPJa5sfywVm).

## Tools and Techniques
- **Languages**: R, Python
- **Techniques**: Regression Analysis, OLS, Data Validation, Visualization
- **Libraries**: 
  - **R**: 
    - `ggplot2`  
    - `tidyverse`  
    - `dplyr`  
    - `readr`  
    - `stringr`  
    - `countrycode`  
    - `skimr`  
    - `moderndive`  
    - `gt`  
    - `gridExtra`
  - **Python**: 
    - `pandas`  
    - `numpy`  
    - `matplotlib.pyplot`  
    - `seaborn`  
    - `statsmodels.formula.api` (for OLS)  
    - `scipy.stats` (for statistical functions)

## Insights
The multiple regression model with parallel slopes emerged as the most appropriate for this analysis. Results indicate a statistically significant positive relationship between life expectancy and GDP. Additionally, the analysis reveals that geographical regions (continents) play a notable role in influencing life expectancy outcomes.
