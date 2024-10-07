# Data Analysis Project: AMCAT Data Exploration

## Project Overview
This project focuses on analyzing the Aspiring Minds Employment Outcome 2015 (AMEO) dataset, which captures the employment outcomes of engineering graduates across India. With the rising competition in the job market, understanding the factors that influence salary and employability has become increasingly important. The primary objective of this project is to explore how various factors—such as educational qualifications, demographic details, personality traits, and specialization—impact salary levels among engineering graduates. By conducting thorough exploratory data analysis (EDA), this project aims to derive insights that can assist students, educators, and policymakers in making informed decisions about career paths and educational strategies. 

Through a systematic approach, we will examine the data to identify trends, patterns, and relationships that exist within the dataset. The findings from this analysis can serve as a valuable resource for understanding salary determinants in the job market and may contribute to improving job placement strategies for engineering graduates.

### Objectives
- Analyze Salary Influences: Identify and analyze the various factors that significantly influence salary levels among engineering graduates.
- Explore Educational Impact: Investigate how educational qualifications, such as GPA and specialization, affect employability and salary.
- Understand Demographic Factors: Examine the role of demographic factors (age, gender, location) in shaping career outcomes for graduates.

### Significance
- Guidance for Students: Provide actionable insights to help students make informed decisions regarding their educational paths and career choices.
- Support for Educators: Offer valuable data for educators to understand trends in graduate employment and salary levels, helping to enhance curriculum and training programs.
- Policy Implications: Present findings that may inform policy decisions related to engineering education and job placement strategies in India.

## Data Information
The AME data set consists of approximately 4000 data points, each representing an individual engineering graduate. It includes around 40 independent variables, encompassing both continuous and categorical types. Key features of the dataset include dependent variables such as salary, job title, and job location, alongside independent variables that capture cognitive, technical, and personality skills, as well as demographic and educational details. Each row in the dataset is associated with a unique identifier for every candidate, allowing for accurate tracking and analysis.

### Key Features
- Salary: The primary dependent variable indicating the annual salary of each graduate.
- Job Title and Location: Categorical variables that describe the roles and locations of employment.
- Educational Metrics: Variables capturing GPAs, scores from standardized tests, and college tier information.

### Data Quality
- Diversity of Variables: The dataset offers a wide range of features, providing a comprehensive view of the factors affecting graduate employability.
- Potential Data Issues: Preliminary checks for missing values and inconsistencies will be conducted to ensure high-quality analysis.

## Project Structure
The project is organized into several structured sections, each addressing a specific aspect of the analysis. The sections are as follows:

1. Introduction: 
   - This section provides a detailed overview of the project, outlining its goals, objectives, and significance.
   - It sets the context for the analysis by discussing the importance of understanding salary determinants in the engineering job market.
   - We introduce the AME dataset and the various factors it encompasses, which will be the focus of our exploration.

2. Data Loading and Overview: 
   - In this part, we will load the dataset using appropriate libraries, such as Pandas.
   - An initial overview of the data will be presented to familiarize the reader with its structure, dimensions, and the types of features included.
   - By examining the first few rows of the dataset, we can gain insights into its contents and prepare for further analysis.

3. Sanity Check of the Data: 
   - This section is crucial for ensuring the quality and integrity of the dataset.
   - We will perform sanity checks to identify any inconsistencies or anomalies within the data.
   - This involves verifying data types, handling missing values, and addressing any incorrect formats.
   - By ensuring that the dataset is clean and well-structured, we can proceed confidently with the analysis.

4. Univariate Numerical Analysis: 
   - In this section, we will conduct a thorough analysis of each independent numerical feature within the dataset.
   - Various statistical methods and visualizations, such as histograms and boxplots, will be employed to examine the distribution of these numerical variables.
   - Special emphasis will be placed on detecting and removing outliers using techniques such as the Interquartile Range (IQR) and Z-score methods, as they can significantly impact our findings.

5. Univariate Categorical Analysis: 
   - This part focuses on the categorical variables present in the dataset.
   - We will use count plots to analyze the frequency distribution of various categorical features, such as job roles, job locations, educational boards, and gender.
   - Understanding these distributions will provide valuable insights into the demographics and educational backgrounds of the engineering graduates represented in the dataset.

6. Bivariate Analysis: 
   - This section encompasses various types of bivariate analysis aimed at uncovering relationships between two variables:
     - Numerical vs Numerical: We will explore relationships between salary and other numerical features through pair plots and heatmaps. This analysis will help identify correlations and potential factors that significantly impact salary.
     - Numerical vs Categorical: Here, we will analyze how salary varies across different categorical variables. We will employ bar plots and box plots to illustrate the mean salary across various groups, such as college tier, percentage scores, and specializations.
     - Categorical vs Categorical: This part focuses on exploring relationships between different categorical features. We will investigate how specialization relates to common job roles and how degree types correlate with chosen specializations.

7. Research Questions: 
   - This section addresses the key research questions that were formulated at the beginning of the project.
   - We will systematically investigate how the data analysis helps answer these questions and what insights can be drawn from the findings.
   - Each research question will be examined in relation to the relevant analysis conducted in the previous sections.

8. Conclusions: 
   - In this part, we will summarize the key insights drawn from the data analysis, highlighting the most significant findings.
   - We will discuss how various factors—such as educational qualifications and specialization—affect salary outcomes.
   - The conclusions will offer actionable recommendations for students and educators based on our findings.

9. Bonus Insights: 
   - This section presents additional observations and insights that were discovered during the analysis.
   - These insights may include unexpected trends, correlations, or patterns that could contribute to further discussions around engineering graduate employability.
   - The bonus insights aim to provide extra value beyond the main conclusions drawn from the analysis.

## Requirements
This project was developed using Python, and the following libraries are required to run the code:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

## How to Run
1.Install the necessary libraries:
  ```bash
   pip install pandas numpy seaborn matplotlib plotly scipy
   ```
2.Open the Jupyter Notebook file (.ipynb) and run the cells in order to reproduce the analysis.
